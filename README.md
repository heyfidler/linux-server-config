# linux-server-config

## info
- user: grader
- server IP address: 35.182.190.182
- ssh port: 2200
- app URL: http://ec2-35-182-190-182.ca-central-1.compute.amazonaws.com

## installed software
- apache2
- python pip
- sqlalchemy
- flask
- oauth2client
- postgreSQL

## changes
- updated packages
- add user 'grader' 
- give sudo privledges to 'grader'
- change ssh port to 2200
- deny logins by root
- setup ufw to only allow ports 2200, 80, and 123
- install catalog app and needed software

## resources
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
