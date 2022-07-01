<a name='Top'></a>
# Class Roster (School Project)

## Table of Contents
- [About this Project](#About)
  - [Project Scenario](#Scenario)
  - [Built With](#BuiltWith)
- [Usage](#Usage)
  - [Requirements](#Requirements)
- [The Program](#TheProgram)
  - [Classes](#Classes)
  - [Algorithms](#Algorithms)
- [Additional Information](#AddInfo)
<br>

<a name='About'></a>
### About this Project
This project was completed for my Scripting and Porgamming Applications course at WGU.

<a name='Scenario'></a>
#### Project Scenario
The given scenario for the project:

_You are hired as a contractor to help a university migrate an existing student system to a new platform using C++ language. Since the application already exists, its requirements exist as well, and they are outlined in the next section. You are responsible for implementing the part of the system based on these requirements. A list of data is provided as part of these requirements. This part of the system is responsible for reading and manipulating the provided data._

_You must write a program containing two classes (i.e., Student and Roster). The program will maintain a current roster of students within a given course. Student data for the program include student ID, first name, last name, email address, age, an array of the number of days to complete each course, and degree program. This information can be found in the “studentData Table” below. The program will read a list of five students and use function calls to manipulate data (see part F4 in the requirements below). While parsing the list of data, the program should create student objects. The entire student list will be stored in one array of students called classRosterArray. Specific data-related output will be directed to the console._

<a name='BuiltWith'></a>
#### Built With
This program was built using C++ with no additional imported libraries.
The project environment was on Windows 10 using Visual Studios Code

<a name='Usage'></a>
### Usage
In order to run the program, you must have a GNU C++ Compiler (g++). Make sure the header and implementation files are in the same directory as main.cpp

For Windows:
The easiest way to run this program on Windows is through Visual Studios Code or using a Linux Virtual Machine.
For Linux: 
Once all the files are in the same directory including the makefile, just run the make command in the terminal.

<a name='Requirements'></a>
#### Requirements
Other than a C++ compiler, there are no specific requirements to run this program.

<a name='TheProgram'></a>
### The Program
The following steps describe what main.cpp should produce.
1. Print out to the screen, via your application, the course title, the programming language used, your WGU student ID, and your name.
2. Create an instance of the Roster class called classRoster.
3. Add each student to classRoster.
4. Convert the following pseudo code to complete the rest of the main() function:

    ```classRoster.printAll();
    classRoster.printInvalidEmails();

    //loop through classRosterArray and for each element:
    classRoster.printAverageDaysInCourse(/*current_object's student id*/);
    classRoster.printByDegreeProgram(SOFTWARE);

    classRoster.remove("A3");
    classRoster.printAll();
    classRoster.remove("A3");
    //expected: the above line should print a message saying such a student with this ID was not found.```

5. Implement the destructor to release the memory that was allocated dynamically in Roster.

<a name='Classes'></a>
#### Classes


<a name='Algorithms'></a>
#### Algorithms

<br>

<a name='AddInfo'></a>
### Additional Information
This project was required for my Scripting and Programming Applications Course at WGU
**Initiated** on March 14, 2021
**Completed** on March 17, 2021


[Back to the Top ↑↑↑↑↑](#Top)
