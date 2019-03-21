

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

In few words, **marshalling** refers to the process of converting the data or the objects into a byte-stream, and **unmarshalling** is the reverse process of converting the byte-stream back to their original data or object.

[Here is a nice simple example showing this](http://tleyden.github.io/blog/2014/12/02/getting-started-with-go-and-protocol-buffers/)
