My Blog Project

My Blog Project is a web application that allows users to create, edit, and delete blog posts. Users can also comment on posts and view posts by other authors. This project is built using Flask, SQLAlchemy, and PostgreSQL.

Features

User authentication (sign up, log in, log out)
Create, edit, and delete blog posts
Add comments to posts
View posts by different authors
Pagination for posts
Responsive design
Technologies Used
Flask: A lightweight WSGI web application framework in Python.
SQLAlchemy: SQL toolkit and Object-Relational Mapping (ORM) library for Python.
PostgreSQL: A powerful, open-source object-relational database system.
Flask-Bcrypt: For password hashing.
Flask-Login: For user session management.
Flask-WTF: For form handling.
HTML/CSS/Bootstrap: For the frontend layout and design.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/my-blog-project.git
cd my-blog-project
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the dependencies:

bash
Copy code
pip install -r requirements.txt

Configure the database:

Update the database configuration in config.py with your PostgreSQL credentials.

Initialize the database:

bash
Copy code
flask db init
flask db migrate -m "Initial migration."
flask db upgrade
Run the application:

bash
Copy code
flask run

Usage

Home Page:

View all blog posts.
Navigate to individual post pages.
User Authentication:

Sign up for a new account.
Log in to an existing account.
Log out from the account.
Create Post:

Create a new blog post after logging in.
Edit/Delete Post:

Edit or delete your own blog posts.
Add Comment:

Add comments to any blog post.

Contributing
Fork the repository.
Create a new branch.
Make your changes.
Submit a pull request.
