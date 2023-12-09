FROM node:18

WORKDIR /app

COPY . /app

RUN npm install

COPY . .

EXPOSE 3003

CMD ["node", "index.js"]
