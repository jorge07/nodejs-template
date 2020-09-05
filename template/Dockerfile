FROM node:12-alpine

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json /usr/src/app/

RUN npm install

# Copy app source
COPY . .

CMD [ "npm", "start" ]
