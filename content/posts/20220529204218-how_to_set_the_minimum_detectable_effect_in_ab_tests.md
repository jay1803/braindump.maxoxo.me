+++
title = "How to set the Minimum Detectable Effect in AB-Tests"
author = ["Max Zhang"]
tags = ["ref"]
draft = false
+++

## How to set the [Minimum Detectable Effect]({{< relref "20220529204040-minimum_detectable_effect.md" >}}) in AB-Tests <span class="tag"><span class="ATTACH">ATTACH</span></span> {#how-to-set-the-minimum-detectable-effect--20220529204040-minimum-detectable-effect-dot-md--in-ab-tests}


### What does the Minimum Detectable Effect mean? {#what-does-the-minimum-detectable-effect-mean}

The [MDE]({{< relref "20220529204040-minimum_detectable_effect.md" >}}) is necessary to calculate the minimum required sample size, which is the number of observations that have to be collected. An AB-Test’s results must not be analyzed before this threshold has been reached.

The MDE is the minimum effect size that should be detected with a certain probability.


### Why the MDE matters {#why-the-mde-matters}

If you wanted to prove that the quality of 50% of the screws being produced was below standards, how many screws would you examine before drawing a conclusion? Probably less than if you wanted to prove that 2% of the screws are low quality.

The smaller the effect we’re interested in, the more samples we need to collect before drawing any conclusions.


### Controlling Risk and Costs with the MDE {#controlling-risk-and-costs-with-the-mde}

In some cases, having a very low MDE can thus be a waste of money and time. Imagine a product team is testing a very promising MVP on a marketplace website. Implementing the change is risky and would cost months of development work but could lead to a massive increase in user conversion. In this case, the team would need an uplift in the conversion rate of at least 5% to justify the costs. Setting a significantly lower MDE would thus not be necessary for the underlying cause and prolong the test unnecessarily (the test would be overpowered).

At the same time, we need to ensure that the AB-Test has the right statistical set up to detect an effect if there exists one. Let’s assume we conduct an experiment where we change the copy on our website’s Buy Now-button to increase the conversion rate. We only power our test to detect an increase in conversion rate by at least 50% with a certain probability. In this case, the test would be very likely not to deliver any significant results even if the change had a positive effect. We might wrongly conclude that the change doesn’t make a difference and decide to continue using the old copy (in this case, one speaks of underpowered tests).


### Setting an appropriate MDE {#setting-an-appropriate-mde}

[MDE]({{< relref "20220529204040-minimum_detectable_effect.md" >}}) highly depends on the use case.

Your minimum [MDE]({{< relref "20220529204040-minimum_detectable_effect.md" >}}) should be the smallest effect that would justify implementing the change that is being tested.

come up with an exact number? It comes down to a simple ROI calculation. Consider the following (very simplified) situation:

-   A team is validating an MVP to make users add travel insurance to their purchase on a travel website’s checkout.
-   The website registers 2000 bookings per day (730.000 per year).
-   The estimated net profit for insurance is 3$ per user.
-   Implementing the full feature would cost the team ca. 150 developer hours with, let’s say 500$ per hour, totaling up to 75.000$ (not considering any opportunity costs).

On a yearly basis, the website would have to sell 25.000 insurances to break even, equalling 3.42% of bookings adding insurance.

With the insurance conversion rate being the primary metric for the experiment, 3.42% would be a reasonable MDE. Any value lower than this would not be of interest to the team and would unnecessarily prolong the test’s duration.
