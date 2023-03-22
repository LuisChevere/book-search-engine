# Google Book Search MERN

![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)

  ## Table of Contents
  - [User Story](#user-story)
  - [Description](#description)
  - [Installation](#installation)
  - [Acceptance Criteria](#acceptance-criteria)
  - [License](#license)
  - [Contributions](#contributions)

## User Story
```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Description
  Usage of Google Books API to create an Graql API with Apollo Server. MERN stack is implemented to create the app. User can sign up and log in for an account, search for a book of their liking and added to a list of saved books, users can also remove the saved books.
  

  ## Installation
 To use this app npm init has to be called to create your package.json file.
 The following necessary Npm dependencies must be installed to run the application properly: the needed dependencies will be found on the package.json file.
 To properly install the database you must create at cluster on Mongodb atlas.
 Run "npm start" for the port to start listening with mongoose.
 <br />
    This app is deployed on Heroku

  ## Acceptance Criteria

```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
```


  ## Deployed App:<br /> 
  [Launched App](https://google-books-lc.herokuapp.com/)
  ![Site Image](https://github.com/LuisChevere/book-search-engine/blob/main/client/public/images/Screenshotbooks.png?raw=true)

  ## Contributions
  - Luis Chevere: [@LuisChevere](https://github.com/LuisChevere) - Github
    <br />
  If you wish to contribute to this application, clone the repository into your VSCode.
  
  
  ## License
  This application uses The Unlicensed license.
  


  ## Questions
  Github: [@LuisChevere](https://github.com/LuisChevere)
  
  Email with any questions: Hairchevere@gmail.com

  
