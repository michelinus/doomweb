FROM node:current-alpine

WORKDIR /app
COPY ["./package.json", "./package-lock.json*", "./public", "./"]
RUN npm install
EXPOSE 666
CMD [ "npm", "start" ]