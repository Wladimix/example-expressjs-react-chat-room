FROM node:20.13.1

RUN mkdir -p app
WORKDIR app

COPY . .

RUN npm install

CMD ["npm", "start"]
