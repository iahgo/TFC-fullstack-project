FROM node:16.14-alpine

WORKDIR /app-frontend

# ADD node_modules .

COPY package.json .
COPY . .
RUN npm install


EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]