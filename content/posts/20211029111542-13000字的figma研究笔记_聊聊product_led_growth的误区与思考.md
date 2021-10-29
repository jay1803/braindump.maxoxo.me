+++
title = "13000 字的 Figma 研究笔记，聊聊 Product-Led Growth 的误区与思考"
author = ["Max"]
draft = false
+++

## Opening {#opening}

PLG，是指客户在主动接触到公司的sales之前，就可以自行使用并体验到产品的大部分价
值。
[Product Lead Growth]({{<relref "20210924095204-product_lead_growth.md#" >}})


## Figma的PLG启示 {#figma的plg启示}


### PLG 不是免费为上，早期也要开始思考商业化 {#plg-不是免费为上-早期也要开始思考商业化}


#### 商业化与Community的关系 {#商业化与community的关系}


#### 商业化与Pricing的本质不是收入 {#商业化与pricing的本质不是收入}

<!--list-separator-->

-  什么时候开始monetize?

    a16z 针对 bottom-up/PLG 成长模式的公司写的 pricing 指南：
    [Bottom Up Pricing & Packaging: Let the User Journey Be Your Guide]({{<relref "20211029112146-bottom_up_pricing_packaging_let_the_user_journey_be_your_guide.md#" >}})
    关于什么时候开始monetize，a16z的建议是：

    当你在一个核心用户群众看到repeatable usage patterns的时候（必须是data
    driven的方式分析出来的），或者当你通过不断的客户访谈发现了一些客户愿意付费
    的功能的时候。

<!--list-separator-->

-  定价的目的：qualification (not just monetization)

    通过推出付费而获得的客户数据，才是商业化的最核心价值——而不是收入增长。

<!--list-separator-->

-  Pricing要跟Land and Expand的产品匹配

    Land and expand 主要有两种模式：

    -   Usage-based pricing
    -   有延展性的产品设计

    而且，用usage-based pricing的模式，通常会带来更高的 [Net Dollar Retention]({{<relref "20210813133528-net_dollar_retention.md#" >}}), 而
    这也是现在资本市场最喜欢的指标（aka 更高的估值溢价！）
    另一个路径，就是通过产品设计，满足expand的要求。
    最好的例子，就是最近刚刚IPO的Gitlab. 下面是他们整个产品的组合。
    （Gitlab）虽然看起来个人用户的单价很低，但是后续expand的空间非常大。
    这就不得不说到，Pricing中不可或缺的一环，packaging.
    这么多产品和功能，要怎么叠加到不同的plan里？有时候，免费用户不向付费版转化，
    可能是你的packaging出了问题。

    packaging 设计我们不用说的太具体，有一个框架供大家参考：Leader, Filler, Killer

    能带来最高价值的leader, 和低优先级的Nice to have的Filler都好理解，最tricky
    的是Killer：也就是加进了你的bundle中反而让客户觉得不值得购买的features。

    Killer：也就是加进了你的bundle中反而让客户觉得不值得购买的features。


### PLG 是自下而上，但早期依然需要标杆和Sales {#plg-是自下而上-但早期依然需要标杆和sales}


#### 与最挑剔的标杆用户打磨产品 {#与最挑剔的标杆用户打磨产品}

Figma跟这些客户的早期合作有两个特点。

1.  找到大家共通的痛点。这样根据一两个标杆客户开发的产品就可以很快标准化。
2.  Figma把产品与客户共同成长做到极致。


#### PLG早期也需要（特殊的）Sales {#plg早期也需要-特殊的-sales}

<!--list-separator-->

-  国外的PLG公司不需要sales吗？

<!--list-separator-->

-  PLG不意味着早期就不需要sales

    首先，最早的sales, 其实最好不要传统sales背景。
    你需要的是Renaissance Reps. 这个概念来自于 Harvard Business Review 中的一个
    经典模型：Sales Learning Curve. [The Sales Learning Curve]({{<relref "20211029112335-the_sales_learning_curve.md#" >}})
    Renaissance Reps, 就是说在你刚刚找到 product-market-fit 的时候，你需要的不是
    成熟的sales经验，而是聪明、学习能力强、对产品有理解的年轻人，跟你的产品、市
    场等团队，一起去做最早期的客户沟通和服务,打磨出最初的一套话术和pattern，为
    日后scale打好基础。

    第二点，在Growth/PLG + sales叠加的模式中，所需要的就不是传统的sales了。
    这种PLG模式下的sales有两个特点：
    一方面，咨询大于销售。
    另一方面，需要大量用户行为数据的支撑。


