# 🔛 Django Simple Real-time Chatting App

## 🔛 Overview

I did this django channels tutoral to know how to make Chatting apps.
I came to know how to build ASGI server using Django.

## 🔛 Preview

![django channels](https://user-images.githubusercontent.com/72008909/208657856-bd43a234-f9cf-44cd-a728-9b1ca9375a7f.gif)

I assumed there are 2 users talking each other through this app.

## 🔛 How to start?
```
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
// You need to install docker
docker run -p 6379:6379 -d redis:5
python manage.py runserver
// Connect to https://127.0.0.1:8000/chat/
```
