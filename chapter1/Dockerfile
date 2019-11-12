FROM golang:1.10.1-alpine3.7

EXPOSE 8080

COPY ./main.go ./

RUN go build -o ./go-app ./main.go

USER nobody

ENTRYPOINT ["./go-app"]
