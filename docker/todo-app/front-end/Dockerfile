FROM node:14-alpine AS build
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
COPY .env .
EXPOSE 3000
ENTRYPOINT ["npm start"]