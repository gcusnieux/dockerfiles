FROM gcusnieux/ubuntu

MAINTAINER Guillaume Cusnieux <@gcusnieux>

# Install nginx
RUN add-apt-repository -y ppa:nginx/stable
RUN apt-get update
RUN apt-get install -y nginx-light

EXPOSE 80