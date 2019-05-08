# Project: Linux Deployment (Novel Library)

Novel library is a novel catalog website hosted in Amazon lightsail ubuntu linux machine which provides information about novels from various authors. 

# Instructions

## The IP address and SSH port to access server.

* IP - 13.232.236.221
* SSH port - 2200

##  The complete URL to the hosted web application.

* http://13.232.236.221/ or http://13.232.236.221.xip.io

* The website is configured to make use of only two ports for connection http(80) and ssh(2200).


## Summary of softwares installed and configuration changes made.

* The application is hosted on Ubuntu 16 linux server/machine instance from Amazon lightsail.
* User **'grader'** has root level access and requires RSA key to login to the linux instance.
* Default SSH port is disabled and connections to the server can be made through SSH(2200), http(80), 123 ports
* root user login is disabled and key based auth is enforced.
* The **Novel library** Python flask full stack application runs on Apache server as WSGI application using Postgresql database server.
* The modules installed are Apache2, mod_wsgi, psycopg2.

## Third-party resource

* Python docs
* Flask docs
* Postgresql docs
* SQLAlchemy docs
* Apache docs
* WSGI docs
* Git