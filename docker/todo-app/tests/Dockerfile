FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/front-end
ADD node_modules.tar.gz ./
COPY . .
ENTRYPOINT npm test