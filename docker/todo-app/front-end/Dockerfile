FROM node:14-alpine

WORKDIR /app

EXPOSE 3000

ADD node_modules.tar.gz .

COPY ./public ./public

COPY ./src ./src

COPY package.json .

COPY package-lock.json .

COPY .env .

ENTRYPOINT [ "npm" ]

CMD [ "start" ]