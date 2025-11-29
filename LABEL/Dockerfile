FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]
#LABEL is used to provide metadata used to filter the immages
LABEL course = "docker" \
      trainer = "siva"
