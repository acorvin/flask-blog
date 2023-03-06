# Oriblog

This is a simple blog application built using Python Flask. It allows users to register new accounts in order to create, update, and remove blog posts.

## Preview

![preview](preview-oriblog.gif?raw=true)

## Features

- User registration: Users can create new accounts by providing a username, email, and password. Passwords are hashed and salted for security.
- User login: Existing users can log in using their email and password. A session is created to keep the user logged in.
- Profile picture: Users can upload a profile picture and update it as needed.
- Blog post creation: Users can create new blog posts, including a title and content.
- Blog post editing: Users can update or delete their own blog posts.
- Error 404 pages: Custom error pages are provided for handling invalid URLs.

### Database

The application uses SQLite to store data. The database schema includes tables for users, blog posts, and profile pictures.

## Technologies Used

- Python
- Flask
- SQLite
- Animate CSS

## Author

Alex Corvin

## Version

1.0.0

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

