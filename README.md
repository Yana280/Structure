# Structure

## 1.Student Details
 This is a C program that defines a struct called student, which has three members: name (a string), roll (an integer), and marks (a floating-point number).

In the main() function, the program prompts the user to enter the information of a student by using printf() statements to display messages. 
It then reads in the user input for the student's name, roll number, and marks using scanf().

After the input is obtained, the program prints out the information that was entered using printf() statements that access the members of the s structure variable. 
The information displayed includes the student's name, roll number, and marks.

Finally, the program returns 0 to indicate successful completion of the program.

### Algorithm
Start

Declare struct student s

Print "Enter The Information of Students :"

Print "Enter Name : "
Read s.name

Print "Enter Roll No. : "
Read s.roll

Print "Enter marks : "
Read s.marks

Print "Displaying Information"

Print "Name: " + s.name
Print "Roll: " + s.roll
Print "Marks: " + s.marks

Return 0

Stop

