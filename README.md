# Structure

## 1.Student Details
 This is a C program that defines a struct called student, which has three members: name (a string), roll (an integer), and marks (a floating-point number).

In the main() function, the program prompts the user to enter the information of a student by using printf() statements to display messages. 
It then reads in the user input for the student's name, roll number, and marks using scanf().

After the input is obtained, the program prints out the information that was entered using printf() statements that access the members of the s structure variable. 
The information displayed includes the student's name, roll number, and marks.

Finally, the program returns 0 to indicate successful completion of the program.
![Screenshot (290)](https://user-images.githubusercontent.com/125993593/234148294-66633a37-4843-4661-a35b-381edbc1d9d9.png)


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

## 2.Student details for 10 students
This program reads information about 10 students and stores it in an array of structs named "s".
Each student has a name, roll number, and marks.
it displays the details of 10 students at the same time and not just one students details
In the for loop, the roll number is initialized and then the program prompts the user to enter the name and marks of the student.
The scanf function is used to read the name and marks entered by the user and store them in the appropriate fields of the current struct in the array.

After reading the information of all 10 students, the program uses another for loop to display the information of each student on the console. The printf function is used to display the roll number, name, and marks of each student.

 puts function is used to display the name of each student instead of printf because it is a string and contains spaces that would be truncated if printf is used.
 ![Screenshot (291)](https://user-images.githubusercontent.com/125993593/234149489-8ee7934e-592c-4386-bb53-6d892f38ee98.png)

 ### Algorithm
1  Start the program.
2  Define a structure named "student" with three members: name, roll, and marks.
3  Define an array of 10 elements of type "student".
4  Declare an integer variable "i".
5  Display "Enter information of students:".
6  Use a for loop to input the information for each student in the array, with i starting from 0 and incrementing by 1 until i is less than 10.
7  Set the roll number of the current student to i + 1.
8  Display "For roll number [i+1]:".
9  Prompt the user to input the name of the current student.
10  Prompt the user to input the marks of the current student.
11  Display a blank line.
12  Use another for loop to display the information for each student in the array, with i starting from 0 and incrementing by 1 until i is less than 10.
13  Display "Information for roll number [i+1]:".
14  Display the name of the current student using the puts() function.
15  Display the marks of the current student with one decimal place.
16  End the program.
 


