# API-and-DB
Python API with DB

This is a simple python script and sqlite database file which demonstrates how to create an API which can return data from the database and output it in JSON.
This is not my unique work, most of the source code is taken from this tutorial: https://programminghistorian.org/en/lessons/creating-apis-with-python-and-flask

To test the API: 
Run it on a localhost using command "python api_final.py" in the same directory.
Test searching data from the database with the following URL:
  http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis
or to search by multiple parameters:
  http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis&published=1993
