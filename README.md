# gmap-container
Run frontend and backend 

git clone https://github.com/somphongph/gmap-container.git

git submodule init

git submodule update

Add Host file (C:\Windows\System32\drivers\etc)
127.0.0.1       devweb.local
127.0.0.1       devwebapi.local


Create and Setup Config file
gmap-netcore
Create and Setup appsettings.json (See example appsettings.example.json)

gmap-vue
Create and Setup .env (See example .env.example)


cd gmap-container
docker-compose build
docker-compose up


Open browser
http://devweb.local