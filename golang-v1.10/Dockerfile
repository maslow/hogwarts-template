FROM golang:1.10
RUN curl -sL https://deb.nodesource.com/setup_8.x | bash -
RUN apt-get install -y nodejs

RUN npm install -g mocha

ADD codes /app/codes