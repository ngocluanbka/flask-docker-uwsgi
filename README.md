
Put your Python code with inside docker container in PATH:

> /app

*Take care, your main Python file must be called: app.py

Start your container with
> docker run -d -p 5000:5000 -v /your-app-folder:/app ngocluanbka/flask-docker-uwsgi
