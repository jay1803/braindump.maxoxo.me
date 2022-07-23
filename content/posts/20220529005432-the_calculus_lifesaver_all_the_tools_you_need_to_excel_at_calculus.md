+++
title = "The Calculus Lifesaver: All the Tools You Need to Excel at Calculus"
author = ["Max Zhang"]
tags = ["book"]
draft = false
+++

## Meta <span class="tag"><span class="ATTACH">ATTACH</span></span> {#meta}


## 第 1 章 函数、图像和直线 {#第-1-章-函数-图像和直线}


### 1.1 函数 {#1-dot-1-函数}

[函数]({{< relref "20210430130022-function.md" >}})是将一个对象转化为另一个对象的规则。起始对象称为输入, 来自称为定义域的集合。返回对象称为输出, 来自称为上域的集合。

f 是一个变换规则, 而 f (x) 是把这个变换规则应用于变量 x 后得到的结果. 因此, 说 “f (x) 是一个函数” 是不正确的, 应该说 “f 是一个函数”.

一个函数必须给每一个有效的输入指定唯一的输出.

值域是所有可能的输出所组成的集合...可能会有重复...值域实际上是上域的一个子集. 上域是可能输出的集合, 而值域则是实际输出的集合.


#### 1.1.1 区间表示法 {#1-dot-1-dot-1-区间表示法}

我们约定, [a, b] 是指从 a 到 b 端点间的所有实数, 包括 a 和 b. 所以 [a, b] 指的是所有使得 a ≤ x ≤ b 成立的 x 的集合.
像 [a, b] 这种形式表示的区间我们称作闭区间.

(a, b) 指的是介于 a 和 b 之间但不包括 a 和 b 的所有实数的集合.
[a, b) 指的是介于 a 和 b 之间、包括 a 但不包括 b 的所有实数的集合; (a, b] 包括 b, 但不包括 a. 这些区间在一个端点处是闭的, 而在另一个端点处是开的. 有时候, 像这样的区间称作半开区间. 上述的 {x : 2 ≤ x &lt; 5} 就是一个例子, 也可以写成 [2, 5).


#### 1.1.2 求定义域 {#1-dot-1-dot-2-求定义域}


#### 1.1.3 利用图像求值域 <span class="tag"><span class="ATTACH">ATTACH</span></span> {#1-dot-1-dot-3-利用图像求值域}

让我们来定义一个新的函数 F , 指定其定义域为 [-2, 1], 并且 F (x) = x2 在此定义域上.
F 和 f 是同一个函数吗？回答是否定的, 因为两个函数的定义域不相同...F 的值域又是什么呢？

{{< figure src="/ox-hugo/_20220601_1336582022-05-29_09-48-49_00014.jpeg" >}}

图　1-1 图 1-1 中左侧的影子覆盖了 y 轴从 0 到 4 (包括 0 和 4) 的所有点, 也就是 [0, 4]; 另一方面, 右侧的影子覆盖了从 0 到 1 (包括 0 和 1)的所有点, 也就是 [0, 1]. 右侧的影子没有贡献更多, 全部的覆盖范围仍然是 [0, 4]. 这就是函数 F 的值域.


#### 1.1.4 垂线检验 {#1-dot-1-dot-4-垂线检验}

关键思想是, 你不可能有两个点有相同的 x 坐标. 换句话说, 在图像上没有两个点会落在相对于 x 轴的同一条垂线上.

垂线检验：如果你有某个图像并想知道它是否是函数的图像, 你就看看是否任何的垂线和图像相交多于一次. 如果是这样的话, 那它就不是函数的图像; 反之, 如果没有一条垂线和图像相交多于一次, 那么你的确面对的是函数的图像.


### 1.2 反函数 {#1-dot-2-反函数}

从输出 y 出发, 这个新的函数发现一个且仅有一个输入 x 满足 f (x) = y. 这个新的函数称为 f 的反函数, 并写作 f -1.


#### 1.2.1 水平线检验 {#1-dot-2-dot-1-水平线检验}

水平线检验：如果每一条水平线和一个函数的图像相交至多一次, 那么这个函数就有一个反函数. 如果即使只有一条水平线和图像相交多于一次, 那么这个函数就没有反函数.


#### 1.2.2 求反函数 {#1-dot-2-dot-2-求反函数}


#### 1.2.3 限制定义域 {#1-dot-2-dot-3-限制定义域}

如果水平线检验失败因而没有反函数, 那应该怎么办呢？我们面临的问题是, 对于相同的 y 有多个 x 值. 解决此问题的唯一方法是：除了这多个 x 值中的一个, 我们放弃所有其他值. 也就是说, 必须决定要保留哪一个 x 值, 然后放弃剩余的值. 正如我们在 1.1 节中看到的, 这称为限制函数的定义域.


#### 1.2.4 反函数的反函数 {#1-dot-2-dot-4-反函数的反函数}

如果 f 有反函数, 那么对于在 f 定义域中的所有 x, f -1 (f (x)) = x 成立; 同样, 对于在 f 值域当中的所有 y, 都有 f (f -1 (y)) = y. (记得, f 的值域和 f -1 的定义域相同, 所以对于 f 值域中的 y, 我们确实可以取到 f -1 (y), 不会导致任何曲解. )


