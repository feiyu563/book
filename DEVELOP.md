# 如何进行【PrometheusAlert】二次开发

### PrometheusAlert开发环境配置

推荐环境

1\) go version &gt; go 1.11 [golang下载](https://golang.org/dl/) 2\) 包管理工具 go mod\(go 1.11默认包含\) 3\) 推荐同时安装git

Clone项目代码

* 执行

```text
git clone https://github.com/feiyu563/PrometheusAlert.git
```

* 编译

```text
#Windows系统直接在项目目录下双击执行
build.bat

#Linux系统直接在项目目录下执行
sh build.sh

编译后默认在项目目录下生成二进制可执行文件（Windows下 .exe 结尾文件），直接执行即可
```

最后在浏览器打开 [http://127.0.0.1:8080](http://127.0.0.1:8080) 即可查看效果

