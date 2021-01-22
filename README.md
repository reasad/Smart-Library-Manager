# Smart Library Manager

## Table of Contents

* [Introduction](#introduction)
* [Features](#features)
* [Technologies](#technologies)

## Introduction

The project titled “Smart Library Manager” is a library management software for monitoring and controlling transactions in library. This project is developed using Java, JavaFX and database management is handled by MySQL. The key purpose of this project is to provide a friendly environment to the users as well as the stuffs of the library to maintain the library the best way possible and help reduce the human efforts. It can help user to manage the transaction or record more effectively and timesaving.

## Features

*	User Login:
This feature gives user to login to the system. A user can log in to the system by providing username and password. After proper verification of the username and password, valid user will be allowed to enter into the system. A username and password mismatch will not allow someone to enter into the home page and the user will be asked to re-enter his/her username and password.  The student login will allow a student to access the general features of the library: search, issue, return or request new books etc. The user can also view his profile and edit his profile information.


*	Administrative Login: 
This feature allows an admin to login to the system by providing username and password. After proper verification of the username and password, admins will be allowed to visit Administrative home page.  Username and password mismatch will not allow an admin to enter into the system. Through administrative login an admin can have access to some special features like: adding new books, entry book details, edit book data, view student information etc. He can also view his profile and edit information.

*	New User Registration:
This feature allows any member from the institution to create an account for himself. This option will be available at the start of the program. A new member has to fill up a registration from providing his name, Id, department, contact no, username and password. After providing valid information a new user can create an account for himself and later he will be allowed to enter into the system.

*	Manage Book:
This feature can only be executed by admins. This feature allows an admin view the list of books and edit book information. Admins can also add new books upon user request through this feature.

*	Search Book:
This feature allows a user to search for a particular book in the library. A book can be searched by-
    1.	Title
    2.	Author Name
    3.	ISBN Number
A user has to select any of the 3 search types and enter the keyword. The system will then filter the book based on the keyword and show the filtered books in a table view.

*	Issue Book:
This feature allows a user to issue a particular book provided that,
    1.	The availability of the book in the library.
    2.	The current user has not exceed the maximum number of books issued.
    3.	No other member has already issued the book

If above conditions are met anyone can issue a book by this feature. This will update the issue information in the database and provide user the issue and return date information. 

*	Return Book:
This feature keeps track with the return books. A user can issue any book for a limited amount of time. The user has to return the books issued by him/her within that time.
After successful return of the issued book the user information database will be updated. 
Unsuccessful return of the book within due date will lead a user to pay the penalty.

*	Reissue Book:
This feature leads the user to extend his/her book return date without paying any penalty. But the can reissue any book maximum 2 times and after that he/she has to return the book within return date.

*	Rate Book:
This feature allows a user to rate a book after finishing it. This will generate a combined user rating about a book. This will help a new reader to choose a particular book or help anyone to compare similar kind of books.

## Technologies

• Java

• JavaFX

• Netbeans 8.2

• MySQL server

