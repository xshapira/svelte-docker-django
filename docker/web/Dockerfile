FROM node:14-alpine as base

WORKDIR /src
COPY ./frontend/package.json ./
EXPOSE 3000

ENV NODE_ENV=development
COPY ./frontend/build ./
RUN npm install -g nodemon && npm install


#CMD ["nodemon", "bin/www"]