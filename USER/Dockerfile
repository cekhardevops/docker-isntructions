# if container has root access, it can able to access container storage as well as host storage. that might lead to security issue. 
# to run the service , there must be application specific user and should be configured USER before executing CMD.
FROM almalinux:9
RUN useradd expense
USER expense
CMD [ "sleep","100" ]