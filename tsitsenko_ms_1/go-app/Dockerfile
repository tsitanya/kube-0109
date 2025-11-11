FROM golang:1.21-alpine3.18
WORKDIR /app
COPY . .
RUN go mod init go-app
RUN command go mod tidy
RUN go build -o main .
CMD ["./main"]