# Khan-Academy-Projects
/*Projects performed on Khan Academy that exhibits SQL skillset*/

/*Design a Store Database*/

CREATE TABLE store (id INTEGER PRIMARY KEY, item text, quantity INTEGER, aisle INTEGER, color TEXT);
INSERT INTO store VALUES (1, "shirts", 5, 1, "BLUE");
INSERT INTO store VALUES (2, "bottoms", 5, 4, "PINK");
INSERT INTO store VALUES (3, "shoes", 4, 5, "YELLOW");
INSERT INTO store VALUES (4, "accessories", 2, 2, "GREEN");

SELECT * FROM store;

SELECT * FROM store ORDER BY quantity;
SELECT * FROM store ORDER BY aisle;
SELECT SUM(quantity) FROM store;
