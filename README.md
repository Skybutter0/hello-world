Install issues
Linux Terminal:

station@station:~$ go env
GOARCH="amd64"
GOBIN=""
GOEXE=""
GOHOSTARCH="amd64"
GOHOSTOS="linux"
GOOS="linux"
GOPATH="/home/station/go"
GORACE=""
GOROOT="/usr/lib/go-1.6"
GOTOOLDIR="/usr/lib/go-1.6/pkg/tool/linux_amd64"
GO15VENDOREXPERIMENT="1"
CC="gcc"
GOGCCFLAGS="-fPIC -m64 -pthread -fmessage-length=0"
CXX="g++"
CGO_ENABLED="1"
station@station:~$ go get -u golang.org/x/tools/cmd/...
go install golang.org/x/tools/cmd/godoc: open /usr/lib/go-1.6/bin/godoc: permission denied
station@station:~$ 
