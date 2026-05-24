FROM almalinux:9
RUN dnf -y update && dnf -y install nginx 
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80
