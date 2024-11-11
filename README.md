# Tech Blog

## Description
A CMS-style blog site built with MVC architecture where developers can publish articles, blog posts, and share their thoughts. The application features user authentication, dynamic content creation, and interactive commenting systems.

## Table of Contents
[Installation](#installation)  
[Usage](#usage)  
[Features](#features)  
[Technologies](#technologies)  
[Contributing](#contributing)  
[License](#license)

## Installation
1. Clone the repository:
~~~
git clone git@github.com:yourusername/tech-blog.git
~~~

2. Install dependencies:
~~~
npm install
~~~

3. Create .env file in root directory:
~~~
DB_NAME=tech_blog_db
DB_USER=postgres
DB_PASSWORD=your_password
SESSION_SECRET=your_session_secret
~~~

4. Set up database:
~~~
psql postgres
CREATE DATABASE tech_blog_db;
~~~

5. Start the server:
~~~
npm start
~~~

## Usage
1. Visit `http://localhost:3001` in your browser
2. Create an account or log in
3. View existing blog posts on the homepage
4. Create, edit, and delete your own posts from the dashboard
5. Comment on other users' posts
6. Manage your content through the user dashboard

## Features
- User authentication
- Create, read, update, and delete blog posts
- Comment on posts
- Personal dashboard
- Session management
- Responsive design
- Secure password hashing
- Database persistence

## Technologies
- Node.js
- Express.js
- PostgreSQL
- Sequelize ORM
- Handlebars.js
- Express Session
- bcrypt
- dotenv
- HTML/CSS
- JavaScript

## Contributing
1. Fork the repository
2. Create your feature branch:
~~~
git checkout -b feature/AmazingFeature
~~~
3. Commit your changes:
~~~
git commit -m 'Add some AmazingFeature'
~~~
4. Push to the branch:
~~~
git push origin feature/AmazingFeature
~~~
5. Open a Pull Request

## License
Please refer to the LICENSE in the repo.
