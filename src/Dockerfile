FROM node:18.16.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
# run container => docker container run -d -p 8080:8080 --name conversao-temperatura augustoribeirodev/conversao-temperatura:v1