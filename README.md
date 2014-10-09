nginx-node
==========
Base nginx + nodejs image.

Nginx config
------------
Create Dockerfile and copy your own nginx config


    FROM jorgenfb/nginx+nodejs
    COPY nginx.conf /etc/nginx/nginx.conf
