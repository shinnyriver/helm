#Dockerfile
FROM node:18-alpine AS build

WORKDIR /app

COPY package.json ./
RUN npm install

COPY . .

# 기본 Node.js 환경에서 실행
CMD ["npm", "start"]

EXPOSE 3000