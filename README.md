### prometheus
---
https://github.com/prometheus/prometheus

```
```

```
docker run --name prometheus -d -p 127.0.0.1:9090 prom/prometheus

go get github.com/prometheus/prometheus/cmd/...
prometheus --config.file=your_config.yml

mkdir -p $GOPATH/src/github.com/prometheus
cd $GOPATH/src/github.com/prometheus
git clone https://github.com/prometheus/prometheus.git
cd prometheus
make build
./prometheus --config.file=your_config.yml
```

```
```


