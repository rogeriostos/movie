FROM node:14-alpine
LABEL vendor=Rogerio\ dos\ Santos\ Silva \
    email=roger7331@gmail.com \
    version="v1.0" \
    release-date="2022-04-24"
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8181
ENTRYPOINT [ "node", "server.js" ]