### 1.3 函数的复合 {#1-dot-3-函数的复合}

函数的复合并不是把它们相乘. 例如 f (x) = x2 sin(x), f 不是两个函数的复合, 因为对任意给定的 x, 计算 f (x) 的值需要求解 x2 和 sin(x)(先求哪个值都没关系, 这与复合函数不同)


### 1.4 奇函数和偶函数 {#1-dot-4-奇函数和偶函数}

[Even and Odd Functions]({{< relref "20220529144042-even_and_odd_functions.md" >}})
f (x) = x2 的函数 f , 任选一个正数 (我选 3) 作用于函数 f (得到 9). 现在取该数的负值, 由我选择的数可得 -3, 将其作用于函数 f (又得到 9).

如果对 f 定义域里的所有 x 有 f (-x) = f (x), 则 f 是偶函数.
偶函数的图像关于 y 轴具有镜面对称性.

当对 f 定义域内所有 x 都有 f (-x) = -f (x) 时, f 是奇函数.
奇函数的图像关于原点有 180° 的点对称性.

大多数函数是非奇非偶的
只有一个函数是既奇又偶的, 它就是非常单调的对所有 x 都成立的 f (x) = 0(我们称之为零函数).


### 1.5 线性函数的图像 {#1-dot-5-线性函数的图像}

形如 f (x) = mx + b 的函数叫作线性函数.

通过斜率找到函数的公式：
已知直线通过 (x_0, y_0)，斜率为 m，则它的方程为 y-y_0 = m(x-x_0)


### 1.6 常见函数及其图像 {#1-dot-6-常见函数及其图像}


## 第 2 章 三角学回顾 {#第-2-章-三角学回顾}


### 2.1 基本知识 {#2-dot-1-基本知识}


### 2.2 扩展三角函数定义域 {#2-dot-2-扩展三角函数定义域}


#### 2.2.1 ASTC 方法 {#2-dot-2-dot-1-astc-方法}


#### 2.2.2 [0; 2π] 以外的三角函数 {#2-dot-2-dot-2-0-2π-以外的三角函数}


### 2.3 三角函数的图像 {#2-dot-3-三角函数的图像}


### 2.4 三角恒等式 {#2-dot-4-三角恒等式}


## 第 3 章 极限导论 {#第-3-章-极限导论}


### 3.1 极限：基本思想 {#3-dot-1-极限-基本思想}


### 3.2 左极限与右极限 {#3-dot-2-左极限与右极限}


### 3.3 何时不存在极限 {#3-dot-3-何时不存在极限}


### 3.4 在∞ 和-∞ 处的极限 {#3-dot-4-在-和-处的极限}


### 3.5 关于渐近线的两个常见误解 {#3-dot-5-关于渐近线的两个常见误解}


### 3.6 三明治定理 {#3-dot-6-三明治定理}


### 3.7 极限的基本类型小结 {#3-dot-7-极限的基本类型小结}


## 第 4 章 求解多项式的极限问题 {#第-4-章-求解多项式的极限问题}


### 4.1 x → a 时的有理函数的极限 {#4-dot-1-x-a-时的有理函数的极限}


### 4.2 x → a 时的平方根的极限 {#4-dot-2-x-a-时的平方根的极限}


### 4.3 x → ∞ 时的有理函数的极限 {#4-dot-3-x-时的有理函数的极限}


### 4.4 x → ∞ 时的多项式型函数的极限 {#4-dot-4-x-时的多项式型函数的极限}


### 4.5 x → -∞ 时的有理函数的极限 {#4-dot-5-x-时的有理函数的极限}


### 4.6 包含绝对值的函数的极限 {#4-dot-6-包含绝对值的函数的极限}


## 第 5 章 连续性和可导性 {#第-5-章-连续性和可导性}


### 5.1 连续性 {#5-dot-1-连续性}


#### 5.1.1 在一点处连续 {#5-dot-1-dot-1-在一点处连续}


#### 5.1.2 在一个区间上连续 {#5-dot-1-dot-2-在一个区间上连续}


#### 5.1.3 连续函数的一些例子 {#5-dot-1-dot-3-连续函数的一些例子}


#### 5.1.4 介值定理 {#5-dot-1-dot-4-介值定理}


#### 5.1.5 一个更难的介值定理例子 {#5-dot-1-dot-5-一个更难的介值定理例子}


#### 5.1.6 连续函数的最大值和最小值 {#5-dot-1-dot-6-连续函数的最大值和最小值}


### 5.2 可导性 {#5-dot-2-可导性}


#### 5.2.1 平均速率 {#5-dot-2-dot-1-平均速率}


#### 5.2.2 位移和速度 {#5-dot-2-dot-2-位移和速度}


#### 5.2.3 瞬时速度 {#5-dot-2-dot-3-瞬时速度}


#### 5.2.4 速度的图像阐释 {#5-dot-2-dot-4-速度的图像阐释}


#### 5.2.5 切线 {#5-dot-2-dot-5-切线}


#### 5.2.6 导函数 {#5-dot-2-dot-6-导函数}


#### 5.2.7 作为极限比的导数 {#5-dot-2-dot-7-作为极限比的导数}


