FROM node:18.20.8-alpine3.21

# Create app directory
WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD [ "npm", "start" ]