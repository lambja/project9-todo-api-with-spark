# Todo API with Spark | Techdegree Project 9

Code files: /src/main
Test files: /src/test

## Project Prompt

A fellow student of yours in the Full Stack JavaScript Techdegree has just taken the Angular Basics course and has a pretty nice working Angular.js Todo app. They went a little farther and used the ng-resource plugin which allows the application to work automatically using RESTful practices. However, they don’t have experience yet on the server side of things. But you do. Can you help them out?

The ability to provide a back-end for a client-side app is a great skill to have, and you will encounter the need to do this throughout your journey. As long as their app is functioning they will be happy.

I’ve started the shell of the project for you and the app currently serves the Angular app. Remember to use your developer tools in your browser to see what is being attempted.


## Minimum Viable Product:

- This API is versioned, all routes should be prefixed with /api/v1

- When the app first starts it will attempt to fetch all Todos in the system. Handle the request and return all the Todos.
  - Look at the browser tool to see what is being requested and how and create the appropriate route

- When a Todo is created and the save link is clicked, it will make a request to the server. Handle the request by creating a Todo and setting the proper status code.
  - Look at the browser tool to see what is being requested and how and create the appropriate route

- When a previously saved Todo is updated and the save link is clicked, it will make a request to the server. Handle the request by updating the existing Todo.
  - Look at the browser tool to see what is being requested and how and create the appropriate route. HINT: You might not’ve used this one before, but you can figure it out if you PUT your mind to it!

- When a previously saved Todo is deleted and the save link is clicked, it will make a request to the server. Handle the deletion and return a blank response and the proper status code.

## Extra Credit:
- Add unit tests to test your model and dao implementation
- Add functional testing to prove the API is working as expected
