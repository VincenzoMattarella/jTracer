# JTracer
Tool used to monitor the execution of a Jolie Service

[1 - Requirements]

[2 - JTracer Usage]

## 1 - Requirements

[JolieLang](http://jolie-lang.org/) and [Docker](https://www.docker.com/) must be installed on your computer. 
[Docker](https://www.docker.com/) must be running.

## 2 - JTracer Usage

Just open a terminal and move inside jTracer directory.

At this point just type ```docker build -t jtracer .``` to build the jtracer image.

Now you can run your image typing ```docker run -p 8000:newPortNumber -v computerPath:/microservice/shared jtracer``` where 8000 is the default port which is exposed and newPortNumber is the port in which you want to run the image. An example for your computer path is: /Users/Username/Desktop.

Open your browser and go to : ```http://localhost:portNumber/index.html```
