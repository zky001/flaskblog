Intro
This is a person blog, powered by flask.

Steps:

1. python setup.py install
install all extensions:for example:flask,flask-wtf and so on

2. python manager.py createall
create all tables in mysql, but MUST modify config.py:SQLALCHEMY_DATABASE_URI

3. python manager.py runserver and Visit 127.0.0.1:5000/login, put your posts.