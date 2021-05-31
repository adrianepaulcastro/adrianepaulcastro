# Final Term Project for LBYEC2B

## GPA-ulator

The project tackles the collection of the GPA and the award received by a student studying in DLSU Manila. The program is designed to collect the data of a Lasallian student such as their name, degree and ID number. The program will ask the number of terms taken by the student and then followed by the courses and the corresponding units. The student will now input the corresponding grade per course. The program will now provide a summary showing the Term GPA (TGPA) and the Cumulative GPA (CGPA) of the student and the award received. This process will repeat until the number of terms inputted in the beginning of the program is reached.

The objective of this project is to apply the following concepts learned from the course: 
- 1D and 2D arrays must be utilized to contain several sets of data into an organized array. Due to the nature of the data, the project required the use of 2D arrays. 
It is also possible to store values inside the arrays whether int or char. The usage of 2D array is for the deanslister part while 1D array for the others it may be char or int.
- String processing is used in this program to know the certain word is the username and the password.
For the strings and array there is char username[20], password[20] is used to identify the number of letters for the username or password can be.
- File I/O is used for placing it to another file. For c, we use the fprint and fscan, but in c++ we used the term outfile it is still the same as the file I/O
For this code pointer was not used that much but we used it on a certain code where there is char *exception in the catch portion.
- Object-Oriented Programming is used to call the variables inside the class structure the programmer must make use of the dot for example subject.name. The subject signifies where the class is then the name is the variable inside the certain class structure. 
- For loop is used for repeating the certain code mentioned in the upper portion of the code which is for the input of number of terms and courses inputted by the user.
- do while loop is similar to while loop, until the statement is false it would continue asking you the same question until the user would input the right conditioned value which is used for the grades where there is no such thing as a negative grade.


In order for the GPA-ulator to work, the programmer must apply the following programming concepts in the pertinent program source code line/s:

| Programming Concept  | Pertinent Program Source Code Line                                                                                                                                                                                                    |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1D and 2D arrays     | 1D Array = line 19, line 76, line 75, line 74, line 103, line 135, line <br> 2D Array = line 175, line 140 |
| Strings, Array of Strings, and String Processing     | strings processor: line 168 <br> strings/array strings: line 159 to 164 |
| File I/O, Pointers   | File I/O: line 108 to 126 <br> Pointer: Line 47 |
| Object-Oriented Programming   | line 9 to 69 <br> line 71 to 105 <br> line 170 to 175 |
| Loops     | For loop: line 31, line 62, line 98, line 117, line 119, line 132, line 143 <br> do while Loop: Line 39 to 50 |
