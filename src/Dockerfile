FROM python:3.11-bullseye
RUN pip3 install Flask
RUN pip3 install Flask-Login
RUN pip3 install Flask-SQLAlchemy
COPY . /opt/app
WORKDIR /opt/app
CMD [ "python", "./app.py" ]