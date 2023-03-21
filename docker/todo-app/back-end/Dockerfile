FROM node:14-alpine

EXPOSE 3001

ADD node_modules.tar.gz ./app

COPY . ./app

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
