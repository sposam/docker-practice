# specify a base image
FROM alpine

# install dependencies for node app
RUN apk add --update nodejs
RUN apk add --update npm
COPY ./ ./
RUN npm install

# Default command to run on startup
CMD ["npm","start"]