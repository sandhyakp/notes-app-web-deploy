# notes-app-web-deploy
this is fork from trainwithshubham with "django-notes-app" website-deploy
Simple Notes App
This is a simple notes app built with React and Django.

Requirements
Python 3.9
Node.js
React
Installation
Clone the repository
git clone https://github.com/LondheShubham153/django-notes-app.git
Build the app
docker build -t notes-app .
Run the app
docker run -d -p 8000:8000 notes-app:latest
Nginx
Install Nginx reverse proxy to make this application available

sudo apt-get update sudo apt install nginx
