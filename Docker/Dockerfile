FROM golang:alpine as builder

WORKDIR /go/src/
COPY AppGo .
RUN CGO_ENABLED=0 go build -o /AppGo codeEducation.go

FROM scratch
COPY --from=builder /AppGo  /AppGo 

CMD ["/AppGo"]