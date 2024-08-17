FROM node:16-alpine
WORKDIR /opt/app
ADD . .
RUN npm install
RUN npm run build converter
CMD [ "node", './dist/apps/converter/main.js' ]
