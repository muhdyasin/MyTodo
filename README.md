# MyTodo - A Simple Flask ToDo App

MyTodo is a minimal ToDo web application built using **Python Flask** and **SQLite**. It allows you to add, view, update, and delete tasks easily through a clean Bootstrap interface.

## 📋 Features

    ✅ Add new tasks with title and description  
    ✅ View a list of all your ToDos  
    ✅ Update existing tasks  
    ✅ Delete tasks when completed  
    ✅ Simple, responsive UI using Bootstrap 5

## 🛠️ Tech Stack

    - **Backend:** Python, Flask, Flask-SQLAlchemy  
    - **Frontend:** HTML, Bootstrap 5, Jinja2 templates  
    - **Database:** SQLite

## 📂 Project Structure

    ├── instance
    | ├── todo.db # SQLite database (auto-created)
    ├── static # You can add your CSS and JavaScript files in this folder(Not used in this project)
    ├── templates/
    │ ├── base.html # Base template with navbar(used to demonstrate template inheritance)
    │ ├── index.html # Home page (add/view todos)
    │ ├── update.html # Update page
    ├── app.py # Main Flask application
    ├── requirements.txt

Follow these steps to run the project locally:

1. **Clone the repository**

    ```bash
    git clone https://github.com/muhdyasin/MyTodo.git
    cd MyTodo

2. **Create a virtual environment and activate it**
   
   ``` python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate

3. **Install the dependencies**

   ``` pip install -r requirements.txt

4. **Run the Flask app**
   
    ``` python app.py

5. **Open in your browser**

    Visit http://127.0.0.1:5000/ to use the app.


## 🗑️ How It Works

    Home (/): Add new ToDos and see all existing tasks.
    
    Update (/update/<sno>): Edit a ToDo by its serial number.
    
    Delete (/delete/<sno>): Remove a ToDo by its serial number.

## 📜 License

    This project is licensed under the MIT License - feel free to use, modify, and share!


## Happy coding! 🚀✨




