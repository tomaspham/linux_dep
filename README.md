#Linux Server Configuration
* ip: 18.220.74.116
* port: 2200
* url: http://itemcatalog.cf/
## used software:
* python3
* mysql, libmysqlclient-dev
* redis-stable
* pip3 packages -> check requirements.txt
* nginx
* uwsgi
* ufw - Uncomplicated Firewall (build in for ubuntu server 18.04)
## configured:
* all system packages updated
* ssh confing
* firewall config -> ufw
* mysql config
* replaced sqllite with mysql server
* wsgi config
* nginx config
* system service app add
* domain record setup (freenom)
## grader key:
* /home/grader/.ssh
## usefull resources can be found on:
* https://www.digitalocean.com/community/tutorials/
* https://help.ubuntu.com/lts/serverguide/index.html.en


## used be me:
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-18-04
https://my.freenom.com/clientarea.php