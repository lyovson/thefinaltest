# Instructions

1. Fork this repo to your GitHub account
2. Clone the fork to your computer
3. Create a Class Person with following fields and methods:
   - name -> string
   - lastName -> string
   - age -> number
   - adult -> boolean
   - introduce -> a method, that Greets and tells the Person's name. Example -> "Hi, I'm Sasha!"
   - greet -> a **_static method_**,that takes another Person or a class which extends Person class and Greets them using their name. Example -> "Hi Mark, nice to meet you!"
4. Create a class Wizard that inherits from Person and has following fields and methods:
   - level -> number
   - bless -> a method that returns the string "Expecto Patronum!"
   - curse -> a method that returns the string "Avada Kedavra!"
5. Create a class Student that inherits from the class Wizard and has following fields and methods:
   - house -> string
   - credits -> number
6. Create new students based on the info in [Students.js](./students.js) app and add them to an array called students.
7. Find the average credit of all students and save it in a variable "hogwards".
8. Find the average credit of every house and save it in respective variables "griffindor", "slytherin", "hufflepuff" and "ravenclaw".
9. Create a file named index.html with following inormation:
   - Title "Hogwards Average Credits"
   - Heading, Same as the title, centered
   - The names of the Student with the best credit and The House with the best average
   - 4 cards with house names as headings and individual student's names and scores,as well as the house average score. On bigger screens the layout should be horizontal.
   - The average of all students with the text "Hogwards Average".

Bonus points if the site is beautiful.

Good Luck!
