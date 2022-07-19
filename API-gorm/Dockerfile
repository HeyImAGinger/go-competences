FROM golang:1.17

WORKDIR /go/src/API-gorm

COPY . .

RUN go get -d -v ./...
RUN go install -v ./...

CMD ["API-gorm"]
