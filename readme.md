#link to video
https://youtu.be/Z1RJmh_OqeA?si=byhGSpINsXSRAk7G


#to install
pip3 install virtualenv

#create virtual env
virtualenv env


#to activate env
.\env\Scripts\activate


#to run flask application
py app.py


#to create db when facing error

on py interactive shell by typing "py", "py3" or "python" (whatever is configured for your terminal for py3)
For those of you who faced the database creation error, do the following: 
```
>>> from app import app, db
>>> app.app_context().push()
>>> db.create_all()
```
it should be created under instance directory after those commands.



