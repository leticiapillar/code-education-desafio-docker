FROM golang:1.15.2-alpine3.12
COPY hello.go .
RUN go build hello.go
FROM scratch
COPY --from=0 /go/hello .
CMD ["./hello"]