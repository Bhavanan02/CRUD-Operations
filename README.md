## Flask CRUD Application
This project is a simple CRUD (Create, Read, Update, Delete) application built using Flask and SQLAlchemy. It provides users with a basic interface to interact with a database.

## Installation
1. Clone the repository to your local machine:

'''bash
Copy code
git clone <repository-url>'''
2.Navigate into the project directory:

'''bash
Copy code
cd <project-directory>'''
3.Create a virtual environment:

'''Copy code
python -m venv venv'''
4.Activate the virtual environment:

'''On Windows:

Copy code
venv\Scripts\activate'''
5.Install dependencies:

'''Copy code
pip install -r requirements.txt'''
## Usage
1.Ensure you have a database set up and configured in the config.py file. Modify the SQLAlchemy URI as needed.

2.Initialize the database:

'''csharp
Copy code
flask db init'''
3.Create the necessary migrations:

'''Copy code
flask db migrate'''
4.Apply the migrations:

'''Copy code
flask db upgrade'''
5.Run the Flask application:

'''arduino
Copy code
flask run'''
6.Access the application in your web browser.

## Technologies Used
-Flask: Lightweight web application framework in Python, known for simplicity and flexibility.
-SQLAlchemy: SQL toolkit and Object-Relational Mapping (ORM) library for Python, simplifies database interaction.
-HTML: Standard markup language for creating web pages, defining structure and content.
-CSS: Style sheet language for controlling web page presentation and enhancing user experience.
