FROM almalinux:9
RUN dnf install nginx -y
#By specifying this, we are letting the user of our image know that its open on port number 80, Its does'nt add any functionality. It's our responsibility to give right information of ports.
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
