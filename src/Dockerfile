FROM node:latest
WORKDIR /app
COPY package*.json /app/
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node","server.js"]