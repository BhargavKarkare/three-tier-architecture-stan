FROM golang:1.17

WORKDIR /go/scr/app

COPY *.go .

RUN go mod init dispatch && go get
RUN go install
CMD [ "dispatch" ]