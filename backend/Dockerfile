FROM node:14

WORKDIR /app

COPY package.json ./

RUN npm i -g nodemon ts-node typescript

RUN npm install

COPY . .

EXPOSE 3000

CMD npm start