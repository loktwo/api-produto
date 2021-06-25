FROM node:14.16.1-alpine3.13
WORKDIR /app
COPY src/package.json ./
COPY src/package-lock.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node","app.js"]
