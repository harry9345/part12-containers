FROM node:16

WORKDIR /usr/src/app

COPY --chown=node:node . .

COPY . . 

RUN npm ci 

ENV DEBUG=test-docker:*

USER node

CMD npm start