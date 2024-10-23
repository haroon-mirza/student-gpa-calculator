Student GPA Calculator


This project is a simple .NET console application that calculates a student's overall GPA (Grade Point Average) based on their course grades and credit hours. The program allows input of course information such as course name, grade, and credit hours, and then performs the necessary calculations to output the student's GPA.


The program takes the following inputs:

Student’s name


Course names


Grades for each course (on a 4-point scale, where A = 4 and B = 3, etc.)


Credit hours for each course


Calculates the Grade Point Average (GPA) by multiplying the grade for each course by its credit hours.


Outputs a formatted table showing the course name, grade, and credit hours for each course.


Displays the final GPA with two decimal precision.


Course                  Grade   Credit Hours
English 101             4       3
Algebra 101             3       3
Biology 101             3       4
Computer Science I      3       4
Psychology 101          4       3

Final GPA:              3.35


Input Data: The student's name, courses, grades, and credit hours are stored in variables.


GPA Calculation:


Each grade is multiplied by the respective course's credit hours.


The results are summed, then divided by the total number of credit hours.


Formatted Output: The application prints a well-formatted table showing the courses, grades, and credit hours, followed by the calculated GPA.
