FROM node:14

WORKDIR /metrics_plotter

COPY package.json .

RUN npm install

COPY . .

CMD [ "npm", "start" ]