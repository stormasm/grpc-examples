
Every time you must do this in a new folder...

```
go get -u google.golang.org/grpc
go get -u github.com/golang/protobuf/protoc-gen-go
```

To compile the proto file run this command.

```
protoc --go_out=. *.proto
```
