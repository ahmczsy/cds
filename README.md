<p align="left">
  <img width ="200px" src="https://github.com/tal-tech/cds/raw/master/doc/logo.png">
</p>

# ClickHouse Data Synchromesh
Data syncing in golang for ClickHouse.


based on [go-zero](https://github.com/tal-tech/go-zero) 

### ARCH

A typical data warehouse architecture

![avatar](https://github.com/tal-tech/cds/raw/master/doc/clickhouse_arch.png)

### design of data sync

Automatically synchronizing data from MySQL/MongoDB data source to ClickHouse cluster in real time.

![同步drawio](https://github.com/tal-tech/cds/raw/master/doc/%E5%90%8C%E6%AD%A5drawio.png)


### quick start

```bash
git clone https://github.com/tal-tech/cds.git
cd cds
make up
```

[demo by docker](doc/quickstart.md)

### data model in clickhouse
[CDS中ClickHouse使用的建表方案](doc/CDS中ClickHouse使用的建表方案.md)

## help

[提问的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way/blob/main/README-zh_CN.md)

[如何有效的报告bug](https://www.chiark.greenend.org.uk/~sgtatham/bugs-cn.html)

---

if you like this project and want to support it，please `star` 🤝

