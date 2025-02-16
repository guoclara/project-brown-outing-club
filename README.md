# BOC Trip Lottery

## Description
Weighted lottery system hosted on a website for Brown Outing Club to run. Any Brown student can enter a lottery to go on a trip, but the lottery will be weighted according to factors like previous behavior (e.g. if they were a no show before, if they already got a trip) as well as other factors. An administrative page allows editors to change the website content and database data without code knowledge. 

## Setting Up
#### Starting venv
Mac: 
`. venv/bin/activate`

Windows: 
`> venv\Scripts\activate`

#### Installing dependencies
Inside your virtual env, run: 
`pip install -r requirements.txt`

#### Loading .env File
Find the demo .env file [here](https://drive.google.com/file/d/1k8gmwnB7f437M31O55UKAT-5e8AefVvZ/view) and put it in 
your toplevel project directory

#### Running the app
`export FLASK_APP=boc/__init__.py`
`flask run`

## Testing
Integrations tests can be run with
`pytest`

## Additional Resources
https://flask.palletsprojects.com/en/1.1.x/quickstart/

https://flask-sqlalchemy.palletsprojects.com/en/2.x/quickstart/

TODO: If creating and destroying the database is not a suitable substitution for true migration, implement [alembic](https://alembic.sqlalchemy.org/en/latest/tutorial.html) 
([alternative resource](https://www.compose.com/articles/schema-migrations-with-alembic-python-and-postgresql/)).

## Contacts
* Clara Guo '23
* Anna Zhao '23
* Lucas Gelfond '23
* Ethan Asis '23


For contact info, please email [fullstack@brown.edu](fullstack@brown.edu)
