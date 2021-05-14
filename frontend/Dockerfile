# Create image based on the official Node image from dockerhub
FROM node:lts-buster-slim

RUN mkdir /project
WORKDIR /project

COPY . .

RUN npm i
CMD ["npm", "start"]
