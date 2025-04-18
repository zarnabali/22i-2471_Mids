FROM node:18
WORKDIR /customer-services
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 3005
CMD ["node", "index.js"]