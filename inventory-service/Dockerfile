FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 5002

CMD ["sh", "-c", "sleep 20 && node app.js"]