FROM node:8

ADD src /opt/src/

WORKDIR /opt/src/

RUN npm init -y

RUN npm install --save uuid

ENTRYPOINT [ "node", "Musician.js" ]