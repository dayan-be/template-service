.PHONY:all
all:  $(wildcard *.pb.go)

%.pb.go:%.proto
	protoc -I. --go_out=. --micro_out=. $(LOWER-SERVICE).proto