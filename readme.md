Q. Thought question: What does module.exports do?
A1. Allows for the export of the files, function and logic from one file to another. Without it, you import the data into another file.

Q. What happens if we forget to add it? What kind of error will we get?
A1. Empty object

Q. What are controllers?
A1. Creates the communication between the user and model.
A2. The controllers "control" how the views (client app) and models (data) interact. Manages the flow of data and control user interaction.
A3. Controllers handle the logic for the application and are the go-between from the client to the database. Takes care of the logic and determines what happens when a user makes a request a server.
A4. In the context of an express.js app. controllers are typically defined as modules that handles the specific routes and functionality.

Q. How should you organize controllers if you are following an MVC pattern?
A1. Folder to be same directory as package.json
A2. Naming convention

- For bookmarks - bookmarksController.js
- models/bookmark.js
- For cats - catsController.js
- models/cat.js
- For weirdSharks - weirdSharksController.js
- models/weirdShark.js
- For rocks - rocksController.js
- models/rock.js

Q. What is the purpose of a 404 route?
A1. To let the user know they requested data that does not exist or page view route does not exist

Q. Why is it important to set the correct status code?
A1. There are many different status code for different error, you want to inform the user what the specific error is.

Q. What datatype is the status code?
A1. Number?

Q. What is the default status code of your responses when you don't add a status code?
A1. 200

Q. What is the purpose of this route?
A. Get an individual view (show one bookmark)

Q. Where would you write this code?
A. Inside bookmarksController.js

Q. What is the purpose of this route?
A. Create a new bookmark

Q. Where would you write this code?
A. Inside bookmarksController.js

Q. Why does create have the same path as the index route?
A. Different methods have different request route

Q. How is it distinguished from the index route?
A. Different HTTP verb, we use .post for create.

Q. How do we make a POST request that will access this route?
A. Use cURL in the terminal.

Q. Why can't we use the browser URL to make this request, as we've done for the GET routes?
A. It is time consuming

Q. What is cURL?
A. client URL

Q. What is the advantage of using cURL over creating an HTML form or a GUI like Postman?
A. Faster

Q. When is it a good time to use cURL?
A. Excellent option for quick demos and testing

Q. When does it make more sense to use an app like Postman?
A. Postman is ideal for testing, debugging, and documenting APIs with its user-friendly interface and comprehensive features. It also facilitates collaboration and automated testing, making it a valuable tool for API development and maintenance.
