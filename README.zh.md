## Pholcus 网站爬取

[Pholcus](https://github.com/andeya/pholcus) 是一款纯 Go 语言编写的分布式高并发爬虫软件，仅用于编程学习和研究。

它支持单机、服务器端和客户端三种运行模式，并拥有 Web、GUI 和命令行三种操作界面；规则简洁灵活，支持批量并发，输出方式丰富（mysql/mongodb/kafka/csv/excel 等）；此外，它还支持水平和垂直两种爬取模式，并支持模拟登录、任务暂停和取消等一系列高级功能。

本项目使用 Pholcus 设计了一些主流网页的爬取规则。它支持将数据导出到 csv 或 mysql 等其他数据存储系统。

支持的网站包括 duanwenxue、kuaidaili、wx100000p、hejin-vote 等。

## 环境
- 操作系统：Windows（推荐 64 位系统）、Mac、Linux
- go 版本 1.8+
## 构建
```
go build app/example.go
```
## 运行
```
./example
```

## 或者使用构建并运行，清除历史记录
```
./build.sh
```
