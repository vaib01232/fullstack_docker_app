FROM node:14-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY app/public ./public
COPY src ./src

EXPOSE 3000

CMD ["npm", "start"]