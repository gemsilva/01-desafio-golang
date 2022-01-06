FROM golang:1.15-alpine

WORKDIR /usr/src/app

COPY go.mod ./
COPY go.sum ./
COPY *.go ./

RUN go build -o main

CMD [ "/main" ]