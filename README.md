
Install Dependencies 

```
pip install -r requirements.txt
```
(Note: To be run with Python3)

Set Database (Make Sure you are in directory same as manage.py)
```
python manage.py makemigrations
python manage.py migrate --run-syncdb
```
Create SuperUser 
```
python manage.py createsuperuser
```
You can now run the app, and start testing and modifying it!
```
python manage.py runserver
```
