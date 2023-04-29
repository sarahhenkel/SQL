# SQL
SQL Portfolio
/** Candles, 5 columns, 15 items, order by price and show one statistic about the items **/

CREATE TABLE Candles (id INTEGER PRIMARY KEY, name TEXT, scent TEXT, quantity INTEGER, price INTEGER);

INSERT INTO Candles VALUES (1, "Cappuccino", "Starbucks Coffee", 10, 22);
INSERT INTO Candles VALUES (2, "Cereal", "Fruity Pebbles", 20, 26);
INSERT INTO Candles VALUES (3, "Ice Cream Sundae", "Sweet Vanilla", 15, 36);
INSERT INTO Candles VALUES (4, "Pink Lemonade", "Lemonade", 20, 22);
INSERT INTO Candles VALUES (5, "Regular", "Flower Bomb", 10, 15);
INSERT INTO Candles VALUES (6, "Regular", "Lavender", 10, 15);
INSERT INTO Candles VALUES (7, "Regular", "Midnight Summer", 10, 15);
INSERT INTO Candles VALUES (8, "Regular", "Bowtie", 10, 15);
INSERT INTO Candles VALUES (9, "Regular", "Baby Powder", 10, 15);
INSERT INTO Candles VALUES (10, "Regular", "Christmas Day", 10, 15);
INSERT INTO Candles VALUES (11, "Regular", "Gummy Bears", 10, 15);
INSERT INTO Candles VALUES (12, "Candle Holder", "Flower", 5, 25);
INSERT INTO Candles VALUES (13, "Matches", "Pink", 5, 8);
INSERT INTO Candles VALUES (14, "Matches", "Orange", 5, 8);
INSERT INTO Candles VALUES (15, "Matches", "Black", 5, 8);

SELECT * FROM Candles ORDER BY price; 
SELECT SUM(quantity) FROM Candles;

