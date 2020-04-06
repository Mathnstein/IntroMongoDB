# IntroMongoDB

We will be following along with this [Mongo DB Course](https://www.coursera.org/learn/introduction-mongodb?).

## Setup
Setup a venv and activate it. (python venv .venv)
You will also need to have:
- MongoDB enterprise downloaded (for mongo shell)
- Mongo Compass as an IDE for querys
- Jupyter hooked up to call notebooks and communicate with mongo
    - `pip install -r requirements.txt` will install additional python packages

## Lesson 01: NoSQL database in contrast to JSON
JSON is a great mental model to how to work with data; nested dictionary structures that can take on various arrays, strings or values.

There are templates for connection commands to the mongo shell inside of the mongoDB cluster (Atlas). Through the mongo shell, you upload data and specify the collection, database and specific data type ('CSV' --headline, etc.).

I have attched the data that can be loaded with `mflix/movies_initial.csv`. Once loaded, you can use Mongo Compass to actually view and query the data.

To interact with Mongo in python we use PyMongo. See the notebook files to see my notes on basic aggregating and how to find keys in a database.