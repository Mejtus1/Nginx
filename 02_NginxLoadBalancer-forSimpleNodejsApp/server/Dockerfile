FROM node:16 

# Create app directory
WORKDIR /user/src/app

# Install app dependencies
COPY package*.json ./ 

RUN npm install 

# Bundle app source 
COPY . . 

EXPOSE 7777
CMD [ "npm", "run", "start"]