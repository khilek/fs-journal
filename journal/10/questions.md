# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > A way of presenting program elements that are exposed to other programs
  
02. What is the difference between a `class` and an `interface`?

  > An interface is a class without fields or method implementation. It cannot implement the methods it defines. A class generally implements the methods defined in an interface

03. What is the method that returns an instance of a class, yet it has no return type?

  > void

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > Public

06. In the Car example what is `string` an indication of?

  > A string that can be accessed from outside the class

07. In the Car example what is `abstract` preventing?

  > A class that is incomplete and cannot be used to create objects. A base for other classes to inherit form

08. In a SQL table, what is the difference between information in a row and information in a column?

  > Columns are vertical, and hold a list of values all from the same field. Rows are your horizontal elements in a table.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE IF NOT EXISTS characters(
    id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    age VARCHAR(255) NOT NULL,
    description VARCHAR(1000)
  )

10. In SQL how can you query more than a single table? Provide an example.

  >     string sql = @"
      SELECT
      houses.*,
      accounts.*
      FROM houses
      JOIN accounts ON accounts.id = houses.creatorId
      WHERE houses.id = @houseId;";
