## About the website

This is my final project for [Harvard CS50x](https://cs50.harvard.edu/x/2020/) course. It's a website named *“I hate it”* that was created in order to give everyone a chance to let the world know about what they really don't like. Every user can add a story about anything they think is annoying.

There are different sections on the website. You can read new stories or random ones, add your own story or create an account in order to leave a comment. There is also a rating system on the site. Every user can vote for or against any story. The most liked stories can be seen in the Top section. If you want to fing a particular story, use the search function.

Now the database of stories is filled with quotes from different books as examples (except for the last two stories that were added while creating a video for submitting the project).

## Description

Web application is based on Flask framework. I used [cs50 python lib](https://github.com/cs50/python-cs50) for working with database, it can be freely downloaded from github or replaced with something like SQLite.

## How to use

To run the web application use these commands:

```
$ export FLASK_APP=application.py
$ flask run
```

## Requirements

- python 3
- flask
- cs50
- werkzeug
