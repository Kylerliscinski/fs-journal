# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > Starting with a namespace will allow your other files to all be able to connect ot eachother. Without using it, you would have to "use" the method in each folder you want to talk to eachother.

02. What is the difference between a `class` and an `interface`?

  > A class describes the behavior of objects. The interface carries out the behaviors.

03. What is the method that returns an instance of a class, yet it has no return type?

  > Void

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

  > public

06. In the Car example what is `string` an indication of?

  > It is the method

07. In the Car example what is `abstract` preventing?

  > It makes it so that you cannot create an object from the car class.

08. In a SQL table, what is the difference between information in a row and information in a column?

  > A row will contain all of the information about something, like an account. A column will be a specific property from the row, like the name of the account.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE characters (
  > id INT NTO NULL PRIMARY KEY AUTO_INCREMENT,
  > name VARCHAR(255) NOT NULL,
  > age INT NOT NULL,
  > description VARCHAR(500)
  > );
  > INSERT INTO
  > characters (
  > name,
  > age,
  > description
  > )
  > VALUES(
  > "Kyler",
  > "23",
  > "Chill guy idk"
  >  );

10. In SQL how can you query more than a single table? Provide an example.

  > Yes, you need to join the two methods. You can join "accounts" with "cars".
