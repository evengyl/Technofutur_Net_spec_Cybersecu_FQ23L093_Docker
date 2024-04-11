FROM node:slim

WORKDIR /api/v1

# COPY ./.env .
# COPY ./index.js .
# COPY ./package.json .
# COPY ./package-lock.json .
# COPY ./Dockerfile .

COPY . .

RUN npm install

EXPOSE 3000


CMD ["node", "index.js"]

#docker build --pull --rm -f "Dockerfile" -t fq23l093_api_without_sql:latest "."
