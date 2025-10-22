FROM ubuntu:22.04
RUN apt update
RUN apt -y install nginx=1.18.* tree
RUN echo "<marqee> Ola k ase</marquee>" > /var/www/html/index.html
EXPOSE 80
CMD [ "/bin/ngins", "-g", "dameon off;" ]


