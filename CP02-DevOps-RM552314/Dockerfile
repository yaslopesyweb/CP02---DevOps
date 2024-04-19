#Inicializar o build da imagem
FROM nginx:latest

RUN apt-get -y update
RUN apt -y install vim && apt -y install curl

RUN mkdir -p /meu-site

COPY ./meu-site/index.html /meu-site
COPY ./meu-site /usr/share/nginx/html


LABEL Image="Entrega do projeto CheckPoint 2 de DevOps & Cloud Computing"\
    Author="RM552314 - Yasmin Araujo Santos Lopes"\
    Verion="1.0"\
    Decription="Imagem que contem o WebServer NGinx com um jogo de Adivinhar um número"\
    E-mail="yaslopesyweb@gmail.com"

EXPOSE 80