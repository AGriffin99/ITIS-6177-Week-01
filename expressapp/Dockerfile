FROM node:12

WORKDIR /expressapp

COPY package*.json ./

RUN npm install 

COPY . .

ENV PORT=8080 

EXPOSE 8080

CMD [ "node", "index" ]