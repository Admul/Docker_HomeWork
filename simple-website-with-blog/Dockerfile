FROM node:fermium-alpine3.15
LABEL maintainer="Admul (Artem Lepesa)"
WORKDIR /nodeserver
COPY . .
RUN npm install
RUN npm run compile
EXPOSE 3000

CMD [ "npm", "start" ]