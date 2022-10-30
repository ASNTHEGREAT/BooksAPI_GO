# BooksAPI_GO
This is an api (in localhost) created to get info of all books, by ID, create a new book in the database (using data structure), checkout and return an existing book.

Use POSTMAN to test the following:

GET:http://localhost:8080/books
>> This will fetch you all the available books in the map
GET:http://localhost:8080/books/2
>> This will fetch you the book with the entered id, i.e, /books/:id

POST:
|| In postman go to body -> raw -> JSON and paste the json object given in body.json
http://localhost:8080/books
>> This will append the given object to the map

PATCH:
http://localhost:8080/checkout/?id=2
>> This will decrement the quantity of the book(ID) that you choose
http://localhost:8080/return/?id=2
>> This will increment the quantity of the book(ID) that you choose
