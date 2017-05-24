thrift的demo项目

thrift_lib 是thrift的代码库，git地址:https://github.com/apache/thrift.git

golang中分别是golang版本的服务端和客户端，服务端和客户端之间是thrift来进行通信
server文件夹是golang版本的server
client文件夹是golang版本的client
gen-go文件夹是golang根基“thrift -r --gen go *.thrift”生成的接口文件


php中是php版本的客户端
Thrift是git库中的php-lib，使用时将其直接copy到项目中即可
gen-php 是通过“thrift -r --gen php *.thrift”生成的接口文件。
server.php是php版本的client

batu.thrift是server和client进行通信的idl文件，需要提前定义
