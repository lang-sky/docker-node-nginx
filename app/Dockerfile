FROM node:12.18.4
RUN mkdir /code
WORKDIR /code
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 5000
CMD ["node", "index.js"]
