FROM caarlos0/alpine-go
WORKDIR /gopath/src/app
ADD . /gopath/src/app/
RUN go get -v app
ENTRYPOINT ["/gopath/bin/app"]
