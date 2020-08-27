# BOOK REVIEW 
<hr/>
<br/>

## PROJECT SCREENSHOT

## CREATING FASK SERVER 
### Create server syntax 
    ```
    from flask import Flask
    app = Flask(__name__)

    @app.route('/')
    def hello_world():
        return 'Hello, World!'
    ```
### Run server command 
        >   on linux export appName.py
            ```
            $ export FLASK_APP=main.py
            $ export FLASK_ENV=development
            $ flask run
            ```
        >   on window we need to set environment variable ps is powershell make sure venv is activated 
            ```
            (venv) PS > $env:FLASK_APP = "app.py"
            (venv) PS > $env:FLASK_ENV= "development"    # optional
            (venv) PS > flask run
            ```
## POSTGRES DATABASE 
    ### postgres vs mysql 
    [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)
        >   postgres
            >>  open source db
            >>  object relational database 
            >>  docs: 
        >   mysql   