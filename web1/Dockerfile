FROM node:alpine
WORKDIR /usr/src/app
COPY package.json .
RUN npm install
COPY server.js .
CMD [ "node" , "server.js" ]
EXPOSE 5000