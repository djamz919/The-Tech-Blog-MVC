# The-Tech-Blog

## Description
This application is a blog that allows users to create an account where they can create, edit, and view posts about technology. Additionally, when logged in, users can comment on any posts in the homepage.

## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Questions](#questions)

## Installation
To install any dependencies run: npm install. 

If ran locally, be sure to create a .env file in the same directory as the index.js file and populate the .env file with the DB_NAME, DB_USER, and DB_PW. Also be sure to source the schema using the terminal and populate the tables with the seeds by running npm run seed. Run the program by entering the command node server.js in your CLI.

## Usage
This application can be accessed via the following [Heroku app.](https://the-tech-blog-mvc.herokuapp.com/) or run locally (see installation above for instructions).

To be able to add posts or comments, simply login or signup.

To navigate to the login page, simply click login in the navigation bar at the top of the page: 
![Screenshot of Login Page](public/images/login.png)

If you do not have an account yet, click on "Sign up instead" in the login page to create an account:
![Screenshot of Signup Page](public/images/signup.png)

Once logged in, you can add posts by clicking on the "+ New Post" button in the dashboard:
![Screenshot of Dashboard](public/images/signup.png)
![Screenshot of Add Post](public/images/add-post.png)

You can also edit your posts in the dashboard:
![Screenshot of Edit Post](public/images/edit-post.png)

To add comments to post, navigate to the homepage and click on the post you would like to add a comment on. You must be logged in to add a comment!
![Screenshot of Homepage](public/images/home-screenshot.png)
![Screenshot of Add Comment](public/images/add-comment.png)

## Questions
For any questions, reach out to github.com/djamz919 via the following email address: djtm97@gmail.com.