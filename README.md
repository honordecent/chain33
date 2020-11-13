[![pipeline status](https://api.travis-ci.org/bityuan/bityuan.svg?branch=master)](https://travis-ci.org/bityuan/bityuan/)
[![Go Report Card](https://goreportcard.com/badge/github.com/bityuan/bityuan)](https://goreportcard.com/report/github.com/bityuan/bityuan)

# HDC公有链系统

#### 编译

```
git clone https://github.com/honordecent/honordecentchain.git $GOPATH/src/github.com/honordecent/honordecentchain
cd $GOPATH/src/github.com/honordecent/honordecentchain
go build -i -o bod
go build -i -o bod-cli github.com/honordecent/honordecentchain/cli
```

#### 运行

拷贝编译好的hdc, hdc-cli, hdc.toml这三个文件置于同一个文件夹下，执行：

```
./hdc -f hdc.toml
```
