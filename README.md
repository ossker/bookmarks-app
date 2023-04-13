# Bookmarks app 👨‍💻

Django web application that allows you to share photos with your friends!

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## Features ⭐

- Registration, logging in and logging out, editing and resetting the password
- Logging in using accounts on the sites Facebook and Google
- JavaScript bookmarklet for downloading images from another website and embedding them in an application
- Dynamic AJAX paging to image list view
- Tracking views and likes
- User following system
- User activity stream


## Environment Setup 🚀

Clone the repo:

```bash
  $ git clone https://github.com/ossker/bookmarks-app.git
```


If virtualenv is not installed:

```bash
    $ pip install virtualenv
```

Create a virtual environment inside your folder with project:
```bash
    python3 -m venv env
```

Activate the environment everytime you open the project:
```bash
    env/Scripts/activate
```

Install requirements:
```bash
    $ pip install -r requirements.txt
```

Go to project folder:
```bash
    $ cd bookmarks
```

Run migrations for database:
```bash
    $ python manage.py makemigrations
```
```bash
    $ python manage.py migrate
```
Create superuser for admin login:

```bash
    $ python manage.py createsuperuser
```

Now you can run the server to see your application up & running 🚀
```bash
    $ python manage.py runserver
```

To exit the environment:
```bash
    $ deactivate
```

## Leave a ⭐ if you like 👨‍💻
