# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > Synchronous code runs from top to bottom of the page, no matter what
  Asynchronous code will do essentially the same but actually stop to take the time to await user input where indicated in the code

02. What is an event listener?

  > Listens for changes or actions taken in

03. What does *REST* stand for, and in simple terms what does it mean??

  > REpresentational State Transfer
  
  The server will transfer to the client a representation of the state of the requested resource.

04. What is a callback / higher order function?

  > Functions that operate on other functions, either by taking them as arguments or by returning them

05. What is a `promise`? How do you capture an error from a `promise`?

  > A promise is a promise that promises to do  or await on a certain interaction from typically from user input

  Use Catch (error)
  Pop.toast("Specific Error", 'error')
  console.error(error)

06. Name three processes used to make requests over `HTTP`?

  > Get, Post & Put

07. What does the `API` acronym stand for?

  > Application Programming Interface

08. What must you do in order to `await` a promise inside of a function?

  > Use 'async' at the beginning of the said function and then use 'await' in appropriate place

09. What is the purpose of encapsulation in programming?

  > Limits direct access to some data, like an objects components . Also, bundling of data with the methods that operate on that data, cleaner code. Makes code private, preventing unauthorized parties direct access.

10. What is `HTTP` response code for a successful request?

  > 200

11. What is a 400 error?

  > Bad Request
