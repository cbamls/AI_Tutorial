
1. # 搜索 推荐 广告系统优质资源

   搜索系统和 推荐系统技术资料整理
   这篇文章意图是收集市面上质量不错的搜索 推荐 广告引擎技术资料，内容来源包括开源项目官网（Lucene、Solr、Elastic）、综合技术网站（AIQ 、infoQ、Stackoverflow、github 等）、专业技术网站（我爱自然语言处理等）、国内外知名互联网公司技术博客（阿里中间件团队博客、美团技术博客等）、知名技术牛人博客（Matrix67、刘超觉先等）等。
   以下整理的内容大致根据来源进行分类，等这篇整理得差不多了再开一篇博客根据知识点进行梳理。
   个人视角有限，还望各位同行补充、丰富，谢谢。

   * * *

   ## 开源相关

   ### Lucene

   *   [Lucene 官网](https://lucene.apache.org/)
   *   [Lucene 7.6.0源码](http://apache.01link.hk/lucene/java/7.6.0/)

   *   [Lucene Wiki](https://wiki.apache.org/lucene-java/FrontPage)

   *   [索引结构 -Lucene6.6.0](https://lucene.apache.org/core/6_6_0/core/org/apache/lucene/codecs/lucene62/package-summary.html#package.description)

       ### Solr

   *   [Solr 官网](http://lucene.apache.org/solr/)

   *   [Solr Wiki](https://wiki.apache.org/solr/)

       ### Elastic

   *   [Elastic 官网](https://www.elastic.co/cn/)

   *   [Elastic Blog](https://www.elastic.co/blog#sthash.khjrgPU5.dpbs)

   *   [Elastic Formus](https://discuss.elastic.co/)

   *   [Elasticsearch: 权威指南 - 中文版](https://www.elastic.co/guide/cn/elasticsearch/guide/current/index.html)

   *   [Elastic 中文社区](https://elasticsearch.cn/)

       ### LucidWorks

   *   [LucidWorks](https://lucidworks.com/)

   *   [LucidWorks Blog](https://lucidworks.com/blog/#blog/)

       ### 中文分词

   *   [ansj 分词](https://github.com/NLPchina/ansj_seg?)

   *   [HanLP 分词](https://github.com/hankcs/HanLP)

   *   [ES-Analysis-IK](https://github.com/medcl/elasticsearch-analysis-ik)

   ## 大公司

   ### 阿里

   *   [天猫推荐算法团队的那些事儿 - 20140401 - infoQ](https://www.infoq.cn/article/2014%2F04%2Ftmall-recommendation-team)
       _本文以访谈的方式呈现，对搜索和推荐算法进行了简单的比较，提到了 AB 测试和离线测试，主要对推荐算法团队的工作方式、工作考评、任务分配、招聘等进行了介绍。_

   *   [天猫 11.11：搜索引擎实时秒级更新 - 20141111 - infoQ](https://www.infoq.cn/article/2014%2F11%2Ftmall-1111-search-engine)
       _文章简单介绍了阿里搜索引擎架构，提到了以下内容：1）为提高数据实时性（库存、价格等），去掉应用层和业务层的缓存，重点提升引擎层的服务能力。2）排序链，根据业务场景定制排序链。3）sku 搜索，搜索结果和属性导航联动（标类产品）。_

   *   [阿里搜索离线技术团队负责人谈 Hadoop：阿里离线平台、YARN 和 iStream](https://www.infoq.cn/article/2014%2F09%2Fhadoop-alibaba-yarn)

   *   [基于 Apache Flink 的实时计算引擎 Blink 在阿里搜索中的应用 - 20170216 - infoQ](https://www.infoq.cn/article/real-time-computing-engine-blink-in-alibaba-search)

   *   [阿里开源深度学习框架 XDL，面向广告、推荐、搜索场景 - 20181128 - AIQ](http://www.6aiq.com/article/1543939628501)
   *   [阿里巴巴搜索引擎平台 Ha3 揭秘 - 201811 - AIQ](http://www.6aiq.com/article/1543672176467)

   **阿里搜索事业部技术团队**
   阿里集团搜索、推荐、图像技术的大本营，大数据时代的创新主场。

   *   [阿里搜索事业部技术团队](https://yq.aliyun.com/teams/23?spm=5176.100239.0.0.IlfIYv)

   *   [OpenSearch：轻松构建大数据搜索服务 - 20160222](https://yq.aliyun.com/articles/67156?spm=a2c4e.11163080.searchblog.9.56c42ec17lRdd2)

   *   [搜索双链路实时计算体系 @双 11 实战 - 20160111](https://yq.aliyun.com/articles/2699?spm=5176.100244.teamhomeleft.95.WweKDa)

   **阿里中间件团队博客**
   2012 年期间，阿里中间件博客记录了 20 多篇 Lucene、Solr 相关博文，主要记录了一些在项目开发过程中遇到的问题，以及部分源码解读。内容丰富、实用，但不是很系统。

   *   [阿里中间件团队博客](http://jm.taobao.org/)

   *   [Solr 调优参考 - 20120521](http://jm.taobao.org/2012/05/21/solr-tuning)

   *   [Solr Lucene 优劣势分析 - 20120626](http://jm.taobao.org/2012/06/26/solr-lucene-advantages-and-disadvantages)

   *   [SolrQuery 性能压测参考 - 20120731](http://jm.taobao.org/2012/07/31/solr-query-performance-test-reference)

   *   [NumericField NumericRangeQuery 原理分析 - 20120731](http://jm.taobao.org/2012/07/31/numeric-field-numeric-range-query)

   *   [Solr schema 编写指导 - 20120731](http://jm.taobao.org/2012/07/31/solr-schema-guide)

   *   [关于搜索挖掘所想 - 20120731](http://jm.taobao.org/2012/07/31/think-about-search/)

   *   [SolrQuery 挖掘 -- 单维度聚合分析 - 20120920](http://jm.taobao.org/2012/09/20/solrquery-mining)

   *   [我感受到的排序机制参考 - 20120920](http://jm.taobao.org/2012/09/20/sort-of-mechanism-reference)

   *   [垂直搜索新问题 - 20120920](http://jm.taobao.org/2012/09/20/vertical-search-new-question)

   *   [Solr 平台化搜索实战必知场景 - 20120921](http://jm.taobao.org/2012/09/21/solar-search)

   *   [Solr Schema 配置小细节大问题 - 20121015](http://jm.taobao.org/2012/10/15/solr-schema-configuration-problem/)

   *   [Solr DisjunctionMax 注解 - 20121015](http://jm.taobao.org/2012/10/15/solr-disjunctionmax/)

   *   [Sql Support within Solr- 类 Sql 的 solr 搜索实现 (1) - 20121015](http://jm.taobao.org/2012/10/15/sql-support-within-solr)

   *   [Sql Support within Solr- 类 Sql 的 solr 搜索实现 (2) - 20121015](http://jm.taobao.org/2012/10/15/solr-flux-source-code-sql-support-within-solr/)

   *   [关于 TrieField 的全面认识、理解、运用 - 20121015](http://jm.taobao.org/2012/10/15/learn-about-triefield)

   *   [Solr Facet 引发思考 on the road - 20121029](http://jm.taobao.org/2012/10/29/solr-facet-on-the-road/)

   *   [查询问题 ---queryparse 深入理解 - 20121029](http://jm.taobao.org/2012/10/29/deep-learn-queryparse)

   *   [TermRangeQuery 源码解析 - 20121106](http://jm.taobao.org/2012/11/06/termrangequery-source-code)

   *   [Solr 之缓存篇 - 20121106](http://jm.taobao.org/2012/11/06/solar-cache/)

   *   [搜索的测试话题 - 20121113](http://jm.taobao.org/2012/11/13/test-topic-about-search)

   *   [关于搜索夜话 ---- 作为阶段序列的告别 - 20121113](http://jm.taobao.org/2012/11/13/night-talk-about-search/)

   *   [solr 长文本搜索问题 - 20121210](http://jm.taobao.org/2012/12/10/solr-long-text-search-problem)

   *   [SolrCore2.9.1 源码分析备忘 - 20121210](http://jm.taobao.org/2012/12/10/solr-core-2-9-1-source-code-analyse)

   ### 百度

   *   [百度万亿量级数据库 Tera 架构应用、设计与实践全攻略 - 20170526 - infoQ](https://www.infoq.cn/article/2017%2F05%2Fdatabase-baidu-Tera)

   ### 京东

   *   [京东 618：揭秘大促销背后的个性化推荐 - 20150618 - infoQ](https://www.infoq.cn/article/2015%2F06%2Fjd-618-personalrecommendation)

   *   [京东 11.11：商品搜索系统架构设计 - 20151111 - infoQ](https://www.infoq.cn/article/jingdong-11-11-commodity-search-system-architecture-design?utm_source=6aiq.com)

   *   [京东 618：机器学习与商品数据挖掘和知识抽取 - 20170618 - infoQ](https://www.infoq.cn/article/2017%2F06%2Fjd-618-Machine-learning-commodit)

   ### 美团点评

   **美团点评技术团队博客**
   在国内互联网公司中，个人认为“美团点评技术团队博客”是最持之以恒的，而且非常干货。

   *   [美团点评技术团队](https://tech.meituan.com/)

   *   [美团 O2O 排序解决方案——线下篇 - 20151207](https://tech.meituan.com/rerank_solution_offline.html)
   *   [美团O2O排序解决方案——线上篇 - 2015-11-16 17:00](https://tech.meituan.com/meituan_search_rank.html)

   *   [美团点评旅游搜索召回策略的演进 - 20170616 - AIQ](http://www.6aiq.com/article/1522247441467)

   ### 携程

   *   [携程技术中心](https://cloud.tencent.com/developer/column/2048/tag-10149/page-8)

   ### 去哪儿

   *   [去哪儿网机票搜索系统的高并发架构设计 20170421 - AIQ](http://www.6aiq.com/article/1522670952812)


   ### 搜狗

   *   [搜狗搜索广告检索系统 - 弹性架构演进之路 - 20160111 - infoQ](https://mp.weixin.qq.com/s?__biz=MzI4MTY5NTk4Ng==&mid=2247489709&idx=1&sn=dd82cbae0f01a13fcef39ac2925c6406&chksm=eba41b30dcd3922697fcbdd22188d919803c40841609f4a1280355b251b68a4d786fddcc8fb6&scene=27#wechat_redirect)

   *   [深度学习在搜狗无线搜索广告中的应用 - 20160808 - infoQ](https://www.infoq.cn/article/2016%2F08%2Fsougou-deep-learing-wireless-sea)

   *   [以搜狗为例，谈语音输入如何影响你的生活 - 20161208 - infoQ](https://www.infoq.cn/article/2016%2F12%2Fsougou-Voice-input-life)
   ### 一号店

   *   [1 号店 11.11：分布式搜索引擎的架构实践 - 20151112 - infoQ](https://www.infoq.cn/article/yhd-11-11-distributed-search-engine-architecture)

   *   [1 号店 11.11：机器排序学习在电商搜索中的实战 - 20161111 - AIQ](http://www.6aiq.com/article/1522330692884)

   *   [机器学习在 1 号店商品匹配中的实践 - 20170506 - 携程技术中心](https://cloud.tencent.com/developer/article/1063204)

   ### 待分类

   **国内**

   *   [**当当** 11.11：促销系统与交易系统的重构实践 - 20151113 - infoQ](https://www.infoq.cn/article/dangdang-11-11-reconstruction-system-practise)

   *   [**苏宁易购** 11.11：商品详情系统架构设计 - 20151227 - infoQ](https://www.infoq.cn/article/suning-product-details-system-architecture-design?)

   *   [**达观数据** 点击模型：提升算法精度的利器 - 20160315 - infoQ](https://www.infoq.cn/article/tool-to-improve-the-accuracy-of-algorithm)

   *   [**达观数据** 一个可供参考的搜索引擎排序架构实践案例 - 20160830 - infoQ](https://www.infoq.cn/article/a-search-engine-scheduling-architecture-for-reference?)

   *   [**达观数据** "搜你所想" 之用户搜索意图识别 - 20170608 - AIQ](http://www.6aiq.com/article/1541861015217)

   *   [**链家网** 数据驱动在搜索优化与推荐策略中的实践 - 20170406 - infoQ](https://www.infoq.cn/article/practise-of-data-driven-search-and-optimize-in-lianjia?)

   *   [**深度学习在 Airbnb 大规模搜索排名上的实战经验 - 20181118 - AIQ](http://www.6aiq.com/article/1542878440663)

   *   [**51 信用卡的个性化推荐体系 - 2018 - AIQ](http://www.6aiq.com/article/1542815641630)

   *   [**苏宁 11.11：搜索引擎 Solr 在苏宁易购商品评价系统中的应用 - 20181105 - AIQ](http://www.6aiq.com/article/1542192071013)
   **国外**

   *   [**Twitter** 实时检索 6700 亿条推文，细谈 Twitter 搜索引擎的演进历程 - 20160330 - infoQ](http://www.6aiq.com/article/1544116316790)

   *   [**Yelp** 是如何用数据驱动搜索过滤器的？ - 20151209 - infoQ](https://www.infoq.cn/article/2015%2F12%2FYelp-Search-filter)

   ## 开发应用

   ### 理论基础

   *   [我爱自然语言处理](http://www.52nlp.cn/) 推荐

   *   [漫话中文自动分词和语义识别](http://www.matrix67.com/blog/archives/4212)

       ### 源码解读

   *   [刘超觉先](http://www.cnblogs.com/forfuture1978) 详细分析了 Lucene3.x 的源码，推荐。

   *   [Anatomy of an Elasticsearch Cluster: Part I](https://www.infoq.cn/article/analysis-of-elasticsearch-cluster-part01?utm_source=infoq&utm_campaign=user_page&utm_medium=link)

   *   [Anatomy of an Elasticsearch Cluster: Part II](https://www.infoq.cn/article/anatomy-of-an-elasticsearch-cluster-part02?utm_source=infoq&utm_campaign=user_page&utm_medium=link)

   *   [Anatomy of an Elasticsearch Cluster: Part III](https://www.infoq.cn/article/anatomy-of-an-elasticsearch-cluster-part03?utm_source=infoq)
     
   ### 常见问题

   *   [Stackoverflow - Lucene](https://stackoverflow.com/questions/tagged/lucene?sort=votes&pageSize=15&)

   *   [Stackoverflow - Solr](https://stackoverflow.com/questions/tagged/solr?sort=votes&pageSize=15)

   *   [Stackoverflow - Elastic](https://stackoverflow.com/questions/tagged/elasticsearch)

       ### 其他

   *   [对话 Kibana 之父：如果需要，你应该自己动手编写工具 - 20170111 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2017%2F01%2FRashid-buildYourOwnTool)

   *   [配置高性能 Elasticsearch 集群的 9 个小贴士 - 20170104 - infoQ](https://www.infoq.cn/article/2017%2F01%2FElasticSearch-9)

   *   [基于 ElasticStack 的数据探索与分析 - 20161018 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fdata-exploration-and-analysis-based-on-elasticstack)

   *   [使用 Akka、Kafka 和 ElasticSearch 等构建分析引擎 - 20160825 - infoQ](https://www.infoq.cn/article/use-akka-kafka--build-analysis-engine?)

   *   [万亿级日志与行为数据存储查询技术剖析 - 20170222 - infoQ](https://www.infoq.cn/article/trillion-log-and-data-storage-query-techniques)

   *   [谷歌的自然语言部门是啥样的？ - 20160118 - infoQ](https://www.infoq.cn/article/Inside-look-of-Google-NLU-Team)

   *   [通过 Baratine 将 Lucene 库暴露为微服务 - 20160225 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2FBuilding-a-Lucene-Microservice-with-Baratine)

   * * *

## 人工智能领域文集
   1. [我在亚马逊学到的三样东西，为我的机器学习职业之路做好了准备](http://www.6aiq.com/article/1569161146669)
   2. [关于数据驱动的重新思考](http://www.6aiq.com/article/1569161025335)
   3. [头条，美团，滴滴，京东及其它公司面试经验分享！](http://www.6aiq.com/article/1569160784677)
   4. [面试了 8 家公司，社招机器学习面试题](http://www.6aiq.com/article/1569136168444)
   5. [今日头条算法原理（全文）](http://www.6aiq.com/article/1569135774487)
   6. [人工智能入门书单推荐，学习 AI 的请收藏好（附 PDF 下载）](http://www.6aiq.com/article/1569135156126)
   7. [CCKS 2019 | 百度 CTO 王海峰详解知识图谱与语义理解](http://www.6aiq.com/article/1568827963634)
   8. [模型评估指标 AUC 和 ROC，这是我看到的最透彻的讲解](http://www.6aiq.com/article/1568827658600)
   9. [GitHub 标星 8k+，最后还有什么想问的么？对面试官的灵魂 50 问！](http://www.6aiq.com/article/1568826908246)
   10. [Andrew Ng(吴恩达) 关于机器学习职业生涯以及阅读论文的一些建议](http://www.6aiq.com/article/1568826255343)
   11. [A/B 测试中我们都会犯的十个常见错误](http://www.6aiq.com/article/1568825519774)
   12. [AI 在爱奇艺视频广告中的探索](http://www.6aiq.com/article/1568791882275)
   13. [快看漫画个性化推荐探索与实践](http://www.6aiq.com/article/1568618505543)
   14. [微博广告策略工程架构体系演进](http://www.6aiq.com/article/1568618069945)
   15. [构建可解释的推荐系统](http://www.6aiq.com/article/1568274177362)
   16. [解读：滴滴“猜你去哪儿”功能的算法实现](http://www.6aiq.com/article/1567577366676)
   17. [推荐系统走向下一阶段最重要的三个问题](http://www.6aiq.com/article/1567308516776)
   18. [电商推荐那点事](http://www.6aiq.com/article/1566564834140)
   19. [风控建模流程：以京东群体感知项目为例](http://www.6aiq.com/article/1566483295719)
   20. [每天超 50 亿推广流量、3 亿商品展现，阿里妈妈的推荐技术有多牛？](http://www.6aiq.com/article/1566482811205)
   21. [聊聊 Linux IO 栈](http://www.6aiq.com/article/1565968949200)
   22. [阿里妈妈深度树检索技术（TDM）及应用框架的探索实践](http://www.6aiq.com/article/1565927125584)
   23. [推荐系统工程难题：如何做好深度学习 CTR 模型线上 Serving](http://www.6aiq.com/article/1565792410807)
   24. [360 搜索的百亿级网页搜索引擎架构实现](http://www.6aiq.com/article/1565759838842)
   25. [京东电商推荐系统实践](http://www.6aiq.com/article/1565595267683)
   26. [< 机器学习实战  高清中英 源代码 > 分享](http://www.6aiq.com/article/1565595258174)
   27. [分布式锁用 Redis 还是 Zookeeper？](http://www.6aiq.com/article/1565538022304)
   28. [InnoDB 事务与分布式事务中一些关键问题](http://www.6aiq.com/article/1565459547589)
   29. [hello, 初次见面请多关注](http://www.6aiq.com/article/1565431795691)
   30. [【兼职】泽山贤教育招聘人工智能线上讲师，时薪 200-300 元](http://www.6aiq.com/article/1565193786066)
   31. [ESearch: 58 搜索内核设计与实践—实时索引篇](http://www.6aiq.com/article/1564639669705)
   32. [两万字深度介绍分布式系统原理，一文入魂](http://www.6aiq.com/article/1564639518329)
   33. [推荐技术随谈](http://www.6aiq.com/article/1564638926290)
   34. [这是我读过写得最好的【秒杀系统架构】分析与实战！](http://www.6aiq.com/article/1564638780024)
   35. [如果这篇文章说不清 epoll 的本质，那就过来掐死我吧！](http://www.6aiq.com/article/1564634702930)
   36. [最完整的 Markdown 基础教程](http://www.6aiq.com/article/1564465563620)
   37. [番外篇：Lucene 索引流程与倒排索引实现](http://www.6aiq.com/article/1564413366882)
   38. [Lucene 倒排索引原理探秘 (2)](http://www.6aiq.com/article/1564413209435)
   39. [Lucene 倒排索引原理探秘 (1)](http://www.6aiq.com/article/1564413040138)
   40. [推荐系统：石器与青铜时代](http://www.6aiq.com/article/1563816467004)
   41. [快手 HBase 在千亿级用户特征数据分析中的应用与实践](http://www.6aiq.com/article/1563816249571)
   42. [深度学习在 360 搜索广告 NLP 任务中的应用](http://www.6aiq.com/article/1563534203590)
   43. [消息中间件—RocketMQ 消息存储（二）](http://www.6aiq.com/article/1563130737288)
   44. [消息中间件—RocketMQ 消息存储（一）](http://www.6aiq.com/article/1563130479801)
   45. [消息中间件—RocketMQ 消息消费（三）（消息消费重试）](http://www.6aiq.com/article/1563130337444)
   46. [消息中间件—RocketMQ 消息消费（二）（push 模式实现）](http://www.6aiq.com/article/1563130068940)
   47. [消息中间件—RocketMQ 消息消费（一）](http://www.6aiq.com/article/1563129820252)
   48. [消息中间件—RocketMQ 消息发送](http://www.6aiq.com/article/1563129642050)
   49. [消息中间件—RocketMQ 的 RPC 通信（二）](http://www.6aiq.com/article/1563128435731)
   50. [消息中间件—RocketMQ 的 RPC 通信（一）](http://www.6aiq.com/article/1563128272857)
   51. [（毕业真实版本）《马来西亚双威大学毕业证书 -|SUNWAY 毕业一模一样证书](http://www.6aiq.com/article/1562961399162)
   52. [（毕业真实版本）《新加坡国立大学毕业证书 -|NUS 毕业一模一样证书](http://www.6aiq.com/article/1562959424675)
   53. [阿里零售通智能导购推荐技术实践](http://www.6aiq.com/article/1562902164382)
   54. [“看一看”推荐模型揭秘！微信团队提出实时 Look-alike 算法，解决推荐系统多样性问题](http://www.6aiq.com/article/1562902056730)
   55. [网易新闻推荐：深度学习排序系统及模型](http://www.6aiq.com/article/1562600299283)
   56. [一镜到底：FM 们的原理及在贝壳搜索的实践](http://www.6aiq.com/article/1562247779512)
   57. [淘宝从几百到千万级并发的十四次架构演进之路！](http://www.6aiq.com/article/1562226253738)
   58. [分布式追踪系统概述及主流开源系统对比](http://www.6aiq.com/article/1561708934642)
   59. [系统架构系列（四）：业务架构实战下篇](http://www.6aiq.com/article/1561569480601)
   60. [系统架构系列 (三)：业务架构实战上篇](http://www.6aiq.com/article/1561569370860)
   61. [系统架构系列 (二)：应对这一概念的方法](http://www.6aiq.com/article/1561569262030)
   62. [系统架构系列（一）：如何用公式定义该概念？](http://www.6aiq.com/article/1561568885381)
   63. [写给开发者的谷歌技术面试终极通关指南](http://www.6aiq.com/article/1561568669839)
   64. [流式数据处理在百度数据工厂的应用与实践](http://www.6aiq.com/article/1561568253928)
   65. [一文读懂深度学习：从神经元到 BERT](http://www.6aiq.com/article/1561568054539)
   66. [基于内容的推荐算法](http://www.6aiq.com/article/1561523060934)
   67. [Embedding 技术在民宿推荐中的应用](http://www.6aiq.com/article/1561522712795)
   68. [XLNet : 运行机制及和 Bert 的异同比较](http://www.6aiq.com/article/1561522178496)
   69. [深度学习在 Airbnb 中的探索与应用](http://www.6aiq.com/article/1561122418648)
   70. [【贝壳智搜】标签：月老手中那一根根红线](http://www.6aiq.com/article/1561122034940)
   71. [从 Word Embedding 到 Bert 模型—自然语言处理中的预训练技术发展史](http://www.6aiq.com/article/1560265487336)
   72. [Bert 时代的创新（应用篇）：Bert 在 NLP 各领域的应用进展](http://www.6aiq.com/article/1560264427921)
   73. [Netflix 推荐系统模型的快速线上评估方法——Interleaving](http://www.6aiq.com/article/1560264272602)
   74. [【真实生产案例】消息中间件如何处理消费失败的消息？](http://www.6aiq.com/article/1560187859658)
   75. [YC 中国创始人陆奇：人工智能时代，芯片和底层软件基本都要重做](http://www.6aiq.com/article/1560187579196)
   76. [从 MySQL 高可用架构看高可用架构设计](http://www.6aiq.com/article/1559928119531)
   77. [abtest- 数据分析 - 假设检验基础](http://www.6aiq.com/article/1559927769510)
   78. [程序员面试最常见问题 TOP 48](http://www.6aiq.com/article/1559927609226)
   79. [abtest 那些事儿（下）—数据跟踪和效果评估](http://www.6aiq.com/article/1559927485634)
   80. [list1 与 list2 求交集的方法总结！](http://www.6aiq.com/article/1559927141249)
   81. [当你打开天猫的那一刻，推荐系统做了哪些工作？](http://www.6aiq.com/article/1559926964517)
   82. [高并发架构消息队列面试题解析](http://www.6aiq.com/article/1559925040613)
   83. [Embedding 在深度推荐系统中的 3 大应用方向](http://www.6aiq.com/article/1559924680404)
   84. [使用 ElasticSearch 的 44 条建议](http://www.6aiq.com/article/1559924453879)
   85. [Elasticsearch 技术分析（七）： Elasticsearch 的性能优化](http://www.6aiq.com/article/1559923193369)
   86. [适合程序员用的笔记本电脑](http://www.6aiq.com/article/1559129392498)
   87. [怎样写网站优化方案](http://www.6aiq.com/article/1559128292478)
   88. [马蜂窝 ABTest 多层分流系统的设计与实现](http://www.6aiq.com/article/1558691486326)
   89. [ES 查询性能调优实践，亿级数据查询毫秒级返回](http://www.6aiq.com/article/1558615099584)
   90. [小米移动搜索中的 AI 技术](http://www.6aiq.com/article/1558597039005)
   91. [LSTM 原理与实践，原来如此简单](http://www.6aiq.com/article/1558505752984)
   92. [基于 “ 滴滴 KDD 2018 论文：基于强化学习技术的智能派单模型 ” 再演绎](http://www.6aiq.com/article/1558370681979)
   93. [阿里妈妈：电商预估模型的发展与挑战](http://www.6aiq.com/article/1558370392037)
   94. [Attention in RNN](http://www.6aiq.com/article/1558111401659)
   95. [详解 Transformer （Attention Is All You Need）](http://www.6aiq.com/article/1558111165025)
   96. [滴滴基于 ElasticSearch 的一站式搜索中台实践](http://www.6aiq.com/article/1558079050114)
   97. [快手万亿级别 Kafka 集群应用实践与技术演进之路](http://www.6aiq.com/article/1558077716919)
   98. [微软 AB/Testing EXP 实验管理平台](http://www.6aiq.com/article/1557945314515)
   99. [揭开 YouTube 深度推荐系统模型 Serving 之谜](http://www.6aiq.com/article/1557332349317)
   100. [深度学习中不得不学的 Graph Embedding 方法](http://www.6aiq.com/article/1557332223911)
   101. [谷歌、阿里、微软等 10 大深度学习 CTR 模型最全演化图谱【推荐、广告、搜索领域】](http://www.6aiq.com/article/1557332028652)
   102. [FTRL 公式推导](http://www.6aiq.com/article/1557331817840)
   103. [个性化推荐技术](http://www.6aiq.com/article/1556533994620)
   104. [分类模型与排序模型在推荐系统中的异同分析](http://www.6aiq.com/article/1556533853641)
   105. [阿里巴巴复杂搜索系统的可靠性优化之路](http://www.6aiq.com/article/1556111667859)
   106. [从 FFM 到 DeepFFM，推荐排序模型到底哪家强？](http://www.6aiq.com/article/1556111000226)
   107. [有赞百亿级日志系统架构设计](http://www.6aiq.com/article/1555946698273)
   108. [打造工业级推荐系统（一）：推荐算法工程师的成长之道](http://www.6aiq.com/article/1555946569416)
   109. [面试官：如果让你设计一个消息中间件，如何将其网络通信性能优化 10 倍以上？【石杉的架构笔记】](http://www.6aiq.com/article/1555913196005)
   110. [机器学习与深度学习常见面试题（上）](http://www.6aiq.com/article/1555912617666)
   111. [ABtest 和假设检验、流量分配](http://www.6aiq.com/article/1555861276270)
   112. [【三. 推荐系统的必备要素 -2】ABtest 框架](http://www.6aiq.com/article/1555859449280)
   113. [复旦邱锡鹏教授公布《神经网络与深度学习》，中文免费下载](http://www.6aiq.com/article/1555858942566)
   114. [携程金融大数据风控算法实践](http://www.6aiq.com/article/1555856447226)
   115. [拯救 996 的配方](http://www.6aiq.com/article/1555756448940)
   116. [【一. 概述 -2】什么样的产品推荐效果明显](http://www.6aiq.com/article/1555679531810)
   117. [【一. 概述 -1】推荐系统简介](http://www.6aiq.com/article/1555678886614)
   118. [万字长文解读电商搜索——如何让你买得又快又好](http://www.6aiq.com/article/1555670364831)
   119. [【搜狐】新闻推荐系统的 CTR 预估模型](http://www.6aiq.com/article/1555562786886)
   120. [阿里妈妈新突破：深度树匹配如何扛住千万级推荐系统压力](http://www.6aiq.com/article/1554659383706)
   121. [计算广告中主要模块、策略及其场景（上篇）](http://www.6aiq.com/article/1554656559591)
   122. [有赞订单搜索 AKF 架构演进之路](http://www.6aiq.com/article/1554655508983)
   123. [独家解读 | 滴滴机器学习平台架构演进之路](http://www.6aiq.com/article/1554481747379)
   124. [前深度学习时代 CTR 预估模型的演化之路](http://www.6aiq.com/article/1554304663821)
   125. [知其然，知其所以然：基于多任务学习的可解释推荐系统](http://www.6aiq.com/article/1554104797761)
   126. [[NAACL19] 一个更好更快更强的序列标注成分句法分析器](http://www.6aiq.com/article/1554104473231)
   127. [一直播千万量级用户推荐系统设计之路](http://www.6aiq.com/article/1553963227373)
   128. [知识图谱 |298 万条三元组生成方法 (一)](http://www.6aiq.com/article/1553935876676)
   129. [AI 下一个拐点，图神经网络带来哪些机遇？](http://www.6aiq.com/article/1553852664542)
   130. [强化学习系列二——应用 AlphaGo Zero 思路优化搜索排序](http://www.6aiq.com/article/1553609835324)
   131. [【58 同城】中文分词技术深度学习篇](http://www.6aiq.com/article/1553609269872)
   132. [一图胜千言: 解读阿里的 Deep Image CTR Model](http://www.6aiq.com/article/1553423324630)
   133. [推荐系统召回四模型之二：沉重的 FFM 模型](http://www.6aiq.com/article/1553423116865)
   134. [Embedding 从入门到专家必读的十篇论文](http://www.6aiq.com/article/1552999496449)
   135. [深度 CTR 预估模型中的特征自动组合机制演化简史](http://www.6aiq.com/article/1552975671851)
   136. [详解 Airbnb 之深度学习在搜索业务的探索](http://www.6aiq.com/article/1552975478018)
   137. [万字长文带你解读 NLP 深度学习的各类模型](http://www.6aiq.com/article/1552543604417)
   138. [基于深度强化学习的新闻推荐模型 DRN](http://www.6aiq.com/article/1552543182669)
   139. [基于 Tensorflow 高阶 API 构建大规模分布式深度学习模型系列: 开篇](http://www.6aiq.com/article/1552542944433)
   140. [【贝壳网】贝壳搜索平台实时流总体架构设计](http://www.6aiq.com/article/1552233110275)
   141. [【贝壳网】贝壳搜索为什么能知道你想住哪？](http://www.6aiq.com/article/1552232944397)
   142. [百度中文纠错技术](http://www.6aiq.com/article/1552219868606)
   143. [版本控制工具——Git 常用操作](http://www.6aiq.com/article/1552219465292)
   144. [【贝壳网】ElasticSearch 相关性计算原理及实践](http://www.6aiq.com/article/1552148885834)
   145. [【贝壳网】Elasticsearch 在贝壳搜索的部署实践](http://www.6aiq.com/article/1552148609719)
   146. [【贝壳网】读“懂”用户找房需求：贝壳语义解析技术实践](http://www.6aiq.com/article/1552148262585)
   147. [【贝壳网】两种简单有效的标签选择方法](http://www.6aiq.com/article/1552148186102)
   148. [回顾 Facebook 经典 CTR 预估模型](http://www.6aiq.com/article/1551876771974)
   149. [主流 CTR 预估模型的演化及对比](http://www.6aiq.com/article/1551874470361)
