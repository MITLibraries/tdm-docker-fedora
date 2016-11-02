
Fedora 4.7.0 Container
======================

Start a Fedora container:

    $ docker run --name fedora -p 8080:8080 -p 61613:61613 -d mitlibraries/fedora

Go to http://localhost:8080/fcrepo/. This container exposes tomcat on port 8080 and ActiveMQ's STOMP endpoint on port 61613.
