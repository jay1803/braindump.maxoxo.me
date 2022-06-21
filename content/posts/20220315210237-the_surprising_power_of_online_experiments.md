+++
title = "The Surprising Power of Online Experiments"
author = ["Max Zhang"]
tags = ["ref"]
draft = false
+++

## The Surprising Power of Online Experiments <span class="tag"><span class="ATTACH">ATTACH</span></span> {#the-surprising-power-of-online-experiments}


### Appreciate the Value of A/B Tests {#appreciate-the-value-of-a-b-tests}

In an [A/B Testing]({{< relref "20220108110426-a_b_test.md" >}}) the experimenter sets up two experiences: “A,” the control, is
usually the current system and considered the “champion,” and “B,” the
treatment, is a modification that attempts to improve something—the
“challenger.” Users are randomly assigned to the experiences, and key metrics
are computed and compared.

Any company that has at least a few thousand daily active users can conduct
these tests.


#### Tiny changes can have a big impact. {#tiny-changes-can-have-a-big-impact-dot}

In 2008 an employee in the United Kingdom made a seemingly minor suggestion:
Have a new tab (or a new window in older browsers) automatically open whenever a
user clicks on the Hotmail link on the MSN home page, instead of opening Hotmail
in the same tab. A test was run with about 900,000 UK users, and the results
were highly encouraging: The engagement of users who opened Hotmail increased by
an impressive 8.9%, as measured by the number of clicks they made on the MSN
home page. (Most changes to engagement have an effect smaller than 1%.) However,
the idea was controversial because few sites at the time were opening links in
new tabs, so the change was released only in the UK.


#### Experiments can guide investment decisions. {#experiments-can-guide-investment-decisions-dot}

faster is better, but could the value of an improvement be quantified? Should
there be three, 10, or perhaps 50 people working on that performance
enhancement?

The data showed that every 100-millisecond difference in performance had a 0.6%
impact on revenue.


### Build a Large-Scale Capability {#build-a-large-scale-capability}

At [Google]({{< relref "20220129140242-google.md" >}}) and [Bing]({{< relref "20220621235841-bing.md" >}}), only about 10% to 20% of experiments generate positive
results. At [Microsoft]({{< relref "20220117204930-microsoft.md" >}}) as a whole, one-third prove effective, one-third have
neutral results, and one-third have negative results.

Scientifically testing nearly every proposed idea requires an infrastructure:
instrumentation (to record such things as clicks, mouse hovers, and event
times), data pipelines, and data scientists.

A company’s experimentation personnel can be organized in three ways:


#### Centralized model. {#centralized-model-dot}


#### Decentralized model. {#decentralized-model-dot}


#### Center-of-excellence model. {#center-of-excellence-model-dot}

Small companies typically start with the centralized model or use a third-party
tool and then, after they’ve grown, switch to one of the other models.


### Address the Definition of Success {#address-the-definition-of-success}

Every business group must define a suitable (usually composite) evaluation
metric for experiments that aligns with its strategic goals.
Getting it right—coming up with an [Overall Evaluation Criterion]({{< relref "20220414173629-overall_evaluation_criterion.md" >}}) (OEC)—takes
thoughtful consideration and often extensive internal debate.
We recommend that the OEC be adjusted annually.

as Bing’s experience shows. Its key long-term goals are increasing its share of
search-engine queries and its ad revenue. Interestingly, decreasing the
relevance of search results will cause users to issue more queries (thus
increasing query share) and click more on ads (thus increasing revenue).
Obviously, such gains would only be short-lived, because people would eventually
switch to other search engines.


### Beware of Low-Quality Data {#beware-of-low-quality-data}

You need to allocate time and resources to validating the experimentation system
and setting up automated checks and safeguards. One method is to run rigorous
A/A tests—that is, test something against itself to ensure that about 95% of the
time the system correctly identifies no statistically significant difference.


### Avoid Assumptions About Causality {#avoid-assumptions-about-causality}

Because of the hype over big data, some executives mistakenly believe that
causality isn’t important.

Office users who get error messages also have lower attrition, because they too
tend to be heavy users. But does that mean that showing users more error
messages will reduce attrition? Hardly.

Clearly, observational studies cannot establish causality.

That said, we should point out that you don’t always have to know the “why” or
the “how” to benefit from knowledge of the “what.” This is particularly true
when it comes to the behavior of users, whose motivations can be difficult to
determine.


### CONCLUSION {#conclusion}
