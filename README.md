# demo
阿里镜像

`go env -w GO111MODULE=on`

`go env -w GOPROXY=https://mirrors.aliyun.com/goproxy/,direct`

安装gin

`go get -u github.com/gin-gonic/gin`

安装grom

`go get github.com/jinzhu/gorm`

安装jwt包

`go get github.com/dgrijalva/jwt-go`

cmd下是可以默认进行base64的编码解码的。使用certutil命令即可。

编码

`certutil -f -encode "输入文件" "输出文件"`

解码

`certutil -f -decode "输入文件" "输出文件"`