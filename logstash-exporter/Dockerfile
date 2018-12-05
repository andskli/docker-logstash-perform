FROM golang:1.9
RUN go get -u github.com/BonnierNews/logstash_exporter \
 && cd $GOPATH/src/github.com/BonnierNews/logstash_exporter \
 && make

ENTRYPOINT [ "/go/src/github.com/BonnierNews/logstash_exporter/logstash_exporter" ]