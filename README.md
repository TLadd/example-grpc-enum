# example-grpc-enum

## Generate files

```
./node_modules/.bin/grpc_tools_node_protoc --js_out=import_style=commonjs,binary:./ --grpc_out=./ --plugin=protoc-gen-grpc=./node_modules/.bin/grpc_tools_node_protoc_plugin helloworld.proto

protoc --plugin=protoc-gen-ts=./node_modules/.bin/protoc-gen-ts --ts_out=./ helloworld.proto
```
