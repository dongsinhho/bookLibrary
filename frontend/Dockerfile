FROM node:13-slim as builder

WORKDIR /usr/src/app/frontend

COPY package*.json /usr/src/app/frontend/

RUN npm install 

COPY . /usr/src/app/frontend/

RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]
