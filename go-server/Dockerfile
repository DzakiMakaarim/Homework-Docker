FROM golang:stretch

WORKDIR /app

COPY . .

RUN go build -o app

EXPOSE 8082

CMD ./app