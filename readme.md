## 概述

STOMP 是一个简单（流式）面向文本的消息传输协议。

STOMP 提供了一种可互操作的连接格式，
这样 STOMP 客户端就可以与任何 STOMP 消息代理通信，
从而在多种语言、平台与代理之间提供简单而广泛的消息互操作性。

## 详述

源仓库 [stomp/stomp-spec](https://github.com/stomp/stomp-spec) 托管已发布的与正在进行的 STOMP 规范。
最新发布的规范位于：

<https://github.com/stomp/stomp-spec/src/stomp-specification-1.2.md>

## 网站生成

该 Git 存储库使用 [Maven](http://maven.apache.org/download.html)
或 [SBT](http://code.google.com/p/simple-build-tool/wiki/Setup)
构建工具生成
[STOMP 协议规范中文站](http://stomp.yueplus.ink/)

### 使用 Maven 构建

当安装好了 [Maven](http://maven.apache.org/download.html) ，
就可以通过运行以下指令生成网站：

    mvn package

将静态站点生成到 `target/sitegen` 目录，
只需使用 Web 浏览器访问 `target/sitegen/index.html`

### 使用 SBT 构建

当安装好了
[SBT](https://www.scala-sbt.org/1.x/docs/) ，
就可以通过运行以下指令生成网站：

    sbt update
    sbt package

将静态站点生成到 `target/scala_2.8.1/sitegen` 目录，
只需使用 Web 浏览器访问 `target/scala_2.8.1/sitegen/index.html`

