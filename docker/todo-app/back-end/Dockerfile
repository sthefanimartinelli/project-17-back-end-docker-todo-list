FROM node:14-alpine

WORKDIR /app

EXPOSE 3001

ADD node_modules.tar.gz .

COPY ./src ./src

COPY package.json .

COPY package-lock.json .

ENTRYPOINT [ "npm" ] 

CMD [ "start" ]

# inicie a aplicação com o comando npm test respeitando as seguintes restrições:
# ao subir um container baseado na imagem buildada a partir desse Dockerfile, o comando npm deve ser rodado sempre;
# ao subir um container baseado na imagem buildada a partir desse Dockerfile, deve ser possível sobrescrever o comando test.
