FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY src/ src/

CMD ["node", "src/app.js"]
