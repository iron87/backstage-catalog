FROM node:18

WORKDIR /usr/src/app

COPY package.json .

RUN npm install

RUN chown -R node /usr/src/app/node_modules

COPY . .

EXPOSE 4000

CMD = ["node","index.js"]