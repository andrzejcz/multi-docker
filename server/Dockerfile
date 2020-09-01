FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . . 
CMD ["npm", "run", "start"]
#tart script is defined in package.json