#### 5.2.8 线性函数的导数 {#5-dot-2-dot-8-线性函数的导数}


#### 5.2.9 二阶导数和更高阶导数 {#5-dot-2-dot-9-二阶导数和更高阶导数}

5.2.10 何时导数不存在
5.2.11 可导性和连续性


## 第 6 章 求解微分问题 {#第-6-章-求解微分问题}


### 6.1 使用定义求导 {#6-dot-1-使用定义求导}


### 6.2 用更好的办法求导 {#6-dot-2-用更好的办法求导}


#### 6.2.1 函数的常数倍 {#6-dot-2-dot-1-函数的常数倍}


#### 6.2.2 函数和与函数差 {#6-dot-2-dot-2-函数和与函数差}


#### 6.2.3 通过乘积法则求积函数的导数 {#6-dot-2-dot-3-通过乘积法则求积函数的导数}


#### 6.2.4 通过商法则求商函数的导数 {#6-dot-2-dot-4-通过商法则求商函数的导数}


#### 6.2.5 通过链式求导法则求复合函数的导数 {#6-dot-2-dot-5-通过链式求导法则求复合函数的导数}


#### 6.2.6 那个难以处理的例子 {#6-dot-2-dot-6-那个难以处理的例子}


#### 6.2.7 乘积法则和链式求导法则的理由 {#6-dot-2-dot-7-乘积法则和链式求导法则的理由}


### 6.3 求切线方程 {#6-dot-3-求切线方程}


### 6.4 速度和加速度 {#6-dot-4-速度和加速度}


### 6.5 导数伪装的极限 {#6-dot-5-导数伪装的极限}


### 6.6 分段函数的导数 {#6-dot-6-分段函数的导数}


### 6.7 直接画出导函数的图像 {#6-dot-7-直接画出导函数的图像}


## 第 7 章 三角函数的极限和导数 {#第-7-章-三角函数的极限和导数}


### 7.1 三角函数的极限 {#7-dot-1-三角函数的极限}


#### 7.1.1 小数的情况 {#7-dot-1-dot-1-小数的情况}


#### 7.1.2 问题的求解——小数的情况 {#7-dot-1-dot-2-问题的求解-小数的情况}


#### 7.1.3 大数的情况 {#7-dot-1-dot-3-大数的情况}


#### 7.1.4 “其他的” 情况 {#7-dot-1-dot-4-其他的-情况}


#### 7.1.5 一个重要极限的证明 {#7-dot-1-dot-5-一个重要极限的证明}


### 7.2 三角函数的导数 {#7-dot-2-三角函数的导数}


#### 7.2.1 求三角函数导数的例子 {#7-dot-2-dot-1-求三角函数导数的例子}


#### 7.2.2 简谐运动 {#7-dot-2-dot-2-简谐运动}


#### 7.2.3 一个有趣的函数 {#7-dot-2-dot-3-一个有趣的函数}


## 第 8 章 隐函数求导和相关变化率 {#第-8-章-隐函数求导和相关变化率}


### 8.1 隐函数求导 {#8-dot-1-隐函数求导}


#### 8.1.1 技巧和例子 {#8-dot-1-dot-1-技巧和例子}


#### 8.1.2 隐函数求二阶导 {#8-dot-1-dot-2-隐函数求二阶导}


### 8.2 相关变化率 {#8-dot-2-相关变化率}


#### 8.2.1 一个简单的例子 {#8-dot-2-dot-1-一个简单的例子}


#### 8.2.2 一个稍难的例子 {#8-dot-2-dot-2-一个稍难的例子}


#### 8.2.3 一个更难的例子 {#8-dot-2-dot-3-一个更难的例子}


#### 8.2.4 一个非常难的例子 {#8-dot-2-dot-4-一个非常难的例子}


## 第 9 章 指数函数和对数函数 {#第-9-章-指数函数和对数函数}


### 9.1 基础知识 {#9-dot-1-基础知识}


#### 9.1.1 指数函数的回顾 {#9-dot-1-dot-1-指数函数的回顾}


#### 9.1.2 对数函数的回顾 {#9-dot-1-dot-2-对数函数的回顾}


#### 9.1.3 对数函数、指数函数及反函数 {#9-dot-1-dot-3-对数函数-指数函数及反函数}


#### 9.1.4 对数法则 {#9-dot-1-dot-4-对数法则}


### 9.2 e 的定义 {#9-dot-2-e-的定义}


#### 9.2.1 一个有关复利的问题 {#9-dot-2-dot-1-一个有关复利的问题}


#### 9.2.2 问题的答案 {#9-dot-2-dot-2-问题的答案}


#### 9.2.3 更多关于 e 和对数函数的内容 {#9-dot-2-dot-3-更多关于-e-和对数函数的内容}


### 9.3 对数函数和指数函数求导 {#9-dot-3-对数函数和指数函数求导}


### 9.4 求解指数函数或对数函数的极限 {#9-dot-4-求解指数函数或对数函数的极限}


#### 9.4.1 涉及 e 的定义的极限 {#9-dot-4-dot-1-涉及-e-的定义的极限}


#### 9.4.2 指数函数在 0 附近的行为 {#9-dot-4-dot-2-指数函数在-0-附近的行为}


