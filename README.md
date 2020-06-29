# Book-Management-System-with-Database-and-Simple-UI---using-Tkinter-and-SQLite3-in-Python
<h3>INTRODUCTION</h3><br>

The mini project ‘Book Management system’ is a sample project for managing book details. The project aims at developing a book management system using the Python language that enables an organization to maintain its book library. <br>
The project demonstrates the creation of a Graphical User Interface of the system, using the Tkinter Graphics library of Python.<br>
The application uses basic Python functions to generate menu options, title boxes, input message boxes, list and print text on the screen. <br>
To fetch information from the user and to perform various tasks on that information  based on the command option selected, various functions have been created. <br>
The application uses tuples, data structure to display the result of all the operations that are to be performed on the data.<br>

<h3>PROBLEM STATEMENT</h3><br>

We have constructed a database using a book management system. This database consists of details about books: book names, author of the book and the issue number(which can’t be changed). <br>
The management system is providing the user or member of an organization to perform the basic operation database/SQL operations on the data stored in the database.<br>
1.	Add Entry – perform the insert operation of adding a new row or tuple into the relation within the database. This tuple will consist of the entries given by the user consisting of the book name, author and issue number. <br>
     SQL—>(“INSERT INTO book VALUES (NULL,?,?,?)", (title, author, isbn,))<br>

2.	View all – performs the search * from table operation. It displays all the rows that are present in the table. <br>
     SQL—>("SELECT * FROM book”)<br>

3.	Search entry – Given certain values of the book name and author name it searches and displays all the entries having those values. <br>
     SQL—>("SELECT * FROM book WHERE title=? OR author=?", (title, author,))<br>

4.	Update – Given a new value for a row, this SQL operation is going to update the value in the table.<br>
     SQL—>"UPDATE book SET title=?, author=? WHERE id=?", (title, author, id,))<br>

5.	Delete – performs deletion of the row that is selected from the table based on the value of the index of the selected row.<br>
     SQL—>("DELETE FROM book WHERE id=?", (id,))<br>
 
<h3>PROGRAM REQUIREMENTS AND MODULES</h3><br>

1.	SQLite3 module: It provides an SQL interface compliant with the DB-API 2.0 specification. You do not need to install this module separately because it is shipped by default along with Python version 2.5.x onwards.<br>
2.	Tkinter: tkinter is most commonly used GUI method IN Python. It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with tkinter outputs the fastest and easiest way to create the GUI applications. <br>
3.	Label(): display area for a short text <br>
4.	Button(): implementation of "push" button.<br>
5.	Window(): Its the space where we show all the outputs. Window is a top-level frame with a title and a border. The size of the frame includes any area designated for the border.<br>
