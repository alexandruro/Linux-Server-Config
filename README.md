# Linux Server Configuration

This is a linux server configuration for the Udacity Full Stack Developer Nanodegree.

### How to access the website hosted by the server (an item catalog app)

The site can be accessed at http://52.40.180.78/ or http://ec2-52-40-180-78.us-west-2.compute.amazonaws.com

### How to connect to the server via SSH

The SSH port of the server is 2200. To be accessed, you need to have the *udacity_key.rsa* key in *~/.ssh/*. The command is like so:

```
ssh -i ~/.ssh/udacity_key.rsa root@52.40.180.78
```

### Software installed

* finger
* apache2
* postgresql
* flask
* psycopg2
* mod_wsgi


### Configuration 

The server is configured to be accessible only using a key-based authentication and remote login of the root user has been disabled. The only allowed connections are HTTP, SSH and NTP. All applications are up-to-date.

### Third-party resources used

http://docs.sqlalchemy.org/en/latest/dialects/postgresql.html
