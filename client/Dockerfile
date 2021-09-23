FROM node:16-alpine3.11

WORKDIR /app

ENV REACT_APP_GO_ENDPOINT=http://localhost:8080

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm","start"]