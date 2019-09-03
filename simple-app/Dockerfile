#Specify a base image.
FROM node:alpine

WORKDIR /usr/app

#Install dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#Default command to run when a container starts up.
CMD [ "npm","start" ]