FROM almalinux:8
RUN yum install nginx -yum && rm -rf usr/share/nginx/html/index.html
COPY index.html usr/share/nginx/html/index.html
CMD ['nginx','-g','demonoff']
EXPOSE 80/tcp
LABEL Narendra=MACHINE
Env Narendra

