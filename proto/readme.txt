

to use ts-proto GITHUB : https://github.com/stephenh/ts-proto
1 download protoc for windows 

2 run command = protoc --plugin=protoc-gen-t./proto/auth.protos_proto=".\\node_modules\\.bin\\protoc-gen-ts_proto.cmd" --ts_proto_out=. 
--ts_proto_opt=nestJs=true ./proto/auth.proto