# [《Go语言四十二章经》](https://github.com/ffhelicopter/Go42/blob/master/SUMMARY.md "《Go语言四十二章经》")

作者：ffhelicopter（李骁）  时间：2018-04-15


## 起因
一直想写点什么但懒得动笔或者是不知道写什么。而这次写《Go语言四十二章经》，纯粹是因为开发过程中碰到过的一些问题，踩到过的一些坑，感觉在Go语言学习使用过程中，有必要深刻理解这门语言的核心思维、清晰掌握语言的细节规范以及反复琢磨标准包代码设计模式，于是才有了这本书。

Go语言以语法简单、门槛低、上手快著称。但入门后很多人发现要写出地道的、遵循 Go语言思维的代码却是不易。

在刚开始学习中，我带着比较强的面向对象编程思维惯性来写代码。但后来发现，带着面向对象的思路来写Go 语言代码会很难继续写下去，或者说看了系统源代码或其他知名开源包源代码后，围绕着Struct和Interface来写代码会更高效，代码更美观。虽然有人认为，Go语言的Strcut 和 Interface 一起，配合方法，也可以理解为面向对象，这点我姑且认可，但开发中不要过意考虑这些。因为在Go 语言中，Interface接口的使用将更为灵活，刻意追求面向对象，会导致你很难理解接口在Go 语言中的妙处。

作为Go语言的爱好者，在阅读系统源代码或其他知名开源包源代码时，发现大牛对这门语言的了解之深入，代码实现之巧妙优美，所以我建议你有时间多多阅读这些代码。网上有说Go大神的标准是“能理解简洁和可组合性哲学”，的确Go语言追求代码简洁到极致，而组合思想可谓借助于struct和interface两者而成为Go的灵魂。

Function，Method，Interface，Type等名词是程序员们接触比较多的关键字，但在Go语言中，你会发现，其有了更强大，更灵活的用法。当你彻底理解了Go语言相关基本概念，以及对其特点有深入的认知，当然这也这本书的目的，再假以时日多练习和实践，我相信你应该很快就能彻底掌握这门语言，成为一名出色的Gopher。

这本书适合Go语言新手来细细阅读，对于有一定经验的开发人员，也可以根据自己的情况，选择一些章节来看。

第一章到第二十六章主要讲Go语言的基础知识，其中第十七章的type，第十八章的struct，第十九章的interface，以及第二十章的方法，都是Go语言中非常非常重要的部分。

而第二十一章的协程，第二十二章的通道以及第二十三章的同步与锁，这三章在并发处理中我们通常都需要用到，需要弄清楚他们的概念和彼此间联系。

从第二十七章开始，到第三十八章，讲述了Go标准包中比较重要的几个包，可以仔细看源代码来学习大师们的编程风格。

从第三十九章开始到结尾，主要讲述了比较常用的第三方包，但由于篇幅有限，也就不展开来讲述，有兴趣的朋友可直接到相关开源项目详细了解。

最后，希望更多的人了解和使用Go语言，也希望阅读本书的朋友们多多交流。虽然本书中例子都经过实际运行，但难免出现错误和不足之处，烦请您指出；如有建议也欢迎交流。联系邮箱：roteman@163.com

祝各位Gopher们工作开心，愉快编码！

## 阅读

本书内容在github更新：https://github.com/ffhelicopter/Go42/blob/master/SUMMARY.md<br>
本书内容在简书更新：  https://www.jianshu.com/nb/29056963

#### [>>>开始阅读](https://github.com/ffhelicopter/Go42/blob/master/content/42_01_install.md)



## 交流

虽然本书中例子都经过实际运行，但难免出现错误和不足之处，烦请您指出；如有建议也欢迎交流。

联系邮箱：roteman@163.com 


感谢以下网友对本书提出的修改建议： Joyboo 、林远鹏、Mr_RSI、magic-joker、3lackrush、Jacky2、tanjibo、wisecsj、eternal-flame-AD、isLishude、morya、adophper、ivanberry、xjl662750、huanglizhuo、xianyunyh、荣怡、pannz、yaaaaaaaan、sidbusy、NHibiki、awkj、yufy、lazyou、 liov 、飞翔不能的翔哥、橡_皮泥、刘冲_54ac、henng



## 更新

本书会持续更新！为了更简单表述清楚，某些章节的内容我会根据情况随时更新；当然也会随Go语言版本的不断更新，不断修改完善相关章节的内容和代码。



## 推荐

下列清单是常用的第三方库。

#### WEB框架

1.Gin  https://github.com/gin-gonic/gin

2.Beego  https://github.com/astaxie/beego

3.martini https://github.com/go-martini/martini


#### HTTP

1.httprouter https://github.com/julienschmidt/httprouter

2.fasthttp https://github.com/valyala/fasthttp

3.mux https://github.com/gorilla/mux


#### JSON解析

1.json-iterator https://github.com/json-iterator/go 


#### 数据库以及ORM

1.LevelDB https://github.com/syndtr/goleveldb

2.BoltDB https://github.com/boltdb/bolt

3.MySQL https://github.com/go-sql-driver/mysql

4.tidb https://github.com/pingcap/tidb

5.gorm https://github.com/jinzhu/gorm


#### 爬虫

1.Colly https://github.com/gocolly/colly

2.Goquery https://github.com/PuerkitoBio/goquery


#### 中间件

1.redis https://github.com/go-redis/redis

2.ElasticSearch https://github.com/olivere/elastic

3.Alice https://github.com/justinas/alice


#### 日志

1.zap https://github.com/uber-go/zap


#### 错误处理

1.errors https://github.com/pkg/errors


#### 消息队列

1.Nsq  https://github.com/nsqio/nsq


#### RPC

1.rpcx https://github.com/smallnest/rpcx

2.grpc https://github.com/grpc/grpc-go

#### 协程池

1.ants https://github.com/panjf2000/ants


#### 视觉图像处理

1.bild https://github.com/anthonynsimon/bild

2.gmf https://github.com/3d0c/gmf

3.opencv https://github.com/hybridgroup/gocv


#### 网络

1.KCP https://github.com/xtaci/kcp-go

2.frp https://github.com/fatedier/frp


#### 测试

1.gock https://github.com/h2non/gock



## 知识星球

欢迎加入知识星球《Go42》社群，持续学习Go语言。


![xing2.png](https://github.com/ffhelicopter/Go42/blob/master/content/img/xing2.png)