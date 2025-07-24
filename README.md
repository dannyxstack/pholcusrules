## Crawl website by Pholcus

[Pholcus](https://github.com/andeya/pholcus) is a distributed high-concurrency crawler software written in pure Go language, which is only used for programming learning and research.

It supports three operation modes: stand-alone, server-side, and client-side, and has three operation interfaces: Web, GUI, and command line; the rules are simple and flexible, batch tasks are concurrent, and the output methods are rich (mysql/mongodb/kafka/csv/excel, etc.); in addition, it also supports two crawling modes: horizontal and vertical, and supports a series of advanced functions such as simulated login and task suspension and cancellation.

This project uses Pholcus to design some crawling rules for mainstream web pages. It supports exporting data to csv, or to other data storage systems such as mysql.

Websites include duanwenxue,kuaidaili,wx100000p,hejin-vote,etc.

## env
- OS: Windows(x64 recommended),Mac,Linux
- go version 1.8+
## build
```
go build app/example.go
```
## run
```
./example
```

## or use build and run, clean history
```
./build.sh
```

