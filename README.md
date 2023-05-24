# Testing a pymongo/Flask app using pytest and mongomock

This repo contains an example on how to use mongomock to replace a pymongo.MongoClient when testing a flask app

The test cases and structure of the app are based on a real project where I was scratching my head over this exact problem.

To try it out, clone this repo, install the dependencies in requirements.txt and run pytest:

``` python
git clone https://github.com/alkc/flask-mongomock-example.git
cd flask-mongomock-example
pip install --requirement requirements.txt
pytest .
```

