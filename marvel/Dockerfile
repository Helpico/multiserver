FROM node:18.4.0-bullseye

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY package*.json ./

RUN npm install
COPY . .
EXPOSE 8192
CMD [ "node", "index.js" ]
