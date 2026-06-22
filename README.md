# Reverse proxy web app
A web app working on nginx and Flask. Requests go to nginx on port 80 ant it forwards it to Flask on port 5000.


## Stack
nginx - reverse proxy server on port 80

 Flask (python) - a simple python web app on port 5000

## How to run 
```
git clone https://github.com/MahirMov/reverse-proxy.git

cd reverse-proxy

docker compose up -d 
```
