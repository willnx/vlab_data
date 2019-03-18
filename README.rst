#########
vLab Data
#########

This server is for monitoring vLab.


Getting Started
===============

1. Deploy a VM and install docker and docker-compose
2. Add two VMDKs to hold the databases for InfluxDB and ElasticSearch
3. Install htpsasswd and configure a user/password for ElasticSerach within the `NGINX layer <https://www.digitalocean.com/community/tutorials/how-to-set-up-basic-http-authentication-with-nginx-on-ubuntu-14-04>`_
4. Copy the configs and docker-compose files from this repo to the appropreate locations on the data server VM
