FROM node:14.20.0-alpine

## RUN mkdir app/

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm ci

COPY . .

ENTRYPOINT ["npm"]
CMD ["run", "prod"]