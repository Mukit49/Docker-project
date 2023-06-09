FROM node:16.18.1

RUN npm install npm -g

WORKDIR /app/client
COPY ./package.json ./

RUN npm install --force
EXPOSE 3000

CMD ["npm", "start"]