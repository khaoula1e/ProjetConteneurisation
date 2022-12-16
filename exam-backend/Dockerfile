# Dockerfile backend

FROM node:12-alpine

WORKDIR /app
COPY ["package.json", "package-lock.json", "./"]

RUN npm install 

COPY . .
EXPOSE 5000


CMD [ "node", "server.js" ]