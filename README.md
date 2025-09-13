# fshare-chat

本项目是`universe_push`消息定义proto


## 安装protoBuf 2.5

```
./configure
make
sudo make install
sudo ldconfig   # 更新动态库缓存可选

protoc --version

```

## 编译说明

```shell
protoc --proto_path=. --java_out=. FSCMessage.proto
```