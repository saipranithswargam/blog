FROM node:18.20.2-alpine 
#this above line without version was causing error while installing packages inside of container

WORKDIR /app

COPY ./package.json .

RUN npm install

COPY ./ ./

CMD ["npm", "start"]