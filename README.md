# basic-django

create virtual env
`virtualenv venv`

for windows you may need
`Set-ExecutionPolicy Unrestricted -Scope Process`

start env in windows
`venv\Scripts\activate`

start env in gitbash
`source venv/Scripts/activate`

end env
`deactivate`

see what you have installed pythonwise
`pip freeze`

in our venv we want a django app
`pip install django`

and then create our django profect
`django-admin.py startproject firstapp`

run our server in /firstapp
`python manage.py runserver`

im ordner wo venv und das projekt liegt wollen wir die git repo haben

damit andere es auch richtig installieren können
`pip freeze > requirements.txt`
