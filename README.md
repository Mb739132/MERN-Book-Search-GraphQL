# MERN Challenge: Book Search Engine

![license badge](https://img.shields.io/badge/license-MIT-brightgreen)

## Description
The "MERN Challenge: Book Search Engine" project involves refactoring a fully functioning search engine powered by the Google Books API. Originally built with a RESTful API, the challenge is to transform it into a GraphQL API using Apollo Server. The project utilizes the MERN stack, comprising MongoDB, Express.js, React, and Node.js, with additional integration of Apollo Client for frontend-server communication. Users can search for books, save their searches, and interact with the application, with the goal of enhancing performance and meeting evolving user demands. Additionally, the project includes tasks such as modifying authentication middleware for GraphQL, creating an Apollo Provider for server communication, and deploying the application to Render.


## User Story

AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

## Acceptance Criteria

* GIVEN a book search engine
* WHEN I load the search engine
* THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
* WHEN I click on the Search for Books menu option
* THEN I am presented with an input field to search for books and a submit button
* WHEN I am not logged in and enter a search term in the input field and click the submit button
* THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
* WHEN I click on the Login/Signup menu option
* THEN a modal appears on the screen with a toggle between the option to log in or sign up
* WHEN the toggle is set to Signup
* THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
* WHEN the toggle is set to Login
* THEN I am presented with two inputs for an email address and a password and login button
* WHEN I enter a valid email address and create a password and click on the signup button
* THEN my user account is created and I am logged in to the site
* WHEN I enter my account’s email address and password and click on the login button
* THEN I the modal closes and I am logged in to the site
* WHEN I am logged in to the site
* THEN the menu options change to Search for Books, an option to see my saved books, and Logout
* WHEN I am logged in and enter a search term in the input field and click the submit button
* THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
* WHEN I click on the Save button on a book
* THEN that book’s information is saved to my account
* WHEN I click on the option to see my saved books
* THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
* WHEN I click on the Remove button on a book
* THEN that book is deleted from my saved books list
* WHEN I click on the Logout button
* THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button    

## Table Of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Test](#test)
* [Questions](#questions)

## Installation

To install dependencies, run the following command: 

```
npm install
```

## Usage
* Search for Books: Utilize the search functionality to look for books using keywords, titles, authors, or any other relevant criteria. Input your query into the search bar and press enter or click the search button to initiate the search.

* View Search Results:Browse through the search results displayed on the page. Each search result card typically includes information such as the book title, author(s), publication year, and a brief description.

* Save Book Searches:Register or log in to your account to access additional features such as saving book searches. Once logged in, use the option provided to save your favorite book searches for future reference.

* Interact with Saved Searches:Retrieve your saved searches from your user profile/dashboard. View, edit, or delete saved searches as desired to manage your saved content effectively.

* GraphQL API Interaction:Developers can explore the GraphQL API endpoints to fetch and modify data programmatically. Utilize GraphQL queries and mutations to interact with the backend server, allowing for efficient data retrieval and manipulation.

* Authentication and Authorization:Ensure proper authentication by logging in with valid credentials. Access restricted features such as saving searches only after authentication to enhance user experience and security.

* Deployment:Access the deployed application on the Render platform to experience the full functionality of the Book Search Engine. Visit the deployed URL to explore the application in a real-world environment.

* Feedback and Support:Provide feedback on the application's usability, performance, and features to contribute to its improvement. Contact the project maintainers or community for support, bug reports, or feature requests.


## Contributing

Contribute to the "MERN Challenge: Book Search Engine" project by reporting issues, suggesting features, or submitting code improvements via pull requests. Help enhance the application's functionality and user experience while adhering to project standards and respecting the contributions of others.

## Test

To run test, use the following command:

```
npm test
```

## Technologies Used


The technologies used in this project are:

MERN Stack:

* MongoDB: A NoSQL database used for storing book data and user information.
* Express.js: A web application framework for Node.js used for building the server-side logic and APIs.
* React: A JavaScript library used for building the user interface of the search engine frontend.
* Node.js: A JavaScript runtime environment used for executing server-side code.

GraphQL:

* Apollo Server: A GraphQL server implementation used for handling GraphQL queries and mutations.

Apollo Client:

* Apollo Client: A state management library for JavaScript used for querying the GraphQL server from the React frontend.

Other:

* Google Books API: An external API used for searching and fetching book data.
* JWT-Decode: A library used for decoding JSON Web Tokens (JWT) for user authentication.

Deployment:

* Render: A cloud platform used for deploying the application.

## Contributers

Mariatu Bah 

## License

MIT License

## Questions

To ask questions about the project, contact me directly at mariatu.bah46@gmail.com You can find more of my work at [Mb739132](https://github.com/mb739132/).
