FROM alpine:3.1

ADD . /src/web

WORKDIR /src/web

RUN apk add --update nodejs

RUN npm install

EXPOSE 3000

RUN ls -trl

CMD ["node", "server.js"]
