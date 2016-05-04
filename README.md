# Go PATH Help
Cannot install Tools to continue set-up 
inputs, outputs of linux term: 

station@station:~/gowork/src/helloworld$ export GOPATH=$HOME/gowork
station@station:~/gowork/src/helloworld$ source ~/.profile
station@station:~/gowork/src/helloworld$ go env
GOARCH="amd64"
GOBIN=""
GOEXE=""
GOHOSTARCH="amd64"
GOHOSTOS="linux"
GOOS="linux"
GOPATH="/home/station/gowork"
GORACE=""
GOROOT="/usr/lib/go-1.6"
GOTOOLDIR="/usr/lib/go-1.6/pkg/tool/linux_amd64"
GO15VENDOREXPERIMENT="1"
CC="gcc"
GOGCCFLAGS="-fPIC -m64 -pthread -fmessage-length=0"
CXX="g++"
CGO_ENABLED="1"
station@station:~/gowork/src/helloworld$ sudo go get -u golang.org/x/tools/cmd/...
package golang.org/x/tools/cmd/...: cannot download, $GOPATH not set. For more details see: go help gopath
station@station:~/gowork/src/helloworld$ 

