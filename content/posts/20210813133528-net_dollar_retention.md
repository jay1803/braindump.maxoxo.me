+++
title = "Net Dollar Retention"
author = ["Max"]
draft = false
+++

## Definition {#definition}

NDR is a churn metric that calculates the percentage of recurring revenue
retained from existing customers over time.


### Calculation {#calculation}

\begin{equation}
{NDR}={\frac{Starting\ MRR\ +\ Expansion\ -\ Ccontraction\ -\ Churned}{Starting\ MRR}}\times{100}
\end{equation}

NDR = ((Starting [MRR]({{<relref "20210807103653-monthly_recurring_revenue.md#" >}}) + [Expansion MRR]({{<relref "20210807103653-monthly_recurring_revenue.md#net-mrr" >}}) - [Contraction MRR]({{<relref "20210807103653-monthly_recurring_revenue.md#net-mrr" >}}) - [Churn MRR]({{<relref "20210807103653-monthly_recurring_revenue.md#net-mrr" >}}))/(Starting [MRR]({{<relref "20210807103653-monthly_recurring_revenue.md#" >}}))) \* 100
