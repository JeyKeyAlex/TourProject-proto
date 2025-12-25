#./go-genproto
protoc -I proto proto/user/type.proto proto/user/user.proto --go_out=./go-genproto --go_opt=paths=source_relative --go-grpc_out=./go-genproto --go-grpc_opt=paths=source_relative
#../TestProject-genproto
protoc -I proto proto/user/type.proto proto/user/user.proto --go_out=../TestProject-genproto --go_opt=paths=source_relative --go-grpc_out=../TestProject-genproto --go-grpc_opt=paths=source_relative