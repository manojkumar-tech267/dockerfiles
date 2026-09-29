FROM almalinux:9
RUN dnf install nginx -y
# root access required to create user or install packages
RUN useradd roboshop
USER roboshop
# now container runs with roboshop user
CMD ["sleep","100"]