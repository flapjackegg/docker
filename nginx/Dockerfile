#
# Nginx Dockerfile
#
# https://github.com/dockerfile/nginx
#

# Pull base image.
# FROM dockerfile/ubuntu
FROM nginx

COPY ./nginx/default.conf /etc/nginx/conf.d/
# COPY *.conf /etc/nginx/sites-enabled/

# Define default command.

# Expose ports.
EXPOSE 80
EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]
