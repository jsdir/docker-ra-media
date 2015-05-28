FROM jsdir/ra-media:0.1.0

RUN apk add --update curl git mercurial bzr go postgresql-client && rm -rf /var/cache/apk/*

ENV GOROOT /usr/lib/go
ENV GOPATH /gopath
ENV GOBIN /gopath/bin
ENV PATH $PATH:$GOROOT/bin:$GOPATH/bin

