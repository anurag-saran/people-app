FROM node:12-alpine

# RUN mkdir -p /home/node/app/node_modules && chown -R node:node /home/node/app

WORKDIR /

COPY package.json ./

# USER node

RUN npm install

# COPY --chown=node:node . .

COPY . /

EXPOSE 3000

CMD ["npm", "start"]