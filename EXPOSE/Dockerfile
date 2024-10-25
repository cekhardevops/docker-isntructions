# Expose instruction meant for providing metadata like on which port application is listening end users request. 
#will be helpful to provide port information to users

FROM almalinux:9
EXPOSE 8080
RUN dnf install nginx -y
CMD [ "nginx", "-g", "daemon off;" ]