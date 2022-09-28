USE people;

-- Q1 . Fetch the name and marks of student who has the highest marks

SELECT *
FROM StudentMarks;

SELECT SD.name , marks 
FROM StudentMarks SM 
INNER JOIN StudentDetails SD
ON SM.class = SD.class AND SM.roll_no = SD.roll_no
WHERE marks = (SELECT MAX(marks) FROM StudentMarks);

-- Challenge : Fetch the value of highest marks from StudentMarks table

SELECT MAX(marks) FROM StudentMarks;

-- Challenge : Select the name and marks of all the students who have their marks more than average marks

SELECT AVG(marks) FROM StudentMarks;

SELECT SD.name , marks 
FROM StudentMarks SM 
INNER JOIN StudentDetails SD
ON SM.class = SD.class AND SM.roll_no = SD.roll_no
WHERE marks > (SELECT AVG(marks) FROM StudentMarks);


-- Homework : Fetch the name and marks of students whose marks are less than the average mark and studying in 8th class
-- HINT : You need to add an extra condition "class" inside the “WHERE” clause . 
