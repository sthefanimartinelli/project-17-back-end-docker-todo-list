FROM node:14-alpine

ADD node_modules.tar.gz ./app

COPY . ./app

EXPOSE 3001

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
