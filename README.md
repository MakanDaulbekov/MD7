
CREATE TABLE Orders (

    id INT,

    customer_name TEXT,

    product_name TEXT,

    quantity INT,

    price INT

);

INSERT INTO Orders (id, customer_name, product_name, quantity, price) VALUES

(1, 'Ayan', 'Mouse', 1, 5000),

(2, 'Dana', 'Keyboard', 2, 8000),

(3, 'Erbol', 'Monitor', 1, 45000),

(4, 'Aliya', 'Laptop', 1, 250000),

(5, 'Timur', 'Webcam', 1, 10000),

(6, 'Alua', 'Mousepad', 2, 3000),

(7, 'Nurlan', 'Headset', 1, 15000),

(8, 'Zarina', 'Speaker', 1, 12000),

(9, 'Dias', 'Microphone', 1, 18000),

(10, 'Mira', 'Tablet', 1, 90000),

(11, 'Ayan', 'Charger', 1, 4000),

(12, 'Dana', 'Cable', 3, 1500),

(13, 'Erbol', 'SSD', 1, 30000),

(14, 'Aliya', 'RAM', 2, 10000),

(15, 'Timur', 'Graphic Card', 1, 180000),

(16, 'Alua', 'Power Supply', 1, 20000),

(17, 'Nurlan', 'Case', 1, 15000),

(18, 'Zarina', 'Cooler', 1, 7000),

(19, 'Dias', 'Fan', 2, 5000),

(20, 'Mira', 'Motherboard', 1, 60000),

(21, 'Ayan', 'Monitor', 1, 45000),

(22, 'Dana', 'Mouse', 2, 5000),

(23, 'Erbol', 'Keyboard', 1, 8000),

(24, 'Aliya', 'Speaker', 1, 12000),

(25, 'Timur', 'Tablet', 1, 90000),

(26, 'Alua', 'Webcam', 2, 10000),

(27, 'Nurlan', 'Mousepad', 3, 3000),

(28, 'Zarina', 'Headset', 1, 15000),

(29, 'Dias', 'Microphone', 1, 18000),

(30, 'Mira', 'Laptop', 1, 250000),

(31, 'Ayan', 'Charger', 2, 4000),

(32, 'Dana', 'Cable', 4, 1500),

(33, 'Erbol', 'SSD', 1, 30000),

(34, 'Aliya', 'RAM', 2, 10000),

(35, 'Timur', 'Graphic Card', 1, 180000),

(36, 'Alua', 'Power Supply', 1, 20000),

(37, 'Nurlan', 'Case', 1, 15000),

(38, 'Zarina', 'Cooler', 1, 7000),

(39, 'Dias', 'Fan', 2, 5000),

(40, 'Mira', 'Motherboard', 1, 60000),

(41, 'Ayan', 'Monitor', 1, 45000),

(42, 'Dana', 'Mouse', 1, 5000),

(43, 'Erbol', 'Keyboard', 2, 8000),

(44, 'Aliya', 'Speaker', 1, 12000),

(45, 'Timur', 'Tablet', 1, 90000),

(46, 'Alua', 'Webcam', 1, 10000),

(47, 'Nurlan', 'Mousepad', 2, 3000),

(48, 'Zarina', 'Headset', 1, 15000),

(49, 'Dias', 'Microphone', 1, 18000),

(50, 'Mira', 'Laptop', 1, 250000);

SELECT * FROM Orders;

SELECT DISTINCT customer_name FROM Orders;

SELECT * FROM Orders WHERE price > 50000;
