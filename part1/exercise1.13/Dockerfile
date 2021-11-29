FROM node:12

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .
ENV FRONT_URL=localhost:5050

EXPOSE 8000
CMD FRONT_URL=* npm start