#### 9.4.3 对数函数在 1 附近的行为 {#9-dot-4-dot-3-对数函数在-1-附近的行为}


#### 9.4.4 指数函数在∞ 或-∞ 附近的行为 {#9-dot-4-dot-4-指数函数在-或-附近的行为}


#### 9.4.5 对数函数在∞附近的行为 {#9-dot-4-dot-5-对数函数在-附近的行为}


#### 9.4.6 对数函数在 0 附近的行为 {#9-dot-4-dot-6-对数函数在-0-附近的行为}


### 9.5 取对数求导法 {#9-dot-5-取对数求导法}


### 9.6 指数增长和指数衰变 {#9-dot-6-指数增长和指数衰变}


#### 9.6.1 指数增长 {#9-dot-6-dot-1-指数增长}


#### 9.6.2 指数衰变 {#9-dot-6-dot-2-指数衰变}


### 9.7 双曲函数 {#9-dot-7-双曲函数}


## 第 10 章 反函数和反三角函数 {#第-10-章-反函数和反三角函数}


### 10.1 导数和反函数 {#10-dot-1-导数和反函数}


#### 10.1.1 使用导数证明反函数存在 {#10-dot-1-dot-1-使用导数证明反函数存在}


#### 10.1.2 导数和反函数：可能出现的问题 {#10-dot-1-dot-2-导数和反函数-可能出现的问题}


#### 10.1.3 求反函数的导数 {#10-dot-1-dot-3-求反函数的导数}


#### 10.1.4 一个综合性例子 {#10-dot-1-dot-4-一个综合性例子}


### 10.2 反三角函数 {#10-dot-2-反三角函数}


#### 10.2.1 反正弦函数 {#10-dot-2-dot-1-反正弦函数}


#### 10.2.2 反余弦函数 {#10-dot-2-dot-2-反余弦函数}


#### 10.2.3 反正切函数 {#10-dot-2-dot-3-反正切函数}


#### 10.2.4 反正割函数 {#10-dot-2-dot-4-反正割函数}


#### 10.2.5 反余割函数和反余切函数 {#10-dot-2-dot-5-反余割函数和反余切函数}


#### 10.2.6 计算反三角函数 {#10-dot-2-dot-6-计算反三角函数}


### 10.3 反双曲函数 {#10-dot-3-反双曲函数}


## 第 11 章 导数和图像 {#第-11-章-导数和图像}


### 11.1 函数的极值 {#11-dot-1-函数的极值}


#### 11.1.1 全局极值和局部极值 {#11-dot-1-dot-1-全局极值和局部极值}


#### 11.1.2 极值定理 {#11-dot-1-dot-2-极值定理}


#### 11.1.3 求全局最大值和最小值 {#11-dot-1-dot-3-求全局最大值和最小值}


### 11.2 罗尔定理 {#11-dot-2-罗尔定理}


### 11.3 中值定理 {#11-dot-3-中值定理}


### 11.4 二阶导数和图像 {#11-dot-4-二阶导数和图像}


### 11.5 对导数为零点的分类 {#11-dot-5-对导数为零点的分类}


#### 11.5.1 使用一次导数 {#11-dot-5-dot-1-使用一次导数}


#### 11.5.2 使用二阶导数 {#11-dot-5-dot-2-使用二阶导数}


## 第 12 章 绘制函数图像 {#第-12-章-绘制函数图像}


### 12.1 建立符号表格 {#12-dot-1-建立符号表格}


#### 12.1.1 建立一阶导数的符号表格 {#12-dot-1-dot-1-建立一阶导数的符号表格}


#### 12.1.2 建立二阶导数的符号表格 {#12-dot-1-dot-2-建立二阶导数的符号表格}


### 12.2 绘制函数图像的全面方法 {#12-dot-2-绘制函数图像的全面方法}


### 12.3 例题 {#12-dot-3-例题}


#### 12.3.1 一个不使用导数的例子 {#12-dot-3-dot-1-一个不使用导数的例子}


#### 12.3.2 完整的方法：例一 {#12-dot-3-dot-2-完整的方法-例一}


#### 12.3.3 完整的方法：例二 {#12-dot-3-dot-3-完整的方法-例二}


#### 12.3.4 完整的方法：例三 {#12-dot-3-dot-4-完整的方法-例三}


#### 12.3.5 完整的方法：例四 {#12-dot-3-dot-5-完整的方法-例四}


## 第 13 章 最优化和线性化 {#第-13-章-最优化和线性化}


### 13.1 最优化 {#13-dot-1-最优化}


#### 13.1.1 一个简单的最优化例子 {#13-dot-1-dot-1-一个简单的最优化例子}


#### 13.1.2 最优化问题：一般方法 {#13-dot-1-dot-2-最优化问题-一般方法}


#### 13.1.3 一个最优化的例子 {#13-dot-1-dot-3-一个最优化的例子}


#### 13.1.4 另一个最优化的例子 {#13-dot-1-dot-4-另一个最优化的例子}


#### 13.1.5 在最优化问题中使用隐函数求导 {#13-dot-1-dot-5-在最优化问题中使用隐函数求导}


