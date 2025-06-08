# Flink & Paimon docker

## Flink

[Flink SQL Client with Session Cluster](https://nightlies.apache.org/flink/flink-docs-release-2.0/docs/deployment/resource-providers/standalone/docker/#flink-sql-client-with-session-cluster)

## [Paimon](https://paimon.apache.org/docs/master/flink/quick-start/)

## 数据集

[天池数据集](https://tianchi.aliyun.com/dataset/140281)

Tianchi_2014001_Rec_Tmall_Product
> 天猫商品属性

* Item_id: 区间[1, 8133507],想通商品会有多条记录
* Title: 包含多个关键词的字符串, 由空格分隔
* Pict_url： 一个链接到对应在线图片URL
* Category: 格式"x-y", x为父项, y为子项
* Brand_id: 商品品牌, "b89366"
* Seller_id: 销售该商品的买家, "s86799"

Tianchi_2014002_Rec_Tmall_Log
> 用户浏览天猫的行为, 用户与商品交互记录

* Item_id: 区间[1, 8133507]
* User_id: 用户id, 如:u9774184
* Action: 行为类型, "click", "collect", "cart", "alipay"
* Vtime: 行为时间戳, yyyy-mm-dd hh:mm:ss

Tianchi_2014003_Rec_Tmall_Review
>

* Item_id: 区间[1, 8133507]
* User_id: u9774184
* feedback: 包含多个关键词的字符串, 由空格分隔
