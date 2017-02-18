# SQL_library
SQL library

/* Create table */

CREATE table table_name (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    title TEXT,
    content TEXT,
    author TEXT);
	
/* insert into table */
	
INSERT INTO documents (author, title, content)
    VALUES ("Puff T.M. Dragon", "Fancy Stuff", "Ceiling wax, dragon wings, etc.");
	
/* Select data & table */
	
SELECT * FROM table_name;
