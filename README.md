# System design algorithms

Algorithm you should know for preparing system design interview. For example, Learn Geohash / S2 Geometry algorithm for "How to design Uber like system?"


#### How to contribute
算法及其资源应该:

1.可以回答系统设计问题。例如，构建完整的推文索引可以回答“如何实现 Twitter 搜索”或“如何在 Twitter 中实现 hashtag”。
2.免费阅读或观看。
3.文字会比视频更好。


#### 目录

- 布隆过滤器✅
- Geohash / S2 Geometry☑️
- 超级日志✅
- Leaky bucket / Token bucket✅
- 有损计数☑️
- 运营转型☑️
- 四叉树/Rtree☑️
- 射线投射☑️
- 反向索引✅
- 同步算法✅
- Trie算法✅

### 布隆过滤器
布隆过滤器是一种数据结构，旨在快速且高效地告诉您某个元素是否存在于集合中。

- [Build a Web Crawler](http://blog.gainlo.co/index.php/2016/06/29/build-web-crawler/)


### Geohash / S2 Geometry
Geohash 可用于 1) 约会应用程序在特定小区内寻找浪漫对象，并创建聊天应用程序。2) 查找附近位置，并识别一个区域内的名胜古迹、餐馆、商店和住宿场所。3) Geohasher 进行全球探险，结识新朋友并探索新地方。

- [Location-based search results with DynamoDB and Geohash](https://read.acloud.guru/location-based-search-results-with-dynamodb-and-geohash-267727e5d54f)

### 超级日志
HyperLogLog 是一种用于计数不同问题的算法，它近似于多重集中不同元素的数量。

- [Redis HyperLogLog Explained](https://www.youtube.com/watch?v=MunL8nnwscQ)

### Leaky bucket / Token bucket
一种控制发送到网络的流量的数量和速率的机制

- [Everything You Need To Know About API Rate Limiting](https://nordicapis.com/everything-you-need-to-know-about-api-rate-limiting/)
- [How to Design a Scalable Rate Limiting Algorithm](https://konghq.com/blog/how-to-design-a-scalable-rate-limiting-algorithm/)

### 有损计数
有损计数算法是一种用于识别数据流中频率计数超过用户给定阈值的元素的算法。

- [Fast and Reliable Ranking in Datastore](https://cloud.google.com/datastore/docs/articles/fast-and-reliable-ranking-in-datastore)
- [Frequency Counts over Data Streams](https://www.cse.ust.hk/vldb2002/VLDB2002-proceedings/slides/S10P03slides.pdf)
- [How we built rate limiting capable of scaling to millions of domains](https://blog.cloudflare.com/counting-things-a-lot-of-different-things/)
- [Rate-limiting strategies and techniques](https://cloud.google.com/solutions/rate-limiting-strategies-techniques)

### 运营转型
运营转型 (OT) 是一种支持高级协作软件系统中的一系列协作功能的技术。

- [How Google docs handle editing collisions](https://stackoverflow.com/a/36366174)
- [Collaborative editing](https://www3.ntu.edu.sg/home/czsun/projects/otfaq/#_Toc321146127)

### 四叉树/Rtree
- [Spatial Indexing with Quadtrees](https://medium.com/@waleoyediran/spatial-indexing-with-quadtrees-b998ae49336)
- Find nearby interest points

### 射线投射
光线投射是许多使用光线追踪几何算法的计算机图形渲染算法中最基本的一种。给定一个具有经度和纬度的点，返回该点的国家。

- [Ray Casting Algorithm](http://philliplemons.com/posts/ray-casting-algorithm)

### 反向索引
反向索引：反向索引是关键字的索引，它存储包含列表中的关键字的文档的记录。

- [How search engines work: Crawling, Indexing, And Ranking](https://moz.com/beginners-guide-to-seo/how-search-engines-operate)
- [Building a complete Tweet index](https://blog.twitter.com/engineering/en_us/a/2014/building-a-complete-tweet-index.html)

### 同步算法
rsync 算法是一种通过避免传输已经在目的地的块来降低文件传输成本的技术。

- [Streaming File Synchronization](https://dropbox.tech/infrastructure/streaming-file-synchronization)

### Trie算法
Trie 是一种高效的信息检索数据结构。使用 Trie，搜索复杂性可以达到最佳限制（密钥长度）

- [How to Design an Autocomplete System](https://dzone.com/articles/how-to-design-a-autocomplete-system)
- [Spell Checkers](https://stackoverflow.com/questions/21366631/how-do-i-use-a-trie-for-spell-checking)
- [prefix matching words (IP Addresses, Phone Numbers)](https://www.geeksforgeeks.org/longest-common-prefix-using-trie/)
- [Auto-complete feature using Trie](https://www.geeksforgeeks.org/auto-complete-feature-using-trie/)

