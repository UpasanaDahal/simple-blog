Hey there!
Welcome to SimpleBlog, a basic blog application built using Django. This is a beginner-friendly project that helps you understand how to work with Django views, models, templates, and forms. It’s simple, clean, and does just what it says.

What This App Can Do:
-Show a list of all blog posts
-Search blog posts by title
-View a single post in detail
-Add a new blog post through a form
-Delete blog posts (no login required)
-Styled using a bit of Bootstrap to keep it neat

Project structure:
simpleblog/
├── blog/
│   ├── templates/blog/
│   │   ├── base.html
│   │   ├── post_list.html
│   │   ├── post_detail.html
│   │   ├── add_post.html
│   │   └── delete_post.html
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── simpleblog/
│   ├── settings.py
│   ├── urls.py
├── db.sqlite3
└── manage.py

Follow this to run this project in your machine:
-git clone https://github.com/UpasanaDahal/simple-blog
-cd simpleblog
-python -m venv venv
-venv\Scripts\activate
-pip install django
-python manage.py migrate
-python manage.py runserver


