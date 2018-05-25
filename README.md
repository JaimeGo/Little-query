# LittleQuery

Flask app developed with students at PUC for the Databases course.

## Requirements

* 🐘 [PostgreSQL](https://www.postgresql.org/download/)
* 🍃 [MongoDB](https://www.mongodb.com/download-center?jmp=nav#community)
* ⚗ [Flask](http://flask.pocoo.org/docs/0.11/installation/)
* Install requirements.txt:
```
pip3 install -r requirements.txt
```

## Use
1. Iniciate databases
2. Iniciate the app:
```shell
export FLASK_APP=flaskr
python3 -m flask run
```

Our app will run in http://127.0.0.1:5000/ and show cards, each of which represents a query to the databases.
