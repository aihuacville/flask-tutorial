# Flask Tutorial

The goal of this project is to follow through Flask's documentation building a blog system.
Learning objectives: 
1. Build a Flask from scratch
2. CRUD in Sqlite database
3. Professional project layout
4. Inspire beginners to build a Flask app fast

Outcome: basic log application called Flaskr
1. Users will be able to register, log in, create posts, and edit or delete their own posts.
2. You will be able to package and install the application on other computers.
3. Deploy and monitor using CI/CD tool on cloud.

Final project: 
1. Build an AI Flask app

## Set up

### Create an environment
`mkdir flask-tutorial`
`cd flask-tutorial`
`python3 -m venv .venv`
### Activate the environment
`source .venv/bin/activate`

### Install Flask
`python3 -m pip install --upgrade pip`
`pip install Flask`

### Run hello.py
`flask --app hello run`
`flask --app hello run --debug`

Reference: https://flask.palletsprojects.com/en/stable/