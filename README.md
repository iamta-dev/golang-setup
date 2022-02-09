# golang-setup

```
https://go.dev/doc/install

https://go.dev/doc/gopath_code

$ vim .zshrc
export PATH=$PATH:$(go env GOPATH)/bin 
export GOPATH=$(go env GOPATH)
$ source .zshrc
$ echo $GOPATH

remove golang
$ which go
$ sudo rm -rvf /usr/local/go/
$ sudo rm /etc/paths.d/go
$ sudo rm $HOME/go
$ echo $PATH

GRPC
https://go-zero.dev/en/protoc-install.html

$ brew install protobuf
$ cd ~/go/bin && rm -rf proto*
$ go get -u github.com/golang/protobuf/{proto,protoc-gen-go} 


Use environment variables in go
$ go env

Use environment variables in Terminal on Mac
$ env

```
