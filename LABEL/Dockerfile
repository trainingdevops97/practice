FROM almalinux:9
RUN dnf update -y && dnf install nginx -y 
CMD ["nginx", "-g", "daemon off;"]
LABEL ENVIRONMENT="Development" \
      MAINTAINER="Kiran Kumar" \
      VERSION="1.0" \
      DESCRIPTION="This is a sample Dockerfile for nginx on almalinux 9" \
      AUTHOR="Kiran Kumar"