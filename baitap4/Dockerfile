FROM node:18-alpine

WORKDIR /app

#Cài đặt node module
COPY package*.json ./
RUN npm install

#Copy toàn bộ src code vào Image
COPY . .

EXPOSE 3000

CMD ["npm", "start"]
