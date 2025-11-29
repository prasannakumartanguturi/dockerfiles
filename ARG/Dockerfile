# ARG instruction is used to pass variables at build tym, we can't access this ARG variables inside comtainer
# we can pass ARG before FROM instruction to pass version to base image

# ARG VERSION  ->  we can't access this ARF after FROM instruction
# FROM nginx:${VERSION:-9}

FROM nginx:9
ARG course = "devops_docker" \
    trainer = "siva" 
ENV course = "docker" \
    trainer = "sivakumatM"
RUN echo "couse=${course} trainer = ${trainer}"
CMD ["sleep","1000"]

