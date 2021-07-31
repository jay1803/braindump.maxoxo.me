+++
title = "Customer Lifetime Value"
author = ["Max"]
draft = false
+++

## DEFINITION {#definition}

\\(LTV=\frac{{ARPU}\times{Gross\ Margin}}{Customer\ Churn\ Rate}\\)

LTV = [ARPU]({{<relref "20210729003208-average_revenue_per_account.md#" >}}) x [Gross Margin]({{<relref "20210729011241-gross_margin.md#" >}}) / [Customer Churn Rate]({{<relref "churn-rate.md#dimension" >}})

LTV = [ARPU]({{<relref "20210729003208-average_revenue_per_account.md#" >}}) / [Customer Churn Rate]({{<relref "churn-rate.md#dimension" >}})


### The David Skok formula {#the-david-skok-formula}

\\(LTV={ARPA}\times{Gross\ Margin}\times{(\frac{1}{1-K}+\frac{{G}\times{K}}{{(1-K)}^{2}})}\\)

K = (1 - [Customer Churn Rate]({{<relref "churn-rate.md#dimension" >}})) x (1 - [Discount Rate]({{<relref "20210311233019-discount_rate.md#" >}}))
G is a fixed $ amount of monthly growth in ARPA per account (not compounding)


## 客户终身价值 {#客户终身价值}

指的是每个购买者在未来可能为企业带来的收益总和。研究表明，如同某种产品一样，顾
客对于企业利润的贡献也可以分为导入期、快速增长期、成熟期和衰退期。

每个客户的价值都由三部分构成：

-   历史价值(到目前为止已经实现了的顾客价值 )、
-   当前价值(如果顾客当前行为模式 不发生改变的话，将来会给公司带来的顾客价值)
-   潜在价值(如果公司通过有效的交叉销售 可以调动顾客购买积极性，或促使顾客向别人推荐产品

和服务等，从而可能增加的顾客价值)。
