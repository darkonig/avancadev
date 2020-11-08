FROM golang:1.15

WORKDIR /go/src/fullcycle

COPY . .

RUN GOS=linux go build -o fullcycle

EXPOSE 9091

ENTRYPOINT ["./fullcycle"]
