FROM node:18-slim

RUN apt-get update && apt-get install python3 wget -y

USER node

WORKDIR /usr/src/app

# COPY . .

# RUN npm install

EXPOSE 3000
CMD [ "node", "index.js" ]