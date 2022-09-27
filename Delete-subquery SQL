USE people;

SELECT COUNT(*) FROM people.citizen;

CREATE TABLE StudentDetails(
class TINYINT,
roll_no TINYINT,
name VARCHAR(30),
PRIMARY KEY (class , roll_no)
);

CREATE TABLE StudentMarks(
class TINYINT,
roll_no TINYINT,
marks TINYINT,
PRIMARY KEY (class , roll_no)
);

INSERT INTO StudentDetails(class , roll_no , name)
VALUES (8 , 1 , 'abhinay');

INSERT INTO StudentDetails(class , roll_no , name)
VALUES (8 , 2 , 'suraj');

INSERT INTO StudentDetails(class , roll_no , name)
VALUES (9 , 1 , 'sindhu');

INSERT INTO StudentDetails(class , roll_no , name)
VALUES (10 , 1 , 'arjun');

INSERT INTO StudentMarks(class , roll_no , marks)
VALUES (8 , 1 , 88);

INSERT INTO StudentMarks(class , roll_no , marks)
VALUES (8 , 2 , 46);

INSERT INTO StudentMarks(class , roll_no , marks)
VALUES (9 , 1 , 95);

INSERT INTO StudentMarks(class , roll_no , marks)
VALUES (10 , 1 , 74);

DELETE FROM StudentMarks
WHERE (class , roll_no) =  (SELECT class, roll_no
							FROM StudentDetials
							WHERE name = 'arjun');
                            
SELECT *
FROM StudentMarks;

DROP TABLE studentdetials;
DROP TABLE studentmarks;






