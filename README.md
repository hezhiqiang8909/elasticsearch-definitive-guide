# Elasticsearch 权威指南

## 项目信息

### [在线阅读](http://learnes.net)

国外自动指向 [GITBOOK 项目](http://fuxiaopang.gitbooks.io/LearnElasticSearch) \| 国内用户自动指向 [阿里云](http://learnes.net)

### [GITHUB 仓库](https://github.com/GavinFoo/elasticsearch-definitive-guide)

## 译者前言

译者现在的工作项目中需要用到 Elasticsearch，但是在网络中找了很多的相关的内容都很不完善，中文的文档更是寥寥无几，所以我决定边研究边翻译一下官方推出的权威手册。在这里要先感谢原作者们！如果各位在这里发现了错误之处，请大家在 Issue 中提出或者 PR [这个项目](https://github.com/GavinFoo/elasticsearch-definitive-guide/)。

> #### 如果你喜欢这个翻译项目可以[点击Star一下](https://github.com/GavinFoo/elasticsearch-definitive-guide/)，您的支持是我们最大的动力。

原作名字：elasticsearch - the definitive guide

原作作者：clinton gormley，zachary tong

译者：Gavin Foo [fuxiaopang@gmail.com](mailto:fuxiaopang@gmail.com)

博客作者：联系请[点击](https://k8sadmin.info/lian-xi-zuo-zhe)，搬运不易，希望请作者喝咖啡，可以点击[联系博客作者](https://k8sadmin.info/lian-xi-zuo-zhe)

## 前言

这本书还在不断地添加内容中，我们会陆陆续续地在这里添加新的章节。这本书中的内容针对的是 Elasticsearch 的最新版本。

欢迎反馈 – 如果这里出现了错误，或者你有什么建议可以到我们 GitHub 项目中 [新建一个issue](https://github.com/GavinFoo/elasticsearch-definitive-guide/issues)。

这个世界已经被数据淹没。我们创造的系统所产生的数据可以瞬间轻而易举地将我们压垮，现有的科技一直致力于如何存储数据，并能将拥有大量信息的数据仓库结构化。而当你准备开始从大量的数据中得出结论做决策的时候，美好的一天就要被毁灭了……

Elasticsearch 是一个分布式可扩展的实时搜索和分析引擎。它能帮助你搜索、分析和浏览数据，而往往大家并没有在某个项目一开始就预料到需要这些功能。Elasticsearch 之所以出现就是为了重新赋予硬盘中看似无用的原始数据新的活力。

无论你是需要全文搜索、结构化数据的实时统计，还是两者的结合，这本指南都会帮助你了解其中最基本的概念，从最基本的操作开始学习 Elasticsearch。之后，我们还会逐渐开始探索更加复杂的搜索技术，你可以根据自身的学习的步伐。

Elasticsearch 并不是单纯的全文搜索这么简单。我们将向你介绍讲解结构化搜索、统计、查询过滤、地理定位、自动完成以及_你是不是要查找_的提示。我们还将探讨如何给数据建模能提升 Elasticsearch 的性能，以及在生产环境中如何配置、监视你的集群。

