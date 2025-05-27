# CMSC-201-Project-11-solution

Download Here: [CMSC 201 Project # 11 solution](https://jarviscodinghub.com/assignment/cmsc-201-project-11-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Concepts Tested in this Program:
● JavaFX Platform
● Design GUI (Graphic User Interface) using JavaFX framework
Program:
(Plot the sine and cosine functions) Write a program that plots the sine function in red and cosine in blue, as shown in Sample Run #1
Hint: The Unicode for π is \u03c0 . To display −2π, use Text(x, y, “-2\u03c0”) . For a trigonometric function like sin(x) , x is in radians. Use the following loop to add the points to a polyline:

Polyline polyline = new Polyline();
ObservableList list = polyline.getPoints();
double scaleFactor = 50;
for (int x = -170; x <= 170; x++) { list.add(x + 200.0); list.add(100 – scaleFactor * Math.sin((x / 100.0) * 2 * Math.PI)); } Name your class as Project11 and file as Project11.java Sample Run #1 Project 11 Submission requirements: Deliverables: ● Java files (source code) ● Word document should include your screen snapshots of outputs ● Algorithm ● UML ● Flowchart ● Javadoc Deliverable format: The above deliverables should be packaged in two compressed files in the following format. 1. FirstInitialLastName_Project11_doc.zip [a compressed file containing the following] FirstInitialLastNamePr11.docx 2. FirstInitialLastName_Project11_Moss.zip [a compressed file containing only the following] Your completed assignment should be submitted on Blackboard ->Course Content-> Week xx->”Project 11″ no later than the assigned due date. You should include one block comment at the top of each program containing the course name, the project number, your name, the date and platform/compiler that you used to develop the project, for example
/*
* Class: CMSC201
* Instructor:
* Description: (Give a brief description for each Program)
* Due: MM/DD/YYYY (<05/03/2017>)
* I pledge that I have completed the programming assignment independently.
I have not copied the code from a student or any source.
I have not given my code to any student.
Print your Name here: __________
*/
Grading Criteria for Project 11 for each Program
The following are components on which the projects will be graded
Attributes Points
Program Layout
● Proper naming conventions 4 pts
● Documentation 4 pts
● Indentation 2 pts
Total 10 pts
Program Design
● Modularity: Proper use of parameters, use of local variables etc. 5 pts
● Proper class design, Correct & appropriate use of programming structures (loops, conditionals, classes etc.) 5 pts
● Algorithms 5 pts
● UML 5 pts
● Javadoc 5 pts
● Flowchart 5 pts
●
Total 30 pts
Test Data
●
● Screenshots of good test data based on a Test Plan 10 pts
Total 10 pts
Functionality
● Program compiles 20 pts
● Program executes correctly on all test data 15 pts
● Meets all requirements 15 pts
Total 50 pts
Total Grand Total 100 pts

Notes:
o Proper naming conventions: All constants, except 0 and 1, should be named. Constant names should be all uppercase, variable names should begin in lower case, but subsequent words should be in title case. Variable and method names should be descriptive of the role of the variable or method. Single letter names should be avoided.
o Documentation: The documentation requirement for all programming projects is one block comment at the top of the program containing the course name, the project number, your name, the date and platform/compiler that you used to develop the project. If you use any code or specific algorithms that you did not create, a reference to its source should be made in the appropriate comment block. Javadoc comments should be made throughout the program where appropriate as well.
o Indentation: It must be consistent throughout the program and must reflect the control structure.
For more examples on documentation please refer to the online template.
