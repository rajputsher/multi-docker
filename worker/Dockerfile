FROM node:14.14.0-alpine
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY . .
#Only change between development and production is the line 7 "dev" --> "start"
CMD ["npm","run","start"] 