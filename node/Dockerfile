FROM node:19

WORKDIR /usr/src/app

COPY index.js .

RUN npm init -y && \
    npm i express --save

EXPOSE 3000

ENTRYPOINT [ "node", "index.js" ]