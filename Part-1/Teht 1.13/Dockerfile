FROM golang:1.16

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

RUN go build
RUN go test ./...

CMD ["./server"]


# Commands:
# docker build . -t backend
# docker run -p 8080:8080 backend
