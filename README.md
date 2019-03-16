Overview
--------

This is a project is to deploy a sports catalog web application to amazon (AWS) server, and properly securing the application to ensure application remains stable and that user’s data is safe


The IP address and SSH port of server
------------
1) 3.86.81.242
2) SSH Port 2200

The complete URL to your hosted web application
-------------------
3.86.81.242.xip.io

A summary of software you installed and configuration changes made, and a list of any third-party resources you made use of to complete this project.
-------------------
1) Install Lightsail AWS server https://lightsail.aws.amazon.com/ls/webapp/home/instances
2) Install git bash / putty 
3) Git clone the sports catalog to /var/www/project/project from github
4) Install apache2
5) Install mod_wsgi
6) Change config in /etc/apache2/sites-enabled/111-default.conf: config server address, and project location and directory
6) Create first wsgi into /var/www/project
7) Install PostgreSQL
8) Install python dependencies to run the sports catalog application
9) Changed the google developer console to add in server and xip.io

SSH key you created for the grader - Notes to Reviewer
-------------------
1) LinuxCourse is the private SSH key
2) grader is the passphrase
3) Should be able to access through ssh grader@3.86.81.242 -p 2200 -i ~/.ssh/linuxCourse

Third party resources
-------------------
1) https://lightsail.aws.amazon.com/ls/webapp/home/instances
2) https://github.com/capcapcappuccino/project2
3) https://github.com/capcapcappuccino/project3
4) https://console.developers.google.com/apis/credentials?project=sportscatalogapp
5) https://console.developers.google.com/apis/credentials/consent?project=sportscatalogapp
6) https://knowledge.udacity.com/?nanodegree=5d0abf4a-496f-11e8-b517-e31790f491a9
