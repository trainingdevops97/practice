ARG version
FROM almalinux:$(version:-8)
RUN dnf -y update && dnf -y install nginx
RUN rm -rf /usr/share/nginx/html/index.html

# This will be executed when the image is used as a base image for another Dockerfile or another project or process
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD [ "nginx" , "-g", "daemon off;" ]

