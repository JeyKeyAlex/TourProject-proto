# TourProject-proto

protoc -I proto proto/user/type.proto proto/user/user.proto --go_out=./go-genproto --go_opt=paths=source_relative --go-grpc_out=./go-genproto --go-grpc_opt=paths=source_relative