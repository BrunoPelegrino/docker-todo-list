FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todo-app/todotests

ADD node_modules.tar.gz ./

COPY . .

CMD [ "npm", "test" ]