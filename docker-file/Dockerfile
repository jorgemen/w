FROM ubuntu:22.04
RUN apt update
RUN apt -y install nginx=1.18.* tree
RUN echo "<marquee>Ola k ase</marquee>" > /var/www/html/index.html
EXPOSE 80
ENTRYPOINT [ "/usr/sbin/nginx"]
CMD [ "-g", "daemon off;" ]

