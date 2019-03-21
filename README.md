

```
git clone git@github.com:stormasm/grpc-examples.git
cd currency
go get

you will get an error message denoting that there are too
many programs in this package with main...
but you can IGNORE this warning, everything still works.
```

Every time you must do this in a new folder...

```
alias grpc1 go get -u google.golang.org/grpc
alias grpc2 go get -u github.com/golang/protobuf/protoc-gen-go
```

The proto files are already compiled but in case
you want to compile them again...

To compile the proto file run this command.

```
protoc --go_out=. *.proto
```
