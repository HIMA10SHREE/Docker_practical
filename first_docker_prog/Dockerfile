FROM ubuntu:latest

#set working dir
WORKDIR /app

#copy from host to image file system
COPY . /app

#install dependencies
RUN apt-get update && apt-get install -y python3 python3-pip

#set env variables
ENV hello world

#run command
CMD ["python3","app.py"]
