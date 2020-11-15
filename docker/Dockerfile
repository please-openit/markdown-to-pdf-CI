FROM node:12-buster

RUN apt-get update
RUN apt-get -y install chromium
RUN npm install -g mdpdf --unsafe-perm=true --allow-root
RUN wget https://github.com/muquit/mailsend-go/releases/download/v1.0.9/mailsend-go_1.0.9_linux-64bit.deb
RUN dpkg -i mailsend-go_1.0.9_linux-64bit.deb
RUN npm install -g markdown-toc

RUN mkdir /data
WORKDIR /data
