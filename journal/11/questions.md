# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > It allows you to create classes that reuse and modify other classes.

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > A class that has inherited members is rerfered to the base class. No it wouldn't, if you had 3 classes, class 3 derives from class 2, and class 2 derives form class 1 whcih means class 3 inherits the properies of all of them.

3. How does ***accessibility*** affect inheritance?

  > If you have a private class, it is only accessible to whatever section it is in.

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > A primary key is a unique identifierin a table like "id". A foreign key creates a relationship between tables by referencing the primary key of another table like a "creator."

5. What is an ***alias***?

  > An alias is something you can use throughout your code like "namespace."

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

  >   SELECT
      doctors.*,
      patients.*
      FROM doctors
      JOIN doctora ON patients.doctorsId = doctors.id;";
