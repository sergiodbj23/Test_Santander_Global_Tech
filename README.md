How to run the application

Please, open the project in Visual Studio 2019 and start the application. The IIS Express server will start and the browser will open with the url https://localhost:44305/swagger/index.html.
In this url you will be able to choose the get method "/api/Book" to return the first 20 books sorted by score in a descending order or you can call the method directly by 
the url https://localhost:44305/api/Book.

One of the premises adopted was to always use linq and linqs queries to optimize searches.

An improvement that I suggest, would be to change the method that searches for an element by another method that returns the necessary data to avoid searching for each element 
at a time.
