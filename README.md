# Mern-google-books

This project is a full-stack web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) that utilizes the Google Books API to allow users to search for and save books to a database.

## Installation

### To run this application locally, follow these steps:

- Clone this repository to your machine
- git clone https://github.com/tonymai6/Mern-google-books
- Install the necessary dependencies in both the root directory and the `client` directory
- cd your-repo
- npm install
- cd client
- npm install

## Usage
- To start the application, run the following command in the root directory:
- npm start
This will start both the server and the client simultaneously. The server will run on http://localhost:3001 and the client will run on http://localhost:3000.

## Functionality
- This application has the following functionality:

## Search
- Users can search for books by entering a keyword or phrase into the search bar.
- The Google Books API will return up to 10 relevant results, which will be displayed on the page.
- Users can click on a book to view more details, including the author, description, and a link to the Google Books page for that book.
## Save
- Users can save books to a MongoDB database by clicking the "Save" button on a book's details page.
- The saved books will be displayed on the "Saved" page, which can be accessed by clicking the "Saved" link in the navigation bar.
## Delete
- Users can delete saved books from the database by clicking the "Delete" button on a book's details page on the "Saved" page.
- The book will be removed from the database and will no longer appear on the "Saved" page.
## Technologies Used
### This project utilizes the following technologies:

- MongoDB
- Express.js
- React.js
- Node.js
- Google Books API
- Axios
- Bootstrap

## Deployed Application 

Visit the deployed application at [https://agile-beach-08478.herokuapp.com/](https://agile-beach-08478.herokuapp.com/)
