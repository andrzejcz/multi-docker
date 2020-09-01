FROM node:alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . . 
CMD ["npm", "run", "start"]  
#observe that above npm start script is the one defined in package.json file
# btw, similarly we had also defined in tha file npm dev script! 