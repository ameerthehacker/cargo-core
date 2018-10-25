FROM node:latest as base
WORKDIR /app
COPY src/package.json /app/src/package.json
WORKDIR /app/src
RUN npm install
ENTRYPOINT ["node", "./index.js"]