#### 13.1.6 一个较难的最优化例子 {#13-dot-1-dot-6-一个较难的最优化例子}


### 13.2 线性化 {#13-dot-2-线性化}


#### 13.2.1 线性化问题：一般方法 {#13-dot-2-dot-1-线性化问题-一般方法}


#### 13.2.2 微分 {#13-dot-2-dot-2-微分}


#### 13.2.3 线性化的总结和例子 {#13-dot-2-dot-3-线性化的总结和例子}


#### 13.2.4 近似中的误差 {#13-dot-2-dot-4-近似中的误差}


### 13.3 牛顿法 {#13-dot-3-牛顿法}


## 第 14 章 洛必达法则及极限问题总结 {#第-14-章-洛必达法则及极限问题总结}


### 14.1 洛必达法则 {#14-dot-1-洛必达法则}


#### 14.1.1 类型 A：0/0 {#14-dot-1-dot-1-类型-a-0-0}


#### 14.1.2 类型 A：±∞/ ±∞ {#14-dot-1-dot-2-类型-a}


#### 14.1.3 类型 B1: (∞－∞) {#14-dot-1-dot-3-类型-b1}


#### 14.1.4 类型 B2: (0 ×±∞) {#14-dot-1-dot-4-类型-b2--0}


#### 14.1.5 类型 C:􀀀(1±∞, 0º 或∞º) {#14-dot-1-dot-5-类型-c--1-0º-或-º}


#### 14.1.6 洛必达法则类型的总结 {#14-dot-1-dot-6-洛必达法则类型的总结}


### 14.2 关于极限的总结 {#14-dot-2-关于极限的总结}


## 第 15 章 积分 {#第-15-章-积分}


### 15.1 求和符号 {#15-dot-1-求和符号}


#### 15.1.1 一个有用的求和 {#15-dot-1-dot-1-一个有用的求和}


#### 15.1.2 伸缩求和法 {#15-dot-1-dot-2-伸缩求和法}


### 15.2 位移和面积 {#15-dot-2-位移和面积}


#### 15.2.1 三个简单的例子 {#15-dot-2-dot-1-三个简单的例子}


#### 15.2.2 一段更常规的旅行 {#15-dot-2-dot-2-一段更常规的旅行}


#### 15.2.3 有向面积 {#15-dot-2-dot-3-有向面积}


#### 15.2.4 连续的速度 {#15-dot-2-dot-4-连续的速度}


#### 15.2.5 两个特别的估算 {#15-dot-2-dot-5-两个特别的估算}


## 第 16 章 定积分 {#第-16-章-定积分}


### 16.1 基本思想 {#16-dot-1-基本思想}


### 16.2 定积分的定义 {#16-dot-2-定积分的定义}


### 16.3 定积分的性质 {#16-dot-3-定积分的性质}


### 16.4 求面积 {#16-dot-4-求面积}


#### 16.4.1 求通常的面积 {#16-dot-4-dot-1-求通常的面积}


#### 16.4.2 求解两条曲线之间的面积 {#16-dot-4-dot-2-求解两条曲线之间的面积}


#### 16.4.3 求曲线与 y 轴所围成的面积 {#16-dot-4-dot-3-求曲线与-y-轴所围成的面积}


### 16.5 估算积分 {#16-dot-5-估算积分}


### 16.6 积分的平均值和中值定理 {#16-dot-6-积分的平均值和中值定理}


### 16.7 不可积的函数 {#16-dot-7-不可积的函数}


## 第 17 章 微积分基本定理 {#第-17-章-微积分基本定理}


### 17.1 用其他函数的积分来表示的函数 {#17-dot-1-用其他函数的积分来表示的函数}


### 17.2 微积分的第一基本定理 {#17-dot-2-微积分的第一基本定理}


### 17.3 微积分的第二基本定理 {#17-dot-3-微积分的第二基本定理}


### 17.4 不定积分 {#17-dot-4-不定积分}


### 17.5 怎样解决问题：微积分的第一基本定理 {#17-dot-5-怎样解决问题-微积分的第一基本定理}


#### 17.5.1 变形 1：变量是积分下限 {#17-dot-5-dot-1-变形-1-变量是积分下限}


#### 17.5.2 变形 2：积分上限是一个函数 {#17-dot-5-dot-2-变形-2-积分上限是一个函数}


#### 17.5.3 变形 3：积分上下限都为函数 {#17-dot-5-dot-3-变形-3-积分上下限都为函数}


#### 17.5.4 变形 4：极限伪装成导数 {#17-dot-5-dot-4-变形-4-极限伪装成导数}


### 17.6 怎样解决问题：微积分的第二基本定理 {#17-dot-6-怎样解决问题-微积分的第二基本定理}


#### 17.6.1 计算不定积分 {#17-dot-6-dot-1-计算不定积分}


#### 17.6.2 计算定积分 {#17-dot-6-dot-2-计算定积分}


#### 17.6.3 面积和绝对值 {#17-dot-6-dot-3-面积和绝对值}


### 17.7 技术要点 {#17-dot-7-技术要点}


### 17.8 微积分第一基本定理的证明 {#17-dot-8-微积分第一基本定理的证明}


