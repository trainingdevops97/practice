FROM almalinux:9
RUN dnf -y update && dnf -y install nginx
CMD ["nginx", "-g", "daemon off;"]
ENV MANGODB_URL="mangodb.dev.teckbase.online" \
    MAGODB_USER="admin"
