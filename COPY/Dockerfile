FROM almalinux:9
RUN  dnf -y update && dnf -y install nginx
CMD  ["nginx", "-g", "daemon off;"]
# Remove the defauult ngnix html file which is available in the ngix image. 
RUN  rm -rf /usr/share/nginx/html/index.html
# copy the content which is available in local to the nginx html directory in the container
COPY qi/ /usr/share/nginx/html/
