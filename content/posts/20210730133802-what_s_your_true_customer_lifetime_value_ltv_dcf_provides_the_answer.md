+++
title = "What’s your TRUE customer lifetime value (LTV)?  – DCF provides the answer"
author = ["Max"]
draft = false
+++

## Notes {#notes}

But it’s important to note that these formulae will only yield meaningful
results when your sales and marketing process and costs are predictable and
scalable.

Instead of spending too much time obsessing over CAC and [LTV](customer-lifetime-value.md), rather focus
your energies on solving the problems of improving product/market fit, and
making your customer acquisition repeatable, scalable and profitable.

We recommend using a 10% discount rate, but this may differ depending on your
own cost of capital.

We have previously recommended your [LTV](customer-lifetime-value.md) to [CAC](customer-acquisition-cost.md) ratio be greater than 3.

Data you’ll need to model this new LTV, using the spreadsheet tool below:

-   Average starting contract revenue per account
-   Gross margin (this should include customer support and account management
    time to retain and upsell)
-   Churn rate
-   Growth rate for retained customers


### Real World Model {#real-world-model}


### Introduction {#introduction}

All of my regular SaaS/subscription economy readers know that one of the core
concepts that I stress is the idea of measuring Unit Economics at the
customer level to help entreprenurs figure out if they have a good business

Unit economics is a simple concept where we look to make sure that the profit
we are getting from a customer over their lifetime ([LTV](customer-lifetime-value.md)) is greater than the
cost to acquire a customer ([CAC](customer-acquisition-cost.md)).

Those posts, and several others, focused on the importance of retaining
customers, and trying to get to “negative churn”. It is this negative churn
that now requires us to develop more complex measurements to understand
future cash flows.


### Traditional Churn and LTV {#traditional-churn-and-ltv}

max: churn is always about cohort.

we can use a simple formula to get at the average Customer Lifetime:

{{< figure src="/Users/max/SynologyDrive/OrgMode/org-roam/data/52/B0CE3D-5CCC-48F0-90B1-E43443628063/2021-07-31_00-04-41_img_5647529830e24.png" >}}

![](/Users/max/SynologyDrive/OrgMode/org-roam/data/52/B0CE3D-5CCC-48F0-90B1-E43443628063/2021-07-31_00-05-29_img_5647543adc00e.png)
(ARPA is the Average Revenue per Account)


### Why Dollar Retention Rate (DRR) is different to Customer Retention Rate (CRR) {#why-dollar-retention-rate--drr--is-different-to-customer-retention-rate--crr}

> Given there's 2 customers, customer A give 1K MRR, customer B give 5K MRR.
> If customer A lost, the CRR is 50%, but DRR is 17%;
> If custome A lost, and customer B given 7K [MRR](monthly-recurring-revenue.md), then the CRR is 50%, and
> DRR is -16%.

This points out an obvious fact: it is more important to retain your larger customers
than it is to retain your smaller customers.

<https://www.forentrepreneurs.com/why-churn-is-critical-in-saas/>


### CRR and DRR {#crr-and-drr}

CRR = 1 - [Customer Churn Rate](churn-rate.md)
DRR = 1 - [MRR Churn Rate](churn-rate.md)

Examples of DRR greater than 100% include: Zendesk: 123%, NewRelic 115%,
Box: 130%, Rally Software 127%.


### Negative Churn invalidates the LTV formula {#negative-churn-invalidates-the-ltv-formula}

Here’s a graph showing what would happen if you had a cohort of 100
customers that initially started paying you $100 a month, but each remaining customer increased their
payment by $5 every month. The monthly customer churn rate is 3%:
clip\_image013\_thumb.png


### Using DCF to account for Risk and Time Value of Money {#using-dcf-to-account-for-risk-and-time-value-of-money}

Given that so much of the customer value in this situation occurs way in the future, where there are
risks of the market changing, new competition, technology platform changes, etc. it makes sense that we
should factor in that risk in some way when computing LTV.


### True LTV: DCF applied to a Negative Churn Scenario {#true-ltv-dcf-applied-to-a-negative-churn-scenario}

