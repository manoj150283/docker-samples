FROM ubuntu:14.10

# make sure apt is up to date
RUN apt-get update

# install nodejs and npm
RUN apt-get install -y nodejs npm nodejs-legacy git git-core

ADD start.sh /tmp/

RUN chmod +x /tmp/start.sh

CMD ./tmp/start.sh
