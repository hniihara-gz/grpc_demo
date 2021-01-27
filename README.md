# grpc_demo
grpc_demo

```bash
#gRPCのインストール
$ go get -u google.golang.org/grpc

#Protocol Buffers v3のインストール
$ brew install protobuf

#Go用のprotocプラグインのインストール
$ go get -u github.com/golang/protobuf/protoc-gen-go

# 
protoc -I helloworld  --go_out=helloworld helloworld/helloworld.proto


```
