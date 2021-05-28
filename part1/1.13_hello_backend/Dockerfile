FROM golang:1.15.0
ENV REQUEST_ORIGIN http://localhost:5000
EXPOSE 8080


WORKDIR /app

COPY . .

RUN go mod download

RUN go build

CMD ["./server"]
