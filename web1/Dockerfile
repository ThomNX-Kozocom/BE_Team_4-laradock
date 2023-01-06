FROM node:alpine

LABEL maintainer="thomnx@kozo-japan.com"

RUN npm install express-generator nodemon -g

COPY command.sh /

ENTRYPOINT ["sh", "/command.sh"]

