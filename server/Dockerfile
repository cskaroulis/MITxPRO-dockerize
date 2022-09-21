FROM node:16.17.0
WORKDIR /server
COPY package.json /server/package.json
RUN npm install
COPY . .
EXPOSE 8080
CMD ["npm", "start"]