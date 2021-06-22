# Architecture
### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

Both Angular and Express make use of Models, Views, and Controllers, Express is used for backend functionality, while Angular is used for frontend functionality. This is precisely what we do with our web application. Angular relies heavily on components for single page functionality, which can be seen by every page having its own component folder. This is not a feature included in the consumer view of the website that runs on Express. The Express pages function off of handlebar views and HTML pages. The Angular component also relies on the API and backend server, as without these, the Admin single page application will not be able to pull the list of trips available or put new trips into the database. Javascript is used for the websites routes, controllers, and models, along with the main app file, which exports the Express application.

### Why did the backend use a NoSQL MongoDB database?

The backend made use of a NoSQL MongoDB database in order to hold information about a few things, mainly trip information and user account login details. NoSQL does not rely on a schema, which makes it much easier for users to store data inside of it. This document based database also offers support for agile development, as the data model is not fixed. For example, adding functionality similar to the handlebars view of the Travel page would be easy to implement on another part of the website, such as the Meals or Rooms page.

# Functionality
### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

The main difference between JSON and Javascript is that JSON is mainly used for the purpose of storing data. This JSON data is what is used to transmit data from the backend of the server to the client side front end, which then renders and displays the data on the webpage there. Javascript can easily convert JSON data because of their similar notation, which is why they are often used together when it comes to web development.

### Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

One example of refactoring code can be seen in the views folder, which contains a handlebars version of the travel page. This version of the website has greatly improved functionality and efficiency when compared to the normal travel.html page. It makes use of partials, which are essentially templates. As the Travlr webpage makes use of a lot of repeated content, inserting these partials makes coding the webpages much easier. The travel handlebar view also pulls trip data directly from the trip database, as opposed to using hardcoded data. This means that the handlebar view of the webpage will always display the most up to date information whenever the database is updated with new trip entries.

# Testing
### Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

API endpoints are the locations in a program where requests for information are sent to. These endpoints are used in combination with certain data related methods, such as GET, POST, PUT, and DELETE. By making use of these methods and endpoints together, you can allow users to push new information into the database, edit existing entries, or view existing records. Implementing security for these endpoints is essential, as if there is no protection unauthorized users would be able to make access of them and gain access to all of the information held inside the database. 

# Reflection
### How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

In terms of skills, I have developed the ability to build Full Stack applications during the duration of this course. Full Stack development skills are very desirable in the field of computer science, as being able to create Full Stack websites requires knowledge of several different languages. You need to have a good handle of HTML and CSS in order to create an attractive looking front-end. Javascript is also used for the "fancier" aspects of webpages that involve user interactions. A programming language such as PHP or Python is require for back-end coding. JSON and knowledge of database technology, such as MongoDB, is important if any kind of user data is going to be stored. I made use of all of these aspects while I was creating this Single Page Application.
