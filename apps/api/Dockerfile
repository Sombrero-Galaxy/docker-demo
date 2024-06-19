FROM node:14.18.2-bullseye-slim
WORKDIR /opt/app
ADD . .
RUN npm install
RUN npm run build api
CMD [ "node", "./dist/apps/api/main.js" ]