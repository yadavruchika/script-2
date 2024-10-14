#!/bin/bash

<<note

This script will install NGINX

note

echo "**********INSTALLING NGINX*********"

sudo apt-get update
sudo apt-get install nginx -y

sudo systemctl start nginx
sudo systemctl enable nginx

echo "*********INSTALLING NGINX*********"


