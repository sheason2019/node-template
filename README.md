# 使用Docker cli构建Node项目

```
$ sudo docker run --entrypoint "/bin/sh" -v /home/sheason/workspace/template:/app  node:16-alpine /app/build.sh
```

使用上述命令即可执行构建命令。

```
$ sudo docker run --entrypoint "/bin/sh" -v /home/sheason/workspace/template:/app  node:16-alpine /app/start.sh
```