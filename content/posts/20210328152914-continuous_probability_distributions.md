+++
title = "Continuous Probability Distributions"
author = ["Max Zhang"]
tags = ["statistic"]
draft = false
+++

## Definition {#definition}

设 X 是具有分布函数 F 的连续[随机变量]({{< relref "20220527121427-random_variable.md" >}})，且 F 的一阶导数处处存在，则其导函数：
\\(f(x)={\frac {\operatorname {d} F(x)}{\operatorname {d} x}}\\)
称 X 的概率密度函数。

每个概率密度函数都有如下性质：
\\(\int \_{-\infty }^{\infty }f(x)\\,{\rm {d}}x=1\\)
\\(\int \_{a}^{b}f(x)\\,{\rm {d}}x=\operatorname {P} (a\leq X\leq b)=F(b)-F(a)\\)

第一个性质表明，概率密度函数与 x 轴形成的区域的面积等于 1，第二个
性质表明，连续随机变量在区间[a,b]的概率值等于密度函数在区[a,b]上的积分，也即是与
X 轴在[a,b]内形成的区域的面积。因为\\({\displaystyle 0\leq F(x)\leq 1}0\leqF(x)\leq1\\)，且 f(x)是 F(x)的导数，
因此按照积分原理不难推出上面两个公式。


### 类型 {#类型}


#### [正态分布]({{< relref "20210328150552-normal_distribution.md" >}}) {#正态分布--20210328150552-normal-distribution-dot-md}


#### [连续型均匀分布]({{< relref "20210328153145-continuous_uniform_distribution.md" >}}) {#连续型均匀分布--20210328153145-continuous-uniform-distribution-dot-md}