## 第 18 章 积分的方法 I {#第-18-章-积分的方法-i}


### 18.1 换元法 {#18-dot-1-换元法}


#### 18.1.1 换元法和定积分 {#18-dot-1-dot-1-换元法和定积分}


#### 18.1.2 如何换元 {#18-dot-1-dot-2-如何换元}


#### 18.1.3 换元法的理论解释 {#18-dot-1-dot-3-换元法的理论解释}


### 18.2 分部积分法 {#18-dot-2-分部积分法}


### 18.3 部分分式 {#18-dot-3-部分分式}


#### 18.3.1 部分分式的代数运算 {#18-dot-3-dot-1-部分分式的代数运算}


#### 18.3.2 对每一部分积分 {#18-dot-3-dot-2-对每一部分积分}


#### 18.3.3 方法和一个完整的例子 {#18-dot-3-dot-3-方法和一个完整的例子}


## 第 19 章 积分的方法 II {#第-19-章-积分的方法-ii}


### 19.1 应用三角恒等式的积分 {#19-dot-1-应用三角恒等式的积分}


### 19.2 关于三角函数的幂的积分 {#19-dot-2-关于三角函数的幂的积分}


#### 19.2.1 sin 或 cos 的幂 {#19-dot-2-dot-1-sin-或-cos-的幂}


#### 19.2.2 tan 的幂 {#19-dot-2-dot-2-tan-的幂}


#### 19.2.3 sec 的幂 {#19-dot-2-dot-3-sec-的幂}


#### 19.2.4 cot 的幂 {#19-dot-2-dot-4-cot-的幂}


#### 19.2.5 csc 的幂 {#19-dot-2-dot-5-csc-的幂}


#### 19.2.6 约化公式 {#19-dot-2-dot-6-约化公式}


### 19.3 关于三角换元法的积分 {#19-dot-3-关于三角换元法的积分}


#### 19.3.1 类型 1：√(α²-x²) {#19-dot-3-dot-1-类型-1--α-x}


#### 19.3.2 类型 2：√(x²+α²) {#19-dot-3-dot-2-类型-2--x-plus-α}


#### 19.3.3 类型 3：√(x²-α²) {#19-dot-3-dot-3-类型-3--x-α}


#### 19.3.4 配方和三角换元法 {#19-dot-3-dot-4-配方和三角换元法}


#### 19.3.5 关于三角换元法的总结 {#19-dot-3-dot-5-关于三角换元法的总结}


#### 19.3.6 平方根的方法和三角换元法 {#19-dot-3-dot-6-平方根的方法和三角换元法}


### 19.4 积分技巧总结 {#19-dot-4-积分技巧总结}


## 第 20 章 反常积分：基本概念 {#第-20-章-反常积分-基本概念}


### 20.1 收敛和发散 {#20-dot-1-收敛和发散}


#### 20.1.1 反常积分的一些例子 {#20-dot-1-dot-1-反常积分的一些例子}


#### 20.1.2 其他破裂点 {#20-dot-1-dot-2-其他破裂点}


### 20.2 关于无穷区间上的积分 {#20-dot-2-关于无穷区间上的积分}


### 20.3 比较判别法(理论) {#20-dot-3-比较判别法--理论}


### 20.4 极限比较判别法(理论) {#20-dot-4-极限比较判别法--理论}


#### 20.4.1 函数互为渐近线 {#20-dot-4-dot-1-函数互为渐近线}


#### 20.4.2 关于判别法的陈述 {#20-dot-4-dot-2-关于判别法的陈述}


### 20.5 p 判别法(理论) {#20-dot-5-p-判别法--理论}


### 20.6 绝对收敛判别法 {#20-dot-6-绝对收敛判别法}


## 第 21 章 反常积分：如何解题 {#第-21-章-反常积分-如何解题}


### 21.1 如何开始 {#21-dot-1-如何开始}


#### 21.1.1 拆分积分 {#21-dot-1-dot-1-拆分积分}


#### 21.1.2 如何处理负函数值 {#21-dot-1-dot-2-如何处理负函数值}


### 21.2 积分判别法总结 {#21-dot-2-积分判别法总结}


### 21.3 常见函数在∞ 和－∞附近的表现 {#21-dot-3-常见函数在-和-附近的表现}


#### 21.3.1 多项式和多项式型函数在 1 和¡1 附近的表现 {#21-dot-3-dot-1-多项式和多项式型函数在-1-和-1-附近的表现}


#### 21.3.2 三角函数在∞ 和－∞ 附近的表现 {#21-dot-3-dot-2-三角函数在-和-附近的表现}


#### 21.3.3 指数在∞和－∞附近的表现 {#21-dot-3-dot-3-指数在-和-附近的表现}


#### 21.3.4 对数在∞ 附近的表现 {#21-dot-3-dot-4-对数在-附近的表现}


### 21.4 常见函数在 0 附近的表现 {#21-dot-4-常见函数在-0-附近的表现}


#### 21.4.1 多项式和多项式型函数在 0 附近的表现 {#21-dot-4-dot-1-多项式和多项式型函数在-0-附近的表现}


#### 21.4.2 三角函数在 0 附近的表现 {#21-dot-4-dot-2-三角函数在-0-附近的表现}


