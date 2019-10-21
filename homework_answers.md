What is responsible for defining the routes of the games resource?
create_router.js.



What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
The client is responsible for the front end and the server is responsible for the back end.



What are the the responsibilities of server.js?
Serves data to and from MongoDB.



What are the responsibilities of the gamesRouter?
It directs create_router to the api.



What process does the the client (front-end) use to communicate with the server?
The methods in gamesservice.js.

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
It is an init object that allows us to control, and it is used in this application to turn data into a JSON string.


Which of the games API routes does the front-end application consume (i.e. make requests to)?
Get, Post and delete, as there is no update or get by ID optoin on the front end.


What are we using the MongoDB Driver for?
To add and remove data from the database.


Extension
Why do we need to use ObjectId from the MongoDB driver?
It creates a unique identifier.

Add to your diagram the dataflow for removing a game.
