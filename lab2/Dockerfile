FROM node:12
WORKDIR /usr/src/2048

COPY package*.json ./
RUN npm install

COPY . .

CMD [ "node", "server.js" ]