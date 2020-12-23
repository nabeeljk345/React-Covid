FROM ubuntu:18.04
# Install app dependencies
COPY package*.json ./
 
RUN npm install
 
# Bundle app source
COPY . .
 
EXPOSE 8080
CMD [ "node", "App.js" ]