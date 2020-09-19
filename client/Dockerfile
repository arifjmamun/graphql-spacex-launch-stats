FROM node:12.18.3-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install --quiet

COPY . .

EXPOSE 3000

CMD ["npm", "run", "start"]

