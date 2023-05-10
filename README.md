# Blog Site

The Blog Site project is a web application built using Node.js and Express framework. It provides a platform for users to create, read, and share blog posts. The project incorporates a MongoDB database for storing and retrieving blog data.

## Technologies Used

- Node.js
- Express
- MongoDB
- EJS
- Body-parser
- Lodash
- Mongoose

## Features

- **Home Page**: Displays the starting content of the blog and a list of existing posts.
- **About Page**: Provides information about the blog or the website.
- **Contact Page**: Provides contact information or a contact form.
- **Compose Page**: Allows users to create new blog posts.
- **Post Page**: Displays the full content of a specific post when accessed with its unique ID.

## Installation

1. Clone the repository:

2. Install the dependencies:

3. Set up MongoDB database:
- Install MongoDB locally or use a MongoDB service provider.
- Update the MongoDB connection string in `app.js` to connect to your database.

4. Start the server:

5. Open the application in your browser at `http://localhost:3000`.

## Usage

- Access the home page (`http://localhost:3000`) to view the starting content and existing blog posts.
- Navigate to the about page (`http://localhost:3000/about`) to read about the blog or website.
- Visit the contact page (`http://localhost:3000/contact`) to find contact information or use the contact form.
- Create new blog posts by going to the compose page (`http://localhost:3000/compose`).
- Each post can be viewed individually by clicking on the post title or accessing the post page (`http://localhost:3000/posts/:postId`).

## Contributing

Contributions to the project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make the necessary changes in your branch
4. Commit your changes
5. Push your changes to your forked repository
6. Submit a pull request
