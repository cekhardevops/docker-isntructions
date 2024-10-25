FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/cekhardevops/docker-isntructions/refs/heads/main/docker-commands.txt /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]