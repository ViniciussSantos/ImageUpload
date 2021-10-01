FROM node:alpine
WORKDIR /app
COPY package.json yarn.* tsconfig.json ./
COPY ./src ./src
RUN yarn install --frozen-lockfile