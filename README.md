# JDBC_Assignment2

CREATE TABLE sqlandjava.cars (
car_id INT NOT NULL AUTO_INCREMENT,
brand VARCHAR(45),
color VARCHAR(45),
PRIMARY KEY(car_id));
INSERT INTO sqlandjava.cars (car_id, brand, color)
VALUES (1, 'Volvo', 'Black'),
(2, 'Saab', 'Blue'),
(3, 'Audi', 'Red'),
(4, 'Ford', 'Green');

SELECT * FROM sqlandjava.cars;

GRANT SELECT ON sqlandjava.cars TO karin@localhost;
