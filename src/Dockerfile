FROM node:18.11.0
WORKDIR /usr/app/
COPY package*.json ./
RUN npm i
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]