LTV Formula
\\(LTV={ARPU}\times{Gross\ Margin\ \%}\times{(\frac{1}{1+K}+\frac{{G}\times{K}}{{(1-K)}^2})}\\)
Where G is the growth rate for the customers that have not churned
K is defined by the following formula: \\(K=(1-{customer\ churn\ rate})\times(1-discount\ rate))\\)


### What is the right Discount Rate? {#what-is-the-right-discount-rate}

All financial theory is consistent about one thing: every time managers spend
money they use capital, so they should be thinking about what that capital
costs the company.

There can be many sources of capital, and the weighted average of those
sources is called WACC ([Weighted Average Cost of Capital](20210731001723-weighted_average_cost_of_capital.md))

If we were looking at the true cost of capital, we’d suggest the following discount rates to use:

• 10% for public companies
• 15% for private companies that are scaling predictably (say above $10m in ARR, and growing
  greater than 40% year on year)
• 20-25% for private companies that have not yet reached scale and predictable growth

The earlier the stage of the startup and the greater the risk in the business,
the higher the discount.


### Impact of DCF on the LTV:CAC Ratio {#impact-of-dcf-on-the-ltv-cac-ratio}


### Introducing CORE – Cost of Retention and Expansion {#introducing-core-cost-of-retention-and-expansion}

Most readers will realize that it requires Account Managers time and effort
to retain customers, and additional sales effort to get expansion revenue.

When cimputing [Gross Margin](20210729011241-gross_margin.md) %, don't forget to include both [COGS](cost-of-goods-sold.md) and  [Cost of Retention and Expansion](20210731011818-cost_of_retention_and_expansion.md) (CORE)


### How to calculate CORE and Gross Margin % for an average customer {#how-to-calculate-core-and-gross-margin-for-an-average-customer}

\\(CORE=\frac{cost\ of\ account\ manager}{number\ of\ customers\ they\ can\ serve}+\frac{cost\ of\ an\ expansion\ sales\ rep}{number\ of\ customers\ they\ can\ serve}\\)

[Gross Margin](20210729011241-gross_margin.md) = ([ARPU](20210729003208-average_revenue_per_account.md) - ([COS](20210731012533-cost_of_serve.md) + [CORE](20210731011818-cost_of_retention_and_expansion.md))) / [ARPU](20210729003208-average_revenue_per_account.md)

COS: [Cost of Serve](20210731012533-cost_of_serve.md)


### Understanding the effectiveness of an Expansion Revenue Salesforce {#understanding-the-effectiveness-of-an-expansion-revenue-salesforce}

If you have dedicated sales people that only work on generating expansion
revenue, and they are in addition to the Account Managers, it will be
interesting to see what the CAC and LTV is for expansion revenue.


### The Real World is more Complicated! {#the-real-world-is-more-complicated}

All of the above formulae make some key assumptions that typically don’t hold
true in the real world:


#### Assumption 1: Your customers will churn in an exponential decay month after month. {#assumption-1-your-customers-will-churn-in-an-exponential-decay-month-after-month-dot}


#### Assumption 2: Your remaining customers will expand their revenue in a linear fashion {#assumption-2-your-remaining-customers-will-expand-their-revenue-in-a-linear-fashion}


#### Assumption 3: Your Gross Margin % will remain constant over time {#assumption-3-your-gross-margin-will-remain-constant-over-time}


### Revenue versus Billings {#revenue-versus-billings}


### Modeling the real world {#modeling-the-real-world}


### How should SaaS Startups react to this article {#how-should-saas-startups-react-to-this-article}

So recognize that the value in this analysis is to get enough accuracy to
make useful business decisions, such as what factors to look at to improve
profitability, which customer segments are most profitable, and which have
problems that need addressing, etc.


#### Make sure you have the data you need to understand Churn, Expansion and LTV {#make-sure-you-have-the-data-you-need-to-understand-churn-expansion-and-ltv}

build a database to track revenue by individual customer by month that can
be used with an analytics tool to analyze cohorts.
