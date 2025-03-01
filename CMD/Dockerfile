#Installs Base OS
FROM almalinux:9
#To add some service on the top of base OS
RUN dnf install nginx -y 
#Systemd Can be accessed by full OS. As we are using a base minimum OS, it will not start the service by its own. Unlike systemctl, we start the service and run the service maually with CMD.
CMD ["nginx", "-g", "daemon off;"]