# serverproject

This README matches the Linux Server Configuration Project for Udacity's Full Stack Web Developer nanodegree. The information required for the grader is as follows:

Server IP: 35.165.163.65
SSH Port: 2200
URL to Hosted Web Application: 35.165.163.65.xip.io

The software installed on the server in order to complete this project was:

* finger
* apache2
* libapache2-mod-wsgi
* postgresql
* python-psycopg2
* python-flask
* python-sqlalchemy
* python-pip
* oauth2client
* requests
* httplib2

The configuration changes made to the server were:

* Update currently installed packages
* Change the SSH port from 22 to 2200
* Configure UFW to only allow connections on ports 2200, 80, and 123
* Create users with the appropriate levels of access

Resources consulted for this project include:

* https://www.postgresql.org/docs/
* http://flask.pocoo.org/docs/1.0/
* https://modwsgi.readthedocs.io/en/develop/
* https://stackoverflow.com/
* http://xip.io/
* http://docs.sqlalchemy.org/en/latest/core/engines.html
* https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
* The Udacity Support Forums and the course materials/videos
