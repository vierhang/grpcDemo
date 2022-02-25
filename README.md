# grpcDemo

## 一个简单的go  grpc demon

根目录运行，重新生成proto文件，如果没protoc 或者 proto-gen-go插件，自行下载
```
protoc --go_out=plugins=grpc:. ./proto/*.proto
```

run server 跟client 代码即可