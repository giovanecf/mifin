FROM node:18

EXPOSE 3000

WORKDIR /usr/app

COPY --chown=node:node package*.json ./

# Install app dependencies
RUN npm install

COPY --chown=node:node . .

CMD ["node","/usr/app/src/index.js"]