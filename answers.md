Homework: Full Stack Games Hub App

MVP

Diagram:

Showing the dataflow through the application starting with a form submission, ending with the re-rendering of the page. This will involve a multi-direction data-flow with the client posting data to the server and the server sending data back to the client with the response. Detail the client, server and database in the diagram and include the names of the files involved in the process.

Questions
What is responsible for defining the routes of the games resource?
- create_router.js

What do you notice about the folder structure? Whats the client responsible for? 
- The client is responsible for the front-end

Whats the server responsible for?
- the server is responsible for the back-end - communicating with databases

What are the the responsibilities of server.js?
- server.js is responsible for setting up Express - gets access to the database

What are the responsibilities of the gamesRouter?
- The gamesRouter creates a router for the games collection and gets the data from it

What process does the the client (front-end) use to communicate with the server?
- the GameForm?

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
- The second argument an init object

Which of the games API routes does the front-end application consume (i.e. make requests to)?
-  http://localhost:3000/api/games/ and http://localhost:3000/api/games/:id

What are we using the MongoDB Driver for?
- connecting server and database

Extension
Why do we need to use ObjectId from the MongoDB driver?
Add to your diagram the dataflow for removing a game.