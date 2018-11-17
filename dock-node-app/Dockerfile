# specify a base image
FROM alpine

# install dependencies for node app
RUN apt-get install node
RUN npm install

# Default command to run on startup
CMD ["npm","start"]