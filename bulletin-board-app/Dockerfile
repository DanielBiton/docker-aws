FROM node:16.20.0-bullseye-slim
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD ["npm","start"]