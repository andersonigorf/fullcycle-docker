# Estágio inicial para gerar imagem
FROM golang:alpine as builder

WORKDIR /go/src

COPY main.go .

RUN go build -ldflags '-w -s' main.go

# Segundo estágio para gerar imagem
FROM scratch

COPY --from=builder /go/src/main .

CMD [ "./main" ]
