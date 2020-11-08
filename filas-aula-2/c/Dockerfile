FROM golang:1.15

WORKDIR /go/src/fullcycle

COPY . .

RUN GOS=linux go build

EXPOSE 9092

ENTRYPOINT ["./fullcycle"]
