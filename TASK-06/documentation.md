# Detailed Documentation for Microblog

## Introduction
Microblog is a simple microblogging application built with Flask, a popular Python web framework. This application demonstrates core features of a microblogging platform, including user authentication, posting updates, following users, and viewing posts.

## Project Overview
Microblog provides a platform for users to:
- Register and authenticate accounts
- Post updates and view posts from themselves and others
- Follow other users to see their updates
- Interact with posts through likes and comments

The application is designed to be a lightweight and straightforward example of a web application built with Flask, demonstrating key concepts in web development.

## Main Features
- *User Authentication*: Users can register, log in, and log out. Passwords are securely hashed.
- *User Profiles*: Each user has a profile page where their posts and information are displayed.
- *Post Creation*: Users can create, edit, and delete their posts.
- *Following System*: Users can follow other users to see their updates in their feed.
- *User Interaction*: Users can like and comment on posts (if implemented in the future).

## Functional Components

### User Registration and Authentication
- *Registration:* Users can create a new account by providing a username and email address. The registration form validates input and securely stores user information in the database.
- *Login:* Registered users can log in using their username and password. The system uses sessions to manage user authentication.
- *Logout:* Users can log out, which invalidates their session and redirects them to the login page.
