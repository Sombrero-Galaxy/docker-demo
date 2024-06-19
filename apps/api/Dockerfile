FROM node:16-bullseye-slim
WORKDIR /opt/app
ADD . .
RUN npm install
RUN npm run build api
CMD [ "node", "./dist/apps/api/main.js" ]