# Go example projects

This repository contains a collection of Go programs and libraries that
demonstrate the language, standard libraries, and tools.

## The examples

### [hello](hello/) ([godoc](//godoc.org/github.com/golang/example/hello)) and [stringutil](stringutil/) ([godoc](//godoc.org/github.com/golang/example/stringutil))

    go get github.com/golang/example/hello

A trivial "Hello, world" program that uses a stringutil package.

Command [hello](hello/) covers:

* The basic form of an executable command
* Importing packages (from the standard library and the local repository)
* Printing strings ([fmt](//golang.org/pkg/fmt/))

Library [stringutil](stringutil/) covers:

* The basic form of a library
* Conversion between string and []rune
* Table-driven unit tests ([testing](//golang.org/pkg/testing/))

### [outyet](outyet/) ([godoc](//godoc.org/github.com/golang/example/outyet))

    go get github.com/golang/example/outyet

A web server that answers the question: "Is Go 1.x out yet?"

Topics covered:

* Command-line flags ([flag](//golang.org/pkg/flag/))
* Web servers ([net/http](//golang.org/pkg/net/http/))
* HTML Templates ([html/template](//golang.org/pkg/html/template/))
* Logging ([log](//golang.org/pkg/log/))
* Long-running background processes
* Synchronizing data access between goroutines ([sync](//golang.org/pkg/sync/))
* Exporting server state for monitoring ([expvar](//golang.org/pkg/expvar/))
* Unit and integration tests ([testing](//golang.org/pkg/testing/))
* Dependency injection
* Time ([time](//golang.org/pkg/time/))

### [appengine-hello](appengine-hello/) ([godoc](//godoc.org/github.com/golang/example/appengine-hello))

	goapp get github.com/golang/example/appengine-hello

A trivial "Hello, world" App Engine application intended to be used as the
starting point for your own code.

_Note_: The `goapp` tool is part of the [Google App Engine SDK for Go](https://cloud.google.com/appengine/downloads#Google_App_Engine_SDK_for_Go).

### [gotypes](gotypes/) ([godoc](//godoc.org/github.com/golang/example/gotypes))

The `go/types` package is a type-checker for Go programs. It is one of the most
complex packages in Go's standard library, so we have provided this tutorial to
help you find your bearings. It comes with several example programs that you
can obtain using `go get` and play with as you learn to build tools that analyze
or manipulate Go programs.

### [template](template/) ([godoc](//godoc.org/github.com/golang/example/template))

A trivial web server that demonstrates the use of the
[`template` package](https://golang.org/pkg/text/template/)'s `block` feature.
去示例项目
此存储库包含一组Go程序和库，用于演示语言，标准库和工具。

例子
你好（godoc）和stringutil（godoc）
go get github.com/golang/example/hello
一个简单的“Hello，world”程序，它使用了一个stringutil包。

命令问候：

可执行命令的基本形式
导入包（从标准库和本地存储库）
打印字符串（fmt）
库stringutil涵盖：

图书馆的基本形式
字符串和[]符文之间的转换
表驱动单元测试（测试）
outyet（godoc）
go get github.com/golang/example/outyet
一个回答问题的网络服务器：“Go 1.x out了吗？”

涵盖的主题：

命令行标志（标志）
Web服务器（net / http）
HTML模板（html /模板）
记录（日志）
长时间运行的后台进程
同步goroutines之间的数据访问（同步）
导出服务器状态以进行监视（expvar）
单元和集成测试（测试）
依赖注入
时间（时间）
appengine-hello（godoc）
goapp get github.com/golang/example/appengine-hello
一个简单的“Hello，world”App Engine应用程序，旨在用作您自己代码的起点。

注意：该goapp工具是Google App Engine SDK for Go的一部分。

gotypes（godoc）
该go/types程序包是Go程序的类型检查程序。它是Go标准库中最复杂的软件包之一，因此我们提供了本教程来帮助您找到方向。它提供了几个示例程序，您可以go get在学习构建分析或操作Go程序的工具时使用和使用它们。

模板（godoc）
一个简单的Web服务器，演示了 template包的block功能的使用。

![Image text](http://s1.51cto.com/images/20181023/1540259246244208.png?x-oss-process=image/watermark,size_16,text_QDUxQ1RP5Y2a5a6i,color_FFFFFF,t_100,g_se,x_10,y_10,shadow_90,type_ZmFuZ3poZW5naGVpdGk=)
