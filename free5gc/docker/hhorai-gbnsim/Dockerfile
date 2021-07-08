FROM golang:1.12.9

WORKDIR /root/

RUN apt update -y && apt -y install git && go get -u -v github.com/hhorai/gnbsim/example

WORKDIR $GOPATH/src/github.com/hhorai/gnbsim/example

RUN go build