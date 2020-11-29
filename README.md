# Note-Taker web app

A simple [web application](https://medium.com/@essentialdesign/website-vs-web-app-whats-the-difference-e499b18b60b4) created with [Django](https://www.djangoproject.com/), a [Python](https://www.python.org/)-based web framework, for taking notes.

## Features of this application: 

This simple note-taking application is designed to support the following features:

- Allow a list of notes to be rendered into a web page GUI.
- Allow a registered user, after logging in, to create, update, delete notes in the user interface (CRUD operations).
- The notes and credentials of the user are personal, personalized and are stored in persistent storage using SQLite3 for relational DB storage.
- Users have to authenticate themselves using a form that asks for username and password. An unregistered user cannot use the note-taking feature.
- The system is currently designed in a way that is not possible for other users of the application to modify posts that were not created by them, though they can view them.

## Requirements:

- Python version 3.6+ to run a Python server on your device ([download here](https://www.python.org/downloads/))

## How to install:

1. Pull the repository
2. Open the Command Prompt and navigate to the repository's root directory
3. Run `pip install -r requirements.txt` and wait until all necessary modules are installed

## How to view:

1. Run `python manage.py runserver` in the Command Prompt in the repository's root directory
2. View the app at `http://127.0.0.1:8000/`

For quicker access you can create a shortcut that will run these 2 steps on a single click.
The app will also run automatically, if you deploy it to a web server.

## Django topics covered/used while building the application:

- Authentication
- Models, views and templates
- Static files
- Forms and form validation
- File upload with drag-and-drop
- Pagination
- Search
- Signals
- 403, 404 and CSRF error handling

## License:

[Unlicensed](https://unlicense.org) (You can use the app anyway you want for free and without attribution).
