# Bydefault container will run with root user which is not recommended, so need to add a USER so that container will run that user

FROM nginx
WORKDIR /opt/server
RUN useradd roboshop
USER roboshop
CMD ["nginx", "-g", "daemon off;"]