FROM node:14

WORKDIR /app

COPY . .

RUN npm i express pg body-parser querystring

EXPOSE 80

CMD ["npm", "start"]