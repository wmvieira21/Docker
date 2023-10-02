FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

EXPOSE 80

ENV MONGO_USERNAME=will
ENV MONGO_SECRET=123

CMD [ "node", "app.js" ]