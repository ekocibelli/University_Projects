You've been hired by Stevens Institute of Technology to create a data repository of courses, students, and instructors.  The system will be used to help students track their required courses, the courses they have successfully completed, their grades,  GPA, etc.  The system will also be used by faculty advisors to help students to create study plans.  We will continue to add new features to this solution over the coming weeks so you'll want to think carefully about a good design and implementation. Your assignment this week is to begin to build the framework for your project and summarize student and instructor data.  You'll need to download three ascii, tab separated,  data files:
  1. students.txt (available from Canvas): Provides information about each student
  2. instructors.txt (available from Canvas):Provides information about each instructor
  3. grades.txt (available from Canvas): Specifies the student CWID, course, and grade for that course, and the instructor CWID.
  
Your assignment is to read the data from each of the three files and store it in a data structure that is easy to process to meet the following requirements:
Your solution should allow a single program to create repositories for different sets of data files, e.g. one set of files for Stevens, another for Columbia University, and a third for NYU. Each university will have different directories of data files.   Hint: you should define a class to hold all of the information for a specific university.
You may hardcode the names of each of the required "students.txt", "instructors.txt", and "grades.txt" files.   Your solution should accept the directory path where the three data files exist so you can easily create multiple sets of input files for testing.
Use your file reader generator from HW08 to read the students, instructors, and grades files into appropriate data structures or classes.
Use PrettyTable to generate and print a summary table of all of the students with their CWID, name, and a sorted list of the courses they've taken (as specified in the grades.txt file).  
Use PrettyTable to generate and print a summary table of each of the instructors who taught at least one course with their CWID, name, department, the course they've taught, and the number of students in each class. 
Implement automated tests to verify that the data in the prettytables matches the data from the input data files. 
You do NOT need to implement automated tests to catch all possible error conditions but your program should print relevant error messages when invalid or missing data is detected.
Your solution MAY print error messages and warnings to the user about inconsistent or bad data, e.g. a data file with the wrong number of fields or a grade for an unknown student or instructor.
