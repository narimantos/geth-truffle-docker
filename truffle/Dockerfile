FROM node:alpine

RUN apk add -t .gyp --no-cache git python g++ make \
    && npm install -g truffle \
    && apk del .gyp

RUN mkdir -p /dapp
WORKDIR /dapp
RUN ls -ltra /root/.config/
EXPOSE 8080
ENTRYPOINT []
