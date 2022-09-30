FROM golang:1.18-alpine
WORKDIR /server
ENV GO111MODULE=on
ENV GOPROXY=https://goproxy.cn,direct
COPY ./goctl1.4.0 /go/bin/goctl
COPY ./modd0.8 /go/bin/modd
RUN goctl env check -i -f --verbose