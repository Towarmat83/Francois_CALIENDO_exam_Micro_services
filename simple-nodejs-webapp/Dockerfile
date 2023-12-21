FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY src/ ./src/

EXPOSE 8080

ENV APPLICATION_INSTANCE="example"

CMD ["node", "./src/count-server.js"]
