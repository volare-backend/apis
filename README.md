## README

コード生成
```shell
protoc --grpc-gateway_out=logtostderr=true:../pb --go_out=plugins=grpc:../pb *.proto  
 ```
