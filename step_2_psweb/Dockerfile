# Test web-app to use with Pluralsight courses and Docker Deep Dive book
# Linux x64
FROM alpine

LABEL maintainer="nigelpoulton@hotmail.com"

# Install Node, curl and NPM
RUN apk add --update nodejs npm curl

# Copy app to /src
COPY . /src

# Working Directory
WORKDIR /src

# Install dependencies
RUN  npm install

# We declear this endpoint in app.js 
EXPOSE 8080

ENTRYPOINT ["node", "./app.js"]
