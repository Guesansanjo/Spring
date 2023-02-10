# Spring 3

[Spring docs](https://spring.io/projects/spring-boot)

Spring has modules , like security , loggin ...

![alt](./img/alt.jpg)

## Spring initizlizer

[Spring initzializer](https://start.spring.io/)

to change version of spring we can apply o the pom.xml .

Everything else managed for us.

![](./img/pom.jpg)

The pom xml has packages and dependencies of the project , managed by maven in our case.


## Running the app


If tomcat starts works fine , it starts in port 8080.

![alt](./img/tom.jpg)


## Setting up Spring app from 0
What SpringAplication.run(Main.class,args); it runs our Main class and also run everything it gets from the command line "args".

![alt](./img/setupSpring.jpg)

## What is tomcat

Implementation of jakarta servlet , extension and web socket tech.
Provides pure java http wb server , a java web server app.

![alt](./img/tomcat.jpg)

Listens to port 8080 -> processes request -> response to client.
There are more web servers example : jetty.

We run the app and see :8080

[http://localhost:8080/](http://localhost:8080/)
Thus this label we shall see.

![alt](./img/white.jpg)

We set a request , we recieve the request but nothing was found "no explicit mapping".
Cant process request