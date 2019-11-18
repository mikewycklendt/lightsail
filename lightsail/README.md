# PROJECT: LINUX SERVER CONFIGURATION

## IP ADDRESS

The static IP Address of the server is:

```
3.134.26.61
```

## URL

The URL of the server is:

```
http://www.dcadventuresonline.com
```

I bought it through Route 53 and configured the DNS in the lightsail console and the Nameservers in the Route 53 console.  I will be using this server for a personal project in the future which is why I registered this domain.

## SOFTWARE INSTALLED

The following software is installed on the server:

1. python 2.7 - sudo apt-get install python-minimal
2. pip - sudo apt-get install python-pip
3. Apache2 - sudo apt-get install apache2
4. MODWSGI - sudo apt-get install libapache2-mod-wsgi
5. postgresql - sudo apt-get install postgresql
6. flask - sudo pip install flask
7. SQLAlchemy - sudo pip install SQLAlchemy
8. OAuth2 - sudo pip install python-oauth2

## CONFIGURATIONS MADE

Changed ssh port from 22 to 2200

Configured WSGI to point to var/www/html/catalog/catalog/application.wsgi

Configured PostgreSQL to listen to my IP Address for it's databases

Set up Oauth2 to work in the google API console

## 3RD PARTY RESOURCES

None