FROM node:12.16.3
WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["node","index.js"]

