# Build a realtime traffic monitor using Python and Pusher

This is a raw project how to build a realtime website traffic monitor using [Python](https://www.python.org/) and [Pusher](https://pusher.com/).
* Example:
* When user link on site: [Main Page](http://cm45285.tmweb.ru/index.html)
* Show traffic on DataBase: [Dashboard](http://cm45285.tmweb.ru/dashboard.html)

## Prerequisites

What things you need to install the software.

* Git.
* Python.
* Pip.

## Install

Clone the git repository on your computer

```
$ git clone https://github.com/ShalamovMax/Users-Traffic-monitor
```

You can also download the entire repository as a zip file and unpack in on your computer if you do not have git.

After cloning the application, you need to install it's dependencies.

```
$ cd path/to/project
$ python3 -m venv .venv # activate virtual environment (you can use the other command too)
$ source .venv/bin/activate # windows has their own method
$ python dbsetup.py
$ pip install flask
$ pip install httpagentparser
$ pip install pusher
$ export FLASK_ENVIRONMENT=development # not necessary
$ flask run
```

You should see the application in action.

## Built With

* [Pusher](https://pusher.com/) - Hosted APIs to build realtime apps with less code
* [Python](https://www.python.org/) - a programming language that lets you work quickly and integrate systems more effectively
* [Flask](http://flask.pocoo.org/) - a microframework for Python based on Werkzeug, Jinja 2 and good intentions
