FROM node:18

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

COPY .env.sample .env.local

EXPOSE 5173

CMD ["npm", "run", "dev"]