#### 21.4.3 指数函数在 0 附近的表现 {#21-dot-4-dot-3-指数函数在-0-附近的表现}


#### 21.4.4 对数函数在 0 附近的表现 {#21-dot-4-dot-4-对数函数在-0-附近的表现}


#### 21.4.5 更一般的函数在 0 附近的表现 {#21-dot-4-dot-5-更一般的函数在-0-附近的表现}


### 21.5 如何应对不在 0 或∞ 处的瑕点 {#21-dot-5-如何应对不在-0-或-处的瑕点}


## 第 22 章 数列和级数：基本概念 {#第-22-章-数列和级数-基本概念}


### 22.1 数列的收敛和发散 {#22-dot-1-数列的收敛和发散}


#### 22.1.1 数列和函数的联系 {#22-dot-1-dot-1-数列和函数的联系}


#### 22.1.2 两个重要数列 {#22-dot-1-dot-2-两个重要数列}


### 22.2 级数的收敛与发散 {#22-dot-2-级数的收敛与发散}


### 22.3 第 n 项判别法(理论) {#22-dot-3-第-n-项判别法--理论}


### 22.4 无穷级数和反常积分的性质 {#22-dot-4-无穷级数和反常积分的性质}


#### 22.4.1 比较判别法(理论) {#22-dot-4-dot-1-比较判别法--理论}


#### 22.4.2 极限比较判别法(理论) {#22-dot-4-dot-2-极限比较判别法--理论}


#### 22.4.3 ρ 判别法(理论) {#22-dot-4-dot-3-ρ-判别法--理论}


#### 22.4.4 绝对收敛判别法 {#22-dot-4-dot-4-绝对收敛判别法}


### 22.5 级数的新判别法 {#22-dot-5-级数的新判别法}


#### 22.5.1 比式判别法(理论) {#22-dot-5-dot-1-比式判别法--理论}


#### 22.5.2 根式判别法(理论) {#22-dot-5-dot-2-根式判别法--理论}


#### 22.5.3 积分判别法(理论) {#22-dot-5-dot-3-积分判别法--理论}


#### 22.5.4 交错级数判别法(理论) {#22-dot-5-dot-4-交错级数判别法--理论}


## 第 23 章 求解级数问题 {#第-23-章-求解级数问题}


### 23.1 求几何级数的值 {#23-dot-1-求几何级数的值}


### 23.2 应用第 n 项判别法 {#23-dot-2-应用第-n-项判别法}


### 23.3 应用比式判别法 {#23-dot-3-应用比式判别法}


### 23.4 应用根式判别法 {#23-dot-4-应用根式判别法}


### 23.5 应用积分判别法 {#23-dot-5-应用积分判别法}


### 23.6 应用比较判别法、极限比较判别法和 p 判别法 {#23-dot-6-应用比较判别法-极限比较判别法和-p-判别法}


### 23.7 应对含负项的级数 {#23-dot-7-应对含负项的级数}


## 第 24 章 泰勒多项式、泰勒级数和幂级数导论 {#第-24-章-泰勒多项式-泰勒级数和幂级数导论}


### 24.1 近似值和泰勒多项式 {#24-dot-1-近似值和泰勒多项式}


#### 24.1.1 重访线性化 {#24-dot-1-dot-1-重访线性化}


#### 24.1.2 二次近似 {#24-dot-1-dot-2-二次近似}


#### 24.1.3 高阶近似 {#24-dot-1-dot-3-高阶近似}


#### 24.1.4 泰勒定理 {#24-dot-1-dot-4-泰勒定理}


### 24.2 幂级数和泰勒级数 {#24-dot-2-幂级数和泰勒级数}


#### 24.2.1 一般幂级数 {#24-dot-2-dot-1-一般幂级数}


#### 24.2.2 泰勒级数和麦克劳林级数 {#24-dot-2-dot-2-泰勒级数和麦克劳林级数}


#### 24.2.3 泰勒级数的收敛性 {#24-dot-2-dot-3-泰勒级数的收敛性}


### 24.3 一个有用的极限 {#24-dot-3-一个有用的极限}


## 第 25 章 求解估算问题 {#第-25-章-求解估算问题}


### 25.1 泰勒多项式与泰勒级数总结 {#25-dot-1-泰勒多项式与泰勒级数总结}


### 25.2 求泰勒多项式与泰勒级数 {#25-dot-2-求泰勒多项式与泰勒级数}


### 25.3 用误差项估算问题 {#25-dot-3-用误差项估算问题}


#### 25.3.1 第一个例子 {#25-dot-3-dot-1-第一个例子}


#### 25.3.2 第二个例子 {#25-dot-3-dot-2-第二个例子}


#### 25.3.3 第三个例子 {#25-dot-3-dot-3-第三个例子}


#### 25.3.4 第四个例子 {#25-dot-3-dot-4-第四个例子}


#### 25.3.5 第五个例子 {#25-dot-3-dot-5-第五个例子}


#### 25.3.6 误差项估算的一般方法 {#25-dot-3-dot-6-误差项估算的一般方法}


### 25.4 误差估算的另一种方法 {#25-dot-4-误差估算的另一种方法}


