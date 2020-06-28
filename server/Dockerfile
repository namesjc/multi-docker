FROM node:14.4.0-alpine3.12

WORKDIR /app


COPY package*.json ./
RUN npm install --silent
COPY . .

CMD ["npm", "run", "start"]
