# searchAndRecommendEngine
搜索系统和 推荐系统技术资料整理
这篇博客意图是收集市面上质量不错的搜索引擎技术资料，内容来源包括开源项目官网（Lucene、Solr、Elastic）、综合技术网站（infoQ、Stackoverflow、github 等）、专业技术网站（我爱自然语言处理等）、国内外知名互联网公司技术博客（阿里中间件团队博客、美团技术博客等）、知名技术牛人博客（Matrix67、刘超觉先等）等。
以下整理的内容大致根据来源进行分类，等这篇整理得差不多了再开一篇博客根据知识点进行梳理。
个人视角有限，还望各位同行补充、丰富，谢谢。

* * *

## 开源相关

### Lucene

*   [Lucene 官网](https://hacpai.com/forward?goto=https%3A%2F%2Flucene.apache.org%2F)

*   [Lucene Wiki](https://hacpai.com/forward?goto=https%3A%2F%2Fwiki.apache.org%2Flucene-java%2FFrontPage)

*   [索引结构 -Lucene6.6.0](https://hacpai.com/forward?goto=https%3A%2F%2Flucene.apache.org%2Fcore%2F6_6_0%2Fcore%2Forg%2Fapache%2Flucene%2Fcodecs%2Flucene62%2Fpackage-summary.html%23package.description)

    ### Solr

*   [Solr 官网](https://hacpai.com/forward?goto=http%3A%2F%2Flucene.apache.org%2Fsolr%2F)

*   [Solr Wiki](https://hacpai.com/forward?goto=https%3A%2F%2Fwiki.apache.org%2Fsolr%2F)

    ### Elastic

*   [Elastic 官网](https://hacpai.com/forward?goto=https%3A%2F%2Fwww.elastic.co%2F)

*   [Elastic Blog](https://hacpai.com/forward?goto=https%3A%2F%2Fwww.elastic.co%2Fblog%23sthash.khjrgPU5.dpbs)

*   [Elastic Formus](https://hacpai.com/forward?goto=https%3A%2F%2Fdiscuss.elastic.co%2F)

*   [Elasticsearch: 权威指南 - 中文版](https://hacpai.com/forward?goto=https%3A%2F%2Fwww.elastic.co%2Fguide%2Fcn%2Felasticsearch%2Fguide%2Fcurrent%2Findex.html)

*   [Elastic 中文社区](https://hacpai.com/forward?goto=https%3A%2F%2Felasticsearch.cn%2F)

    ### LucidWorks

*   [LucidWorks](https://hacpai.com/forward?goto=https%3A%2F%2Flucidworks.com%2F)

*   [LucidWorks Blog](https://hacpai.com/forward?goto=https%3A%2F%2Flucidworks.com%2Fblog%2F%23blog%2F)

    ### 中文分词

*   [ansj 分词](https://hacpai.com/forward?goto=https%3A%2F%2Fgithub.com%2FNLPchina%2Fansj_seg)

*   [HanLP 分词](https://hacpai.com/forward?goto=https%3A%2F%2Fgithub.com%2Fhankcs%2FHanLP)

*   [ES-Analysis-IK](https://hacpai.com/forward?goto=https%3A%2F%2Fgithub.com%2Fmedcl%2Felasticsearch-analysis-ik)

## 大公司

### 阿里

*   [一淘 购物搜索引擎架构的变与不变（视频） - 20130127 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fshopping-search-engine-framework-variable)
    _音频质量不高，听起来比较费劲。_

*   [天猫推荐算法团队的那些事儿 - 20140401 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2014%2F04%2Ftmall-recommendation-team)
    _本文以访谈的方式呈现，对搜索和推荐算法进行了简单的比较，提到了 AB 测试和离线测试，主要对推荐算法团队的工作方式、工作考评、任务分配、招聘等进行了介绍。_

*   [天猫推荐算法实践（视频） - 20140622 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Ftianmao-recommendation-algorithm-practice)
    _简单介绍了天猫推荐业务、推荐系统架构，较为详细的分析了双 11 个性化会场案例，主要是针对品牌的个性化推荐，最后引出阿里巴巴大数据竞赛、天猫推荐算法大赛，题目是：开放 2011 年 4 月 -8 月用户对品牌的行为数据（点击、购买、收藏、加入购物车等），预测这些用户在 2011 年 9 月购买的品牌。_
    推荐：[天池大数据竞赛](https://hacpai.com/forward?goto=https%3A%2F%2Ftianchi.aliyun.com%2Fcompetition%2Findex.htm%3Fspm%3D5176.100065.111.2.EdzxZN%26id%3D) [天池数据集](https://hacpai.com/forward?goto=https%3A%2F%2Ftianchi.aliyun.com%2Fdatalab%2Findex.htm%3Fspm%3D5176.100066.1234.9.WioQNV)

*   [天猫 11.11：搜索引擎实时秒级更新 - 20141111 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2014%2F11%2Ftmall-1111-search-engine)
    _文章简单介绍了阿里搜索引擎架构，提到了以下内容：1）为提高数据实时性（库存、价格等），去掉应用层和业务层的缓存，重点提升引擎层的服务能力。2）排序链，根据业务场景定制排序链。3）sku 搜索，搜索结果和属性导航联动（标类产品）。_

*   [基于 Hadoop 生态技术构建阿里搜索离线系统（视频） - 20141205 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Falibaba-search-offline-system-based-on-hadoop)
    _主要介绍了：1）阿里搜索业务（1688、淘宝、天猫、一淘、openSearch）；2）搜索技术体系；3）搜索离线系统；4）实时计算方案；5）集群优化与管理；_

*   [开放搜索服务系统架构：从系统、平台到开放服务（视频） - 20150610 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fopen-search-service-system-architecture)
    _简单介绍了：1）搜索引擎的基础数据结构（倒排索引） 2）阿里搜索架构演变：单机架构；分布式架构（自动分发部署、集群资源复用）；平台化（系统插件化）；服务化（openSearch 自助式云搜索服务、多租户数据模型）。 讲解循序渐进，思路清晰，推荐。_

*   [B2B 搜索领域的算法挑战（视频） - 20150722 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fb2b-search-field-algorithm-challenges)

*   [阿里搜索实时计算和在线学习系统 PORA 介绍（视频） - 20160308 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Falibaba-search-real-time-computing-and-online-learning-system)

*   [基于 Apache Flink 的实时计算引擎 Blink 在阿里搜索中的应用 - 20170216 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Freal-time-computing-engine-blink-in-alibaba-search)

*   [LTR（Learning To Rank）在个性化电商搜索领域的应用（视频） - 20170419 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Flearning-to-rank-in-the-field-of-personalized-electric-business-search)

**阿里搜索事业部技术团队**
阿里集团搜索、推荐、图像技术的大本营，大数据时代的创新主场。

*   [阿里搜索事业部技术团队](https://hacpai.com/forward?goto=https%3A%2F%2Fyq.aliyun.com%2Fteams%2F23%3Fspm%3D5176.100239.0.0.IlfIYv)

*   [OpenSearch：轻松构建大数据搜索服务 - 20160222](https://hacpai.com/forward?goto=https%3A%2F%2Fyq.aliyun.com%2Farticles%2F4266%3Fspm%3D5176.100244.teamhomeleft.1.M2nbqK)

*   [搜索双链路实时计算体系 @双 11 实战 - 20160111](https://hacpai.com/forward?goto=https%3A%2F%2Fyq.aliyun.com%2Farticles%2F2699%3Fspm%3D5176.100244.teamhomeleft.95.WweKDa)

**阿里中间件团队博客**
2012 年期间，阿里中间件博客记录了 20 多篇 Lucene、Solr 相关博文，主要记录了一些在项目开发过程中遇到的问题，以及部分源码解读。内容丰富、实用，但不是很系统。

*   [阿里中间件团队博客](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F)

*   [Solr/Lucene 日志分析 - 查询热点词 - 脚本工具 - 20120501](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F05%2F01%2Fsolr-lucene-log-analysis-discover-hot-words%2F)

*   [Solr 调优参考 - 20120521](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F05%2F21%2Fsolr-tuning%2F)

*   [Solr Lucene 优劣势分析 - 20120626](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F06%2F26%2Fsolr-lucene-advantages-and-disadvantages%2F)

*   [SolrQuery 性能压测参考 - 20120731](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F07%2F31%2Fsolr-query-performance-test-reference%2F)

*   [NumericField NumericRangeQuery 原理分析 - 20120731](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F07%2F31%2Fnumeric-field-numeric-range-query%2F)

*   [Solr schema 编写指导 - 20120731](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F07%2F31%2Fsolr-schema-guide%2F)

*   [关于搜索挖掘所想 - 20120731](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F07%2F31%2Fthink-about-search%2F)

*   [SolrQuery 挖掘 -- 单维度聚合分析 - 20120920](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F09%2F20%2Fsolrquery-mining%2F)

*   [我感受到的排序机制参考 - 20120920](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F09%2F20%2Fsort-of-mechanism-reference%2F)

*   [垂直搜索新问题 - 20120920](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F09%2F20%2Fvertical-search-new-question%2F)

*   [Solr 平台化搜索实战必知场景 - 20120921](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F09%2F21%2Fsolar-search%2F)

*   [Solr Schema 配置小细节大问题 - 20121015](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F10%2F15%2Fsolr-schema-configuration-problem%2F)

*   [Solr DisjunctionMax 注解 - 20121015](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F10%2F15%2Fsolr-disjunctionmax%2F)

*   [Sql Support within Solr- 类 Sql 的 solr 搜索实现 (1) - 20121015](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F10%2F15%2Fsql-support-within-solr%2F)

*   [Sql Support within Solr- 类 Sql 的 solr 搜索实现 (2) - 20121015](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F10%2F15%2Fsolr-flux-source-code-sql-support-within-solr%2F)

*   [关于 TrieField 的全面认识、理解、运用 - 20121015](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F10%2F15%2Flearn-about-triefield%2F)

*   [Solr Facet 引发思考 on the road - 20121029](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F10%2F29%2Fsolr-facet-on-the-road%2F)

*   [查询问题 ---queryparse 深入理解 - 20121029](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F10%2F29%2Fdeep-learn-queryparse%2F)

*   [TermRangeQuery 源码解析 - 20121106](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F11%2F06%2Ftermrangequery-source-code%2F)

*   [Solr 之缓存篇 - 20121106](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F11%2F06%2Fsolar-cache%2F)

*   [搜索的测试话题 - 20121113](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F11%2F13%2Ftest-topic-about-search%2F)

*   [关于搜索夜话 ---- 作为阶段序列的告别 - 20121113](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F11%2F13%2Fnight-talk-about-search%2F)

*   [solr 长文本搜索问题 - 20121210](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F12%2F10%2Fsolr-long-text-search-problem%2F)

*   [SolrCore2.9.1 源码分析备忘 - 20121210](https://hacpai.com/forward?goto=http%3A%2F%2Fjm.taobao.org%2F2012%2F12%2F10%2Fsolr-core-2-9-1-source-code-analyse%2F)

### 腾讯

*   [腾讯社区搜索架构演进（视频） - 20121107 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Ftencent-community-search)

### 百度

*   [大型搜索引擎的系统测试方法及案例分享（视频） - 20120717 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Flarge-scale-search-engine-system-testing-methods-and-case-sharing)

*   [百度网页搜索，规模大幅膨胀下的架构优化实践（视频） - 20151214 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fbaidu-web-search-architecture-optimization-practice)

*   [Eden – 百度搜索系统的 PaaS 架构设计和实践（视频） - 20161104 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Feden-baidu-search-system-paas-architecture-design-and-practice)

*   [百度搜索开源基础架构系统解密（视频） - 20161208 - infoQ - 百度搜索基础架构团队](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fbaidu-search-open-source-infrastructure-system)

*   [百度万亿量级数据库 Tera 架构应用、设计与实践全攻略 - 20170526 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2017%2F05%2Fdatabase-baidu-Tera)

*   [Tera 在百亿级实时搜索架构中的应用（视频） - 20170601 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Ftera-in-the-ten-thousand-level-real-time-search-framework)

### 京东

*   [京东 618：揭秘大促销背后的个性化推荐 - 20150618 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2015%2F06%2Fjd-618-personalrecommendation)

*   [京东数据驱动下的个性化推荐（视频） - 20151008 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fpersonalized-recommendation-driven-by-jingdong-data)

*   [京东 11.11：商品搜索系统架构设计 - 20151111 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fjingdong-11-11-commodity-search-system-architecture-design)

*   [京东基于大数据技术的个性化电商搜索引擎（视频） - 20150209 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fjingdong-personalized-search-engine-based-on-big-data-technology)

*   [京东 618：机器学习与商品数据挖掘和知识抽取 - 20170618 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2017%2F06%2Fjd-618-Machine-learning-commodit)

### 美团点评

*   [外卖商家排序的算法演进（视频） - 20161008 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Falgorithm-evolution-of-takeaway-businesses-sort)

**美团点评技术团队博客**
在国内互联网公司中，个人认为“美团点评技术团队博客”是最持之以恒的，而且非常干货。

*   [美团点评技术团队](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2F)

*   [搜索引擎关键字智能提示的一种实现 - 20140217](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2Fpinyin-suggest.html)

*   [Solr Facet 技术的应用与研究 - 20140609](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2Fsolr-facet.html)

*   [Solr 空间搜索原理分析与实践 - 20140902](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2Fsolr-spatial-search.html)

*   [地理空间距离计算优化 - 20140905](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2Flucene-distance.html)

*   [基于机器学习方法的 POI 品类推荐算法 - 20141218](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2Fcategory-recommend-base-ml.html)

*   [美团 O2O 排序解决方案——线上篇 - 20151116](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2Fmeituan-search-rank.html)

*   [美团 O2O 排序解决方案——线下篇 - 20151207](https://hacpai.com/forward?goto=https%3A%2F%2Ftech.meituan.com%2Frerank_solution_offline.html)

*   [美团点评旅游搜索召回策略的演进 - 20170616](https://hacpai.com/forward?goto=http%3A%2F%2Ftech.meituan.com%2Ftravel-search-strategy.html)

### 携程

*   [携程技术中心](https://hacpai.com/forward?goto=http%3A%2F%2Ftechshow.ctrip.com%2Farchives%2Fcategory%2Fshare)

*   [携程用户数据采集与分析系统 - 20170518 - 携程技术中心](https://hacpai.com/forward?goto=http%3A%2F%2Ftechshow.ctrip.com%2Farchives%2F2120.html)

*   [携程 ELK 日志分析平台深耕之路 - 20160302 - 携程技术中心](https://hacpai.com/forward?goto=http%3A%2F%2Ftechshow.ctrip.com%2Farchives%2F1042.html)

*   [旅游行业垂直搜索的架构探索 - 20141212 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Farchitecture-exploration-travel-industry-vertical-search)

### 去哪儿

*   [构建实时垂直搜索网站经验分享（视频） - 20120113 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fllc-real-time-vertical-search-site)

*   [去哪儿网机票搜索系统的高并发架构设计 20170421 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fqunar-ticket-search-system)

*   [去哪儿酒店算法服务平台 - 20170506 - 携程技术中心](https://hacpai.com/forward?goto=http%3A%2F%2Ftechshow.ctrip.com%2Farchives%2F2046.html)

*   [去哪儿搜索引擎 QSearch 设计与实现（视频） - 20120711 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fqsearch)

### 搜狗

*   [计算广告技术之大数据下的短文本相关性计算（视频） - 20150713 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fshort-text-correlation-computation-of-big-data)

*   [搜狗搜索广告检索系统 - 弹性架构演进之路 - 20160111 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fsogou-search-advertising-retrieval-system)

*   [深度学习在搜狗无线搜索广告中的应用 - 20160808 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2016%2F08%2Fsougou-deep-learing-wireless-sea)

*   [以搜狗为例，谈语音输入如何影响你的生活 - 20161208 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2016%2F12%2Fsougou-Voice-input-life)

### 一号店

*   [1 号店 11.11：分布式搜索引擎的架构实践 - 20151112 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fyhd-11-11-distributed-search-engine-architecture)

*   [1 号店 11.11：机器排序学习在电商搜索中的实战 - 20161111 - infoQ](http://www.6aiq.com/article/1522330692884)

*   [机器学习在 1 号店商品匹配中的实践 - 20170506 - 携程技术中心](https://hacpai.com/forward?goto=http%3A%2F%2Ftechshow.ctrip.com%2Farchives%2F2049.html)

### 待分类

**国内**

*   [**当当** 11.11：促销系统与交易系统的重构实践 - 20151113 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fdangdang-11-11-reconstruction-system-practise)

*   [**苏宁易购** 11.11：商品详情系统架构设计 - 20151227 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fsuning-product-details-system-architecture-design)

*   [**饿了么** 推荐系统的从 0 到 1 - 20170123 - 携程技术中心](https://hacpai.com/forward?goto=http%3A%2F%2Ftechshow.ctrip.com%2Farchives%2F1767.html)

*   [**一点咨询** 如何深度融合搜索和推荐：兴趣引擎架构设计（视频） - 20170406 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fdesign-of-interest-engine-architecture)

*   [**易到用车** O2O 的实时搜索引擎（视频） - 20151019 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Freal-time-search-engine-of-o2o)

*   [**达观数据** 点击模型：提升算法精度的利器 - 20160315 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Ftool-to-improve-the-accuracy-of-algorithm)

*   [**达观数据** 一个可供参考的搜索引擎排序架构实践案例 - 20160830 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fa-search-engine-scheduling-architecture-for-reference)

*   [**达观数据** "搜你所想" 之用户搜索意图识别 - 20170608 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fuser-search-intention-recognition)

*   [**链家网** 数据驱动在搜索优化与推荐策略中的实践 - 20170406 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fpractise-of-data-driven-search-and-optimize-in-lianjia)

*   [**豌豆荚** 发布应用内搜索协议 - 20140401 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2014%2F03%2Fwandoujia-search-protocol)

*   [**豌豆荚** 工程师谈其新版应用搜索技术 - 20121206 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2012%2F12%2Fwandoujia-app-search)

*   [**蘑菇街** 电商算法演化：从爆款模型到个性化模型（视频） - 20160523 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Felectricity-business-algorithm-evolution-of-mogujie)

*   [**今日头条** 的个性化推荐 - 20150624 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Finterviews%2Finterview-with-dinghaifeng-talk-toutiao-personalized-recommendation)

*   [**艺龙** 基于实时价格计算的电商检索系统（视频） - 20160715 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Felectricity-supplier-retrieval-system-based-on-real-time-price-calculation)

**国外**

*   [**Twitter** 实时搜索引擎发展历程（视频） - 20160330 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Ftwitter-real-time-search-engine-development-process)

*   [**Twitter** 是怎么做搜索的 - 20160219 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Finterviews%2Finterview-with-wangtian-talk-twitter-search)

*   [**LinkedIn** 基于 Kafka 和 ElasticSearch 的实时日志分析系统 - 20170316 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Flinkedin-real-time-log-analysis-system-based-on-kafka-and-elasticsearch)

*   [**Yelp** 是如何用数据驱动搜索过滤器的？ - 20151209 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2015%2F12%2FYelp-Search-filter)

*   [**Instagram** 的热门趋势发现算法 - 20150707 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2015%2F07%2FInstagram-equality)

## 开发应用

### 理论基础

*   [我爱自然语言处理](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.52nlp.cn%2F) 推荐

*   [漫话中文自动分词和语义识别](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.matrix67.com%2Fblog%2Farchives%2F4212) 膜拜中文系大牛 Matrix67

    ### 源码解读

*   [刘超觉先](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.cnblogs.com%2Fforfuture1978%2F) 详细分析了 Lucene3.x 的源码，推荐。

*   [Anatomy of an Elasticsearch Cluster: Part I](https://hacpai.com/forward?goto=https%3A%2F%2Fblog.insightdatascience.com%2Fanatomy-of-an-elasticsearch-cluster-part-i-7ac9a13b05db) - [infoQ 翻译](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fanalysis-of-elasticsearch-cluster-part01%3Futm_source%3Dinfoq%26utm_campaign%3Duser_page%26utm_medium%3Dlink)

*   [Anatomy of an Elasticsearch Cluster: Part II](https://hacpai.com/forward?goto=https%3A%2F%2Fblog.insightdatascience.com%2Fanatomy-of-an-elasticsearch-cluster-part-ii-6db4e821b571) - [infoQ 翻译](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fanatomy-of-an-elasticsearch-cluster-part02%3Futm_source%3Dinfoq%26utm_campaign%3Duser_page%26utm_medium%3Dlink)

*   [Anatomy of an Elasticsearch Cluster: Part III](https://hacpai.com/forward?goto=https%3A%2F%2Fblog.insightdatascience.com%2Fanatomy-of-an-elasticsearch-cluster-part-iii-8bb6ac84488d) - [infoQ 翻译](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fanatomy-of-an-elasticsearch-cluster-part03%3Futm_source%3Dinfoq%26utm_campaign%3Duser_page%26utm_medium%3Dlink)

    ### 常见问题

*   [Stackoverflow - Lucene](https://hacpai.com/forward?goto=https%3A%2F%2Fstackoverflow.com%2Fquestions%2Ftagged%2Flucene%3Fsort%3Dvotes%26pageSize%3D15)

*   [Stackoverflow - Solr](https://hacpai.com/forward?goto=https%3A%2F%2Fstackoverflow.com%2Fquestions%2Ftagged%2Fsolr%3Fsort%3Dvotes%26pageSize%3D15)

*   [Stackoverflow - Elastic](https://hacpai.com/forward?goto=https%3A%2F%2Fstackoverflow.com%2Fquestions%2Ftagged%2Felasticsearch%3Fsort%3Dvotes%26pageSize%3D15)

    ### 其他

*   [对话 Kibana 之父：如果需要，你应该自己动手编写工具 - 20170111 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2017%2F01%2FRashid-buildYourOwnTool)

*   [配置高性能 Elasticsearch 集群的 9 个小贴士 - 20170104 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fnews%2F2017%2F01%2FElasticSearch-9)

*   [基于 ElasticStack 的数据探索与分析 - 20161018 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Fpresentations%2Fdata-exploration-and-analysis-based-on-elasticstack)

*   [使用 Akka、Kafka 和 ElasticSearch 等构建分析引擎 - 20160825 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Fuse-akka-kafka--build-analysis-engine)

*   [万亿级日志与行为数据存储查询技术剖析 - 20170222 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2Ftrillion-log-and-data-storage-query-techniques)

*   [谷歌的自然语言部门是啥样的？ - 20160118 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2FInside-look-of-Google-NLU-Team)

*   [通过 Baratine 将 Lucene 库暴露为微服务 - 20160225 - infoQ](https://hacpai.com/forward?goto=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2FBuilding-a-Lucene-Microservice-with-Baratine)

