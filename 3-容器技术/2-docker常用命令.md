# Docker常用命令

- 查看当前正在运行的 Docker 容器的进程号（PID）：

```
$ docker inspect --format '{{ .State.Pid }}'  4ddf4638572d
25686
```

