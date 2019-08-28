# Specify the base image
FROM node:alpine

WORKDIR /app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Tell the image what to do
# as a container
CMD ["npm", "start"]
