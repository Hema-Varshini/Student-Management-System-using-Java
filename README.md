Problem Statement:

Implement a StudentManagementSystem, This system can handle
multiple departments and students. Create Student class and Department
classs with the below properties.

Department:
private String deptName (this is unique, each deptName will uniquely
identify the department),
private String deptHead.

Student:
private long studentID (this is unique, each studentID will uniquely
identify the student),
private String studentName,
private int creditScore

Create relationships in java so that each department can have a list of
students.

Implement the below methods in StudentManagement.java
1.public boolean enrollStudent(Student student, long deptName) throws
StudentAlreadyExistsException This method will enroll the given student
to the given department, throw StudentAlreadyExistsException, if he
already exists in the department. Return true only if the student has
been added successfully.
2. public ArrayList getStudentsByDepartment(String deptName) This
method will return a list of students belongs to the given department.
3.public void displayStudents(String deptName) This method will display
the students' details retrieved from the method
getStudentsByDepartment(String deptName) based on their credit
score(descending). Create a Tester class, create as many student and
department objects and test all the above methods.


Description

This program is to implement a StudentManagementSystem in which
there are several tasks to be performed. In this program there is one
interface named StudentManagementSystem which handle many
departments and students, there is a class "Student" in which details of
students are being given for their enrolment, there is a class
"Department" which is being inherited from
"StudentManagementSystem" interface and "Student" class . This
Department class contains the details of department i.e., dept name and
dept head.
There are private variables in the program. To use them in any part of
the program, we created functions which returns the values for these
private variables. There are few string handling functions used to check
whether we are entering correct department name and to check whether
student name is already enrolled before or not. There are few exception
implemented where user must enter proper name which must not contain
any numbers, if given throw an exception. There is an exception where
user must enter proper department name, if given wrong department,
throw an exception. These are few exceptions used in the program.
There are few methods used in this program to implement the tasks
given. enrollStudent() method is used to enrol the name, ID number and
credits of a student. If a students is already register in that respective
department ,then we have to throw an exception claiming that "Student
already enrolled". We should create user defined exception to throw this
exception. We use an "ArrayList" in this program to add the details of
students and department details. This method is used to return a list of
students belonging to the given department. We use a method
displayStudents() to print all the students enrolled in each department
with their credit score. The details of these students should be printed
in descending order of their credit score. So for this to get implemented
we use sorting technique so as to print the details in descending order of
their credit score. If we want to print the details of students only with
respective to one department, then we print in those details in
accordance to their department. We do these multiple operations using a
switch case where different cases are provided to perform users task.
And we create a tester class, it contains a main() in which we write the
switch statements and we create an object array with which all methods
are invoked as per number of students required to the user. This is the
main theme of the program where student enrolment is performed
successfully.
