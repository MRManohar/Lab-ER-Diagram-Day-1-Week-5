We are gonna come with an ER diagram for the most solved scenario.



The University Database


University of Florida requires a database that stores details about university students, courses, the semester a student took a particular course (and his mark and grade if he completed it), and what degree program each student is enrolled in. 



Consider the following requirements list provided by Mr. John Hanson (Head of Administration):

The university offers one or more programs.
	1. A program is made up of one or more courses.
	2. A student must enroll in a program.
	3. A student takes the courses that are part of her program.
	4. A program has a name, a program identifier, the total credit points required to graduate, and the year it commenced.
	5. A course has a name, a course identifier, a credit point value, and the year it commenced.
	6. Students have one or more given names, a surname, a student identifier, a date of birth, and the year they first enrolled. We can treat all given names as a single object—for example, “John Paul.”
	7. When a student takes a course, the year and semester he attempted it are recorded. When he finishes the course, a grade (such as A or B) and a mark (such as 60 percent) are recorded.
	8. Each course in a program is sequenced into a year (for example, year 1) and a semester (for example, semester 1).


Can you help them with an ER diagram for their University database?