FROM node:14.13.0-stretch

COPY package*.json ./

RUN npm install

COPY . /usr/src/app/

EXPOSE 8081

CMD [ "node", "/usr/src/app/start.js" ]