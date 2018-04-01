tianfuswp.com
===========

Fork from [https://github.com/studygolang/studygolang](studygolang)

# DEVELOP

要求 Go 1.8+

1、下载 gvt 依赖管理工具
	
	go get github.com/polaris1119/gvt
	
下载后将 gvt 加入 PATH 中。

2、下载安装依赖

cd 到源码目录	

	// unix
	./getpkg.sh
	// windows
	getpkg.bat

3、编译
	
	// unix
	./install.sh
	// windows
	install.bat

启动

	// unix
	./start.sh
	// windows
	start.bat

或者
	
	// unix
	bin/studygolang
	// windows
	bin\studygolang.exe

一切顺利的话，studygolang 应该就启动了。

## 步骤四

在浏览器中输入：http://127.0.0.1:8088

应该就能看到了。

接下来你会看到图形化安装界面，一步步照做吧。

* 如果之后有出现页面空白，请查看 error.log 是否有错误

## FAQ

Q: 提示找不到：config/env.ini 文件？  
A: 因为 studygolang 项目本身是一个完整的项目，而且目录结构采用了 GOPATH 要求的目录结构，同时，它的安装、运行不依赖系统配置的 GOPATH，因此，请务必不要将 studygolang 目录放入你系统的 `$GOPATH/src` 下面。如果你遇到这样的错误，请尝试将 studygolang 文件夹移到 src 目录之外，比如根目录下的某个目录。


# 使用该项目搭建的网站

- [Go语言中文网](https://studygolang.com)
- [Kotlin中国](https://kotlintc.com)
- [tianfuswp.com](https://tianfuswp.com)
