# Specify a base image

FROM node:alpine

# Adding WORKDIR as the one where all commands will run into inside the container
WORKDIR /usr/app

# Adding the required package file
#COPY ./ ./

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command 
CMD ["npm","start"]


