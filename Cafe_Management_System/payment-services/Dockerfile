FROM node:18
WORKDIR /payment-services
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 3005
CMD ["node", "index.js"]