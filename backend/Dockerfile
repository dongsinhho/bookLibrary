FROM node:alpine

WORKDIR /usr/src/app/backend

COPY package*.json /usr/src/app/backend/

RUN npm install --only=production

COPY . /usr/src/app/backend/

EXPOSE 8080

CMD ["npm", "start"]
