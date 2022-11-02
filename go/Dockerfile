FROM golang:alpine AS builder

WORKDIR /usr/src/app

COPY . .

RUN go build -ldflags '-s -w' main.go

CMD ["./main"]
