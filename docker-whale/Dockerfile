FROM docker/whalesay:latest
RUN apt-get -y update && apt-get install -y fortunes
RUN echo 'I got run'
CMD /usr/games/fortune -a | cowsay
