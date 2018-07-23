# go-quant
一个简单的量化分析工具，聚焦在整合多种分析工具，并提供lua、js脚本支持。不提供交易实现，但留有交易接口可以自行实现交易逻辑。

# 技术实现
* 基于bingo 作为服务框架
* 集成otto 支持js脚本
* 集成goquery 支持简单的爬取内容解析

# roadmap
* 支持通用爬虫功能，实现简单的数据爬取
* 爬虫支持脚本来解析爬来的数据
* 支持数据导入：csv
* 实现常用的模型分析工具
* 支持自定义模型用于对数据进行分析
* 支持图表展现数据
* 支持策略开发，能输出策略结果
* 策略支持自定义脚本
