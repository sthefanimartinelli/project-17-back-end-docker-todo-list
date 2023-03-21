FROM node:14-alpine

WORKDIR /app

EXPOSE 3001

ADD node_modules.tar.gz .

COPY ./src ./src

COPY package.json .

COPY package-lock.json .

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