## 第 26 章 泰勒级数和幂级数：如何解题 {#第-26-章-泰勒级数和幂级数-如何解题}


### 26.1 幂级数的收敛性 {#26-dot-1-幂级数的收敛性}


#### 26.1.1 收敛半径 {#26-dot-1-dot-1-收敛半径}


#### 26.1.2 求收敛半径和收敛区域 {#26-dot-1-dot-2-求收敛半径和收敛区域}


### 26.2 合成新的泰勒级数 {#26-dot-2-合成新的泰勒级数}


#### 26.2.1 代换和泰勒级数 {#26-dot-2-dot-1-代换和泰勒级数}


#### 26.2.2 泰勒级数求导 {#26-dot-2-dot-2-泰勒级数求导}


#### 26.2.3 泰勒级数求积分 {#26-dot-2-dot-3-泰勒级数求积分}


#### 26.2.4 泰勒级数相加和相减 {#26-dot-2-dot-4-泰勒级数相加和相减}


#### 26.2.5 泰勒级数相乘 {#26-dot-2-dot-5-泰勒级数相乘}


#### 26.2.6 泰勒级数相除 {#26-dot-2-dot-6-泰勒级数相除}


### 26.3 利用幂级数和泰勒级数求导 {#26-dot-3-利用幂级数和泰勒级数求导}


### 26.4 利用麦克劳林级数求极限 {#26-dot-4-利用麦克劳林级数求极限}


## 第 27 章 参数方程和极坐标 {#第-27-章-参数方程和极坐标}


### 27.1 参数方程 {#27-dot-1-参数方程}


### 27.2 极坐标 {#27-dot-2-极坐标}


#### 27.2.1 极坐标与笛卡儿坐标互换 {#27-dot-2-dot-1-极坐标与笛卡儿坐标互换}


#### 27.2.2 极坐标系中画曲线 {#27-dot-2-dot-2-极坐标系中画曲线}


#### 27.2.3 求极坐标曲线的切线 {#27-dot-2-dot-3-求极坐标曲线的切线}


#### 27.2.4 求极坐标曲线围成的面积 {#27-dot-2-dot-4-求极坐标曲线围成的面积}


## 第 28 章 复数 {#第-28-章-复数}


### 28.1 基础 {#28-dot-1-基础}


### 28.2 复平面 {#28-dot-2-复平面}


### 28.3 复数的高次幂 {#28-dot-3-复数的高次幂}


### 28.4 解 z^n＝ w {#28-dot-4-解-z-n-w}


### 28.5 解 e^z ＝ w {#28-dot-5-解-e-z-w}


### 28.6 一些三角级数 {#28-dot-6-一些三角级数}


### 28.7 欧拉恒等式和幂级数 {#28-dot-7-欧拉恒等式和幂级数}


## 第 29 章 体积、弧长和表面积 {#第-29-章-体积-弧长和表面积}


### 29.1 旋转体的体积 {#29-dot-1-旋转体的体积}


#### 29.1.1 圆盘法 {#29-dot-1-dot-1-圆盘法}


#### 29.1.2 壳法 {#29-dot-1-dot-2-壳法}


#### 29.1.3 总结和变式 {#29-dot-1-dot-3-总结和变式}


#### 29.1.4 变式 1：区域在曲线和 y 轴之间 {#29-dot-1-dot-4-变式-1-区域在曲线和-y-轴之间}


#### 29.1.5 变式 2：两曲线间的区域 {#29-dot-1-dot-5-变式-2-两曲线间的区域}


#### 29.1.6 变式 3：绕平行于坐标轴的轴旋转 {#29-dot-1-dot-6-变式-3-绕平行于坐标轴的轴旋转}


### 29.2 一般立体体积 {#29-dot-2-一般立体体积}


### 29.3 弧长 {#29-dot-3-弧长}


### 29.4 旋转体的表面积 {#29-dot-4-旋转体的表面积}


## 第 30 章 微分方程 {#第-30-章-微分方程}


### 30.1 微分方程导论 {#30-dot-1-微分方程导论}


### 30.2 可分离变量的一阶微分方程 {#30-dot-2-可分离变量的一阶微分方程}


### 30.3 一阶线性方程 {#30-dot-3-一阶线性方程}


### 30.4 常系数微分方程 {#30-dot-4-常系数微分方程}


#### 30.4.1 解一阶齐次方程 {#30-dot-4-dot-1-解一阶齐次方程}


#### 30.4.2 解二阶齐次方程 {#30-dot-4-dot-2-解二阶齐次方程}


#### 30.4.3 为什么特征二次方程适用 {#30-dot-4-dot-3-为什么特征二次方程适用}


#### 30.4.4 非齐次方程和特解 {#30-dot-4-dot-4-非齐次方程和特解}


#### 30.4.5 求特解 {#30-dot-4-dot-5-求特解}


#### 30.4.6 求特解的例子 {#30-dot-4-dot-6-求特解的例子}


#### 30.4.7 解决 yP 和 yH 间的冲突 {#30-dot-4-dot-7-解决-yp-和-yh-间的冲突}


#### 30.4.8 IVP {#30-dot-4-dot-8-ivp}


### 30.5 微分方程建模 {#30-dot-5-微分方程建模}