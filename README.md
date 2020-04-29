#Nginx configyration

#Getting Started
This is the configuration file for nginx web server

#Installing
copy this file to the directory /etc/nginx/

#Running the tests
After transferring the file to the nginx directory, run the command
 sudo nginx -t

If the configuration check is successful, run the command
 sudo nginx -s reload
this command is needed for nginx to re-read the configuration file and apply it