### PLG 的产品更需要系统化的战略设计 {#plg-的产品更需要系统化的战略设计}


#### 战略层面：如何思考产品的定位和核心value {#战略层面-如何思考产品的定位和核心value}

在蓝海战略中，这个Four Actions Framework用来挖掘行业中全新的价值曲线。传统的
竞争策略，一般是差异化和低成本的取舍，全新的价值曲线就是为了打破这个两难

-   Eliminate: 哪些被产业认定为理所当然的元素需要剔除？如果因素不再重要了，那
    么巨头这些领域的积累优势也没那么重要，你也不必再去投入资源compete.
-   Reduce: 哪些元素的含量应被减少到产业标准以下？这就促使你作出决定，看看现有
    产品是不是在功能上设计过头，只是为了竞争而竞争（内卷！）。这些东西徒增成本
    却对用户没有价值。
-   Raise: 哪些元素应该被大大提高到产业标准以上？现有产品的一些功能，如果有质
    的提升（注意，不是简单的量变），可以创造新的客户价值，甚至形成新的行业标准
    和趋势？
-   Create: 哪些产业内从未有过的元素需要创造？这就是要发现全新的价值点，来创造
    新的需求。


#### 标杆用户为核心的Go-To-Market (GTM) {#标杆用户为核心的go-to-market--gtm}

在2021年初的采访中，Dylan回答这三者对于Figma成功的重要性时，他说，应该是三个
同心圆的结构：create是核心，只有帮助大家更好地create,才能促成collaboration,
有了team 之间自然的collab, community也就形成了。


#### 产品与组织：三层Activation + 数据驱动 {#产品与组织-三层activation-plus-数据驱动}

<!--list-separator-->

-  PLG的产品要以self-service的activation为核心

    PLG产品的核心就是Activation。也就是一开始说的，不需要sales介入、用户通过
    self-service，1-2分钟就迅速get到产品的价值。

    B2B产品需要三层Aha moment：

    -   User level Aha: 比如，一个gitlab用户完成basic setup之后提交了第一行代码。
        他解决了一个问题，明白了产品feature的价值。
    -   Team-level Aha：通常通过协作的方式。比如一个两三个人的小team开始用免费版。
    -   Organization-level Aha：team 体会到了产品价值以后，需要pitch到别的部门或者决策层。

    怎样的产品适合PLG？
    显然，不是所有B2B产品。
    第一，跨部门属性很强的、没有一定数量的人使用就很难体会到价值的产品，就很难用PLG。
    第二，产品的使用者离业务比较远的，难度也比较大。

<!--list-separator-->

-  数据驱动需要组织能力支撑

    其实更核心的是data-driven的运营模式和self-service的onboarding 过程。
    ****Gitlab Growth Model****
    要做到这一点，只是有分析团队是不够的。必须把data-driven growth建立成组织能力。


## 三个（小）思考 {#三个-小-思考}


### 投资思考：科学地判断timing是不是伪命题 {#投资思考-科学地判断timing是不是伪命题}

其实，对timing的判断，本质是对市场需求、核心变量以及变量成熟度的判断。
Dylan用了一个有意思的指标：企业中设计师跟开发者的比例。以IBM为例，2012-2017的
5年之间，这个比例从1:72提高到了1:8! 现在很多硅谷公司，这个比例都在1:6左右，对
设计特别强调的公司，甚至会达到1:3!


### 创业维艰：对标追随未必比先驱容易 {#创业维艰-对标追随未必比先驱容易}

Figma CEO在反思这一路历程的时候，最经常说的就是，我们其实应该更快。
与其闭门造车两年多，不如更快ship，更快拿到用户反馈，更快招人。
左晖那句，做难而正确的事情，或许是因为，看似容易的事情，往往会在后面变得更难。


### 小八卦：非典型又典型的B2B创始人 {#小八卦-非典型又典型的b2b创始人}


## Conclusion of all {#conclusion-of-all}

总结一下我们讨论过的误区：

-   PLG早期要有市场广度，但是商业化更重要。商业化目的不是收入增加，而是借助
    Pricing更深入理解自己的市场和客户群。Community是商业化的结果，而不是目标。
-   商业化过程中Pricing不是一蹴而就，要结合严格的数据分析，定期变动。
-   PLG是自下而上，但是早期必须跟有行业影响力的KOL用户，和/或对产品要求最挑剔的
    企业共同打造顶尖产品。
-   PLG不能仅仅依赖创始人的产品灵感，需要结构化思考。
-   不是什么产品都适合PLG。PLG产品设计的核心是基于三层Aha Moment的Activation和一
    个数据驱动的组织体系。
