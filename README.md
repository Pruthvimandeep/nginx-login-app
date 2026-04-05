# NGINX Login App

This project creates a simple login page using NGINX.

## Build Image

docker build -t nginx-login-app .

## Run Container

docker run -d -p 8080:80 nginx-login-app

## Access

http://localhost:8080
