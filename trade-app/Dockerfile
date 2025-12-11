FROM node:22.20.0-alpine
WORKDIR /trade-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start