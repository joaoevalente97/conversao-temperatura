FROM node
WORKDIR /app
RUN apt-get update
COPY package*.json ./
RUN npm i
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
