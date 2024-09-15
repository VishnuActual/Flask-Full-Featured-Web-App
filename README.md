# Flask Blog Application

## Overview

This is a simple blog application built with Flask, demonstrating the use of Flask Blueprints, SQLAlchemy for database management, and Flask-Login for user authentication. The application allows users to create, read, update, and delete blog posts.

## Features

- **User Authentication**: Users can register, log in, and manage their posts. Secure routes are protected using Flask-Login.
- **CRUD Operations**: Users can create new posts, view individual posts, update existing posts, and delete posts.
- **Error Handling**: Custom error pages for 403 (Forbidden), 404 (Not Found), and 500 (Internal Server Error).
- **Pagination**: Posts are paginated to enhance user experience on the home page.

## Project Structure

- **Blueprints**:
  - `main`: Handles the home page and about page.
  - `posts`: Manages blog posts including creation, updating, and deletion.
  - `errors`: Manages custom error pages.

- **Models**:
  - `Post`: Represents a blog post with fields for title, content, and author.

- **Forms**:
  - `PostForm`: Used for creating and updating blog posts.

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/flask-blog.git
