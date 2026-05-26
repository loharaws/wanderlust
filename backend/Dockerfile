FROM node:21

WORKDIR /app

COPY . .

RUN npm install

RUN cp .env.sample .env

EXPOSE 5000

CMD ["npm", "start"]
