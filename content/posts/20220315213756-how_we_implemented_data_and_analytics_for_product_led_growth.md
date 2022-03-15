+++
title = "How we implemented data and analytics for product-led growth"
author = ["Max Zhang"]
draft = false
+++

## How we implemented data and analytics for product-led growth {#how-we-implemented-data-and-analytics-for-product-led-growth}

[Mixpanel]({{<relref "20220315213851-mixpanel.md#" >}})’s [PLG]({{<relref "20210924095204-product_lead_growth.md#" >}}) approach to new business looks like this:

{{< figure src="/ox-hugo/2022-03-15_21-39-26_MXP-Blog-MixpanelsOwnDataStack-1920x800-new.png" >}}

From the data and analytics perspective, we needed to do two things to make this
process work:

-   We needed to track potential customers along all the paths they may take in the diagram above and route them to sales when appropriate with the right contextual information.
-   We needed to make data and analysis on how accounts are progressing through the entire diagram above available self-serve to everyone at Mixpanel.

The big challenge with implementing a PLG strategy is that you need to make use
of product data, marketing data, and sales data all together.


### Data infrastructure for PLG {#data-infrastructure-for-plg}

With that in mind, below is how we set up our data infrastructure.

{{< figure src="/ox-hugo/2022-03-15_21-42-24_Vijay-docs-1-2048x1274.png" >}}


### Problem 1: Identity resolution {#problem-1-identity-resolution}


#### Product data {#product-data}

<!--list-separator-->

-  Transactional data

<!--list-separator-->

-  Clickstream data


#### Sales data {#sales-data}


#### Marketing data {#marketing-data}


#### Tying them all together {#tying-them-all-together}

-   Transactional ≤≥ Clickstream ⇒ On signup, identify/alias your anonymous UUID to your user ID from the transactional database
-   Product ≤≥ Sales ⇒ Create/update a lead on signup and make sure to tag the user ID on the lead/contact
-   Sales ≤≥ Marketing ⇒ Most marketing tools already track marketing users to Salesforce leads and accounts


### Problem 2: Focus {#problem-2-focus}


#### Ideal customer profile (ICP) {#ideal-customer-profile--icp}

<!--list-separator-->

-  Domain is key


#### Getting to value {#getting-to-value}


### Conclusion {#conclusion}