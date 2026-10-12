#pull base image from python in dockerhub
FROM python:3.8-slim

#creating working directory in image
WORKDIR /app

#copying the files inside the working directory

#COPY . /app
COPY app.py /app
COPY Dockerfile /app

#runing the application
CMD ["python", "app.py"]