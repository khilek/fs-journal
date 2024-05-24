# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > Bringing in and using other properties from other models

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > Inheritance enables you to create new classes that reuse, extend, and modify the behavior defined in other classes

3. How does ***accessibility*** affect inheritance?

  > A members accessibility affects its visibility for derived classes

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > FOreign key references a different table while a primary is key is specific to that table

5. What is an ***alias***?

  > idk what context this is meant to be used in but a temporary name used on a table or column.

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > select doctors.*, patients.*  from patient_doctors
