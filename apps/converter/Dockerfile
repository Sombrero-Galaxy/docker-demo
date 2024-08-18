FROM node:16-alpine
WORKDIR /opt/app
ADD package*.json ./
RUN npm install
ADD . .
RUN npm run build converter
CMD [ "node", "./dist/apps/converter/main.js" ]
