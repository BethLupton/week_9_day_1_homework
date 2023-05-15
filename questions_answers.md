![Image Description](./Screenshot%202023-05-15%20at%2020.39.13.png)

Questions

1. What is responsible for defining the routes of the games resource?

A: create_router.js


2. What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?

A. It's split into two separate apps/folders for client and server
    Client- Defining the interface for the user
    Server- Defining the API for the client to interact with, interacts with the database appropriately.


3. What are the the responsibilities of server.js?

A. It initialises the server, routes and database connection

4. What are the responsibilities of the gamesRouter?

A. To create a RESTful API.


5. What process does the the client (front-end) use to communicate with the server?

A. It makes a HTTP request to the server using the appropriate URL and method, passing a body as needed (the game).

6. What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the  MDN docs

A. It passes in the request options.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?

A. POST, GET (all) & DELETE

8. What are we using the MongoDB Driver for?

A. To connect to the database.
