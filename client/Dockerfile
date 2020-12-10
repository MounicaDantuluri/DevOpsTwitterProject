FROM node:10.19.0

# Create app directory
WORKDIR /usr/src/app
COPY package*.json ./


RUN npm install --g cross-env

RUN npm install

RUN npm i is-empty

# Bundle app source
COPY . .

EXPOSE 3000

CMD [ "npm", "start" ]