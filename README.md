# Linux Server Configuration

### Summary
The goal of this project was to set up a Linux distribution using an AWS Lightsail instance to host a web application. The web application being hosted is the [Car Catalog](https://github.com/jjp601/Car_Catalog_Project) project. 

### Details
IP Address: 18.217.35.245
SSH Port: 2200
URL: http://18.217.35.245

### Software and Packages
* PostgreSQL
* Apache2
* mod_wsgi
* Python
* Flask
* pip
* SQLAlchemy
* httplib2
* psycopg2
* oauth2client
* requests

### Web Server Configuration
1. Create an Amazon Lightsail Instance
    * Source: [Udacity](https://classroom.udacity.com/nanodegrees/nd004/parts/ab002e9a-b26c-43a4-8460-dc4c4b11c379/modules/357367901175462/lessons/3573679011239847/concepts/c4cbd3f2-9adb-45d4-8eaf-b5fc89cc606e)
2. SSH onto Server
    * Source: [Udacity](https://classroom.udacity.com/nanodegrees/nd004/parts/ab002e9a-b26c-43a4-8460-dc4c4b11c379)
3. Change SSH port
    * Source: [Ask Ubuntu](https://askubuntu.com/questions/16650/create-a-new-ssh-user-on-ubuntu-server)
4. Configure Firewall
    * Source: [Udacity](https://classroom.udacity.com/nanodegrees/nd004/parts/ab002e9a-b26c-43a4-8460-dc4c4b11c379/modules/357367901175461/lessons/4331066009/concepts/48010894990923)
5. Create new user `grader`
    * Source: [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-add-and-delete-users-on-an-ubuntu-14-04-vps)
6. Create an SSH key for `grader`
    * Source: [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2)
7. Install Apache & mod_wsgi
    * Source: [Udacity](https://blog.udacity.com/2015/03/step-by-step-guide-install-lamp-linux-apache-mysql-python-ubuntu.html)
8. Install & Configure PostgreSQL
    * Source: [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps)
9. Deploy Flask application
    * Source: [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
10. Launch the Web application
    * Restart the Apache Server: `sudo service apache2 restart`
    * Open your browser to http://18.217.35.245
