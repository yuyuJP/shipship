build:
	protoc -I. --go_out=plugins=micro:$(GOPATH)/src/github.com/yuyuJP/shipship/user-service proto/user/user.proto
	docker build -t consignment-service .