# GitHub Analysis 2019
这是 GitHub 2019 统计无垠版相关数据集存储库。

## 数据集信息
在 52 天 21 小时内，爬虫一共爬取了与 2,024,705 个用户有关的 14,651,923 个公共存储库的基础信息。

## 数据结构
一条记录为一个存储库的基础信息，无重复。

```
|     id|       name|      owner|  forked|      star|   language|  created|    license|   update|
+-------+-----------+-----------+--------+----------+-----------+---------+-----------+---------+
| bigint| mediumtext| mediumtext| tinyint| mediumint| mediumtext| datetime| mediumtext| datetime|
```

## 数据下载
提供 SQL 文件及 CSV 文件，请根据需求自行选择。

## 数据分析
请参阅 [GitHub 2019 统计无垠版](https://flyhigher.top/develop/1564.html)。

## 免责声明
我会尽可能地提供准确信息，但我不对此数据集信息的准确性和即时性及带来的任何影响负责。

我不代表 GitHub 官方，本数据集仅供学习之用。