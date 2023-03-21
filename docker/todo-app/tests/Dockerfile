FROM mjgargani/puppeteer:trybe1.0

ADD node_modules.tar.gz ./app

COPY . ./app

ENTRYPOINT [ "npm" ]

CMD [ "test" ]
