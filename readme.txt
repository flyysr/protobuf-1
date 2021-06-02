//protoc --go_out=. *.proto 用这个会报错，装下面这个插件

go get github.com/gogo/protobuf/protoc-gen-gogo

protoc  *.proto --gogo_out=.

//运行
go run main.go aa.pb.go
//结果
//(base) root@go-learn:/data/2021-03/mm# go run main.go aa.pb.go
//Elliot
//24
//1400
//2500


//reference https://blog.csdn.net/JunChow520/article/details/115345622
