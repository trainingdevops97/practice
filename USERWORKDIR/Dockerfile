FROM almalinux:9
RUN dnf -y update && dnf -y install nginx 
CMD ["nginx"; "-g"; "daemon off;"]

# Once ngix installed user need to create and it should be nonpriviledged user and then we need to change the ownership of the nginx directory to that user and then we need to switch to that user and then we need to run the nginx command to start the nginx server.
RUN useradd practice

USER practice
WORKDIR /home/practice

