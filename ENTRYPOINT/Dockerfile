FROM almalinux:9
RUN  dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
# To combine both cmd and entrypoint we can use the below syntax.
CMD [ "google.com" ]
ENTRYPOINT [ "ping" ]
