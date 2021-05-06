-- CREATE TABLE person (
-- 	person_id SERIAL PRIMARY KEY,
--   name VARCHAR(35),
--   age INT,
--   height INT,
--   city VARCHAR(35),
--   favorite_color VARCHAR(35)
-- );


-- INSERT INTO person
-- (name, age, height, city, favorite_color)
-- VALUES
-- ('Nicholas', 22, 176, 'St George', 'Yellow'),
-- ('Person 2', 23, 164, 'Danbury', 'Green'),
-- ('Person 3', 18, 154, 'Austin', 'Blue'),
-- ('Person 4', 21, 183, 'Seattle', 'Purple'),
-- ('Person 5', 35, 173, 'Las Vegas', 'Black');

-- SELECT * FROM person
-- ORDER BY height DESC;

-- SELECT * FROM person
-- ORDER BY height;

-- SELECT * FROM person
-- ORDER BY age DESC;

-- SELECT * FROM person
-- WHERE age > 20;

-- SELECT * FROM person
-- WHERE age = 18;

-- SELECT * FROM person
-- WHERE age < 20 OR age > 30;

-- SELECT * FROM person
-- WHERE age != 27;

-- SELECT * FROM person 
-- WHERE favorite_color = 'Red';

-- SELECT * FROM person
-- WHERE favorite_color != 'Red' AND favorite_color != 'Blue';

-- SELECT * FROM person
-- WHERE favorite_color = 'Green' OR favorite_color = 'Orange';

-- SELECT * FROM person
-- WHERE favorite_color IN('Green','Orange','Blue');

-- SELECT * FROM person
-- WHERE favorite_color IN('Yellow','Purple')

-- CREATE TABLE orders (
-- 	orders_id SERIAL PRIMARY KEY,
--   person_id INT,
--   product_name VARCHAR(50),
--   product_price NUMERIC,
--   quantity INT
-- );

-- INSERT INTO orders
-- (person_id, product_name, product_price, quantity)
-- VALUES
-- (1, 'Chair', 37, 1),
-- (1, 'Table', 70, 1),
-- (1, 'Shoes', 125, 1),
-- (2, 'Car', 20000, 1),
-- (2, 'Pizza', 30, 3);

-- SELECT * FROM orders

-- SELECT sum(quantity) FROM orders

-- SELECT sum(product_price) FROM orders

-- SELECT sum(product_price) FROM orders
-- WHERE person_id = 1;

-- INSERT INTO artist
-- (name)
-- VALUES
-- ('Nick'),
-- ('Bob'),
-- ('Lil Uzi Vert');

-- SELECT * FROM artist
-- ORDER BY name DESC
-- LIMIT 10;

-- SELECT * FROM artist
-- ORDER BY name ASC
-- LIMIT 5;

-- SELECT * FROM artist
-- WHERE name LIKE 'Black%';

-- SELECT * FROM artist
-- WHERE name LIKE '%Black%';

-- SELECT * FROM employee
-- WHERE city = 'Calgary';

-- SELECT max(birth_date) FROM employee

-- SELECT min(birth_date) FROM employee

-- SELECT * FROM employee
-- WHERE reports_to = 2;

-- SELECT COUNT(*) FROM employee
-- WHERE city = 'Lethbridge';

-- SELECT COUNT(*) FROM invoice 
-- WHERE billing_country = 'USA';

-- SELECT max(total) FROM invoice; 

-- SELECT min(total) FROM invoice;

-- SELECT * FROM invoice
-- WHERE total > 5;

-- SELECT COUNT(*) FROM invoice
-- WHERE total < 5;

-- SELECT COUNT(*) FROM invoice
-- WHERE billing_country IN('CA','TX','AZ')

-- SELECT avg(total) FROM invoice;

-- SELECT sum(total) FROM invoice;

