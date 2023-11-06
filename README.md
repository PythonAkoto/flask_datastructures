# Data Structures and Algorithms With Python & Flask

This is a small web app that showcases the implementation of data structures and algorithms using Python & Flask.

This Flask app common data structures such as ***linked lists, hash tables, stacks***, and searching algorithms such as ***binary search***.

This is a blogging app that is meant to show you how these data structures and algortihms are created & implemented in a 'real world scenario'.

## Development Envrionment 

To set up your development envrionment correctly, you will first need to create your virtual environment:

`py -m pip install --use r virtalenv`

This will allow you create your virtual enviornment:

`python -m venv virtualenv`

*Please note you can name your virtual environment anyhting, to make it easy most develeopers use `venv` or `virtualenv`.* Now you need to activate the `virtualenv` you will need type the following:

```
# Mac OS or Linux
source virtualenv/bin/activate
```

```
# Windows
.\virtualenv\Scripts\activate
```

If you need to deactivate your `virtualenv` run the following:

`deactivate`

With your virtual environment running, you can now install the required libraries:

`pip install flask flask-sqlalchemy sqlalchemy faker datetime`

Another easy way to do this is to install what you need using the `requirements.txt` file using the following command:

`pip install requirements.txt`

## Running The App

Before we do anything, we need to start the application by running:

`python server.py`

For Windows users please run:

`python .\server.py`

We will need to generate some dummy data by running the following command:

`python generate_dummy_data.py` or `python .\generate_dummy_data.py`

Now with the dummy data created you can test the endpoints created in `server.py`.  For example, you can run `http://localhost:5000/blog_post/1` to get the first blog post.  You will notice you will get a json response returned.

**Please make sure your virtual environment is running when starting the Flask app and generating the dummy data.**