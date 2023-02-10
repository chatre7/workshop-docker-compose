FROM node:18-alpine

# Create app directory
RUN mkdir -p /nodejs
WORKDIR /nodejs

# Install app dependencies
COPY app.js /nodejs

EXPOSE 8000
CMD [ "node", "app.js" ]