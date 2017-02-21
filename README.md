The following normalized tables from the Student Registration System (some tables have been simplified) will be used in this project:

Students(B#, firstname, lastname, status, gpa, email, bdate, deptname) Courses(dept_code, course#, title)
Course_credit(course#, credits)
Classes(classid, dept_code, course#, sect#, year, semester, limit, class_size, faculty_B#) Faculty(B#, firstname, lastname, rank, office, email, phone#, deptname) Enrollments(B#, classid, lgrade)
Grades(lgrade, ngrade)

As a general clarification, we assume that no student takes the same course (including different sections of the same course) more than once.

There are 20 statements and you are asked to write one or more SQL query for each statement. 
