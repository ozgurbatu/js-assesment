# js-assesment
Asessment for candidates

# What is this? 
This is a simple object orianted coding assesment. You need to follow instructions to build a simple library system while following object oriented programming paradigms. 

# About the assesment
 - You need to build it using javascript programming language.
 - You need to write a class for book object, which will have the following properties.
   - name
   - author
   - pageCount
 - You need to write a class (Library) which will have the following functions.
   - addBook // adds new book to library and returns this book as object.
   - deleteBook // returns true if successfully deleted else returns false
   - updateBook // gets bookname as argument and updates book, returns true if successfully updated book else returns false
   - getAllBooks // returns all books in library
   - getBookWithMostPageNumber // returns a book object with the most page number 
 - Your program *doesn't* need to store data in file or database. You can store this data in memory.
 - Your program needs to follow object oriented programming paradigms.
 
 # Additional information
  - Library object can be Array, Set or Map 
  - You can deny to add book if book exist in the library. (aka book names are unique)
  - You can find a boilerplate code to start with in this repo. [Here](index.js)
