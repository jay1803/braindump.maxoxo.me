+++
title = "The Cold Start Problem"
author = ["Max Zhang"]
draft = false
+++

## About {#about}

作者：[Andrew Chen]({{<relref "20211211004641-andrew_chen.md#" >}})


## Introduction {#introduction}


#### A Network of Networks {#a-network-of-networks}


#### Foundational Questions {#foundational-questions}


#### The Definitive Guide to Network Effects {#the-definitive-guide-to-network-effects}

[The Cold Start Problem](#org7ca091b) is the culmination of hundreds of interviews, three years
of research and synthesis, and nearly two decades of experience as an investor
and operator. It takes much of the knowledge and core concepts swirling inside
the technology industry and frames them in the context of the beginning, middle,
and end of a network’s life cycle. This is the core framework I’ll describe via
the major sections of this book, along with examples, and providing an
actionable road map for your own products.


## Part I: Network Effects {#part-i-network-effects}


### 1. What’s a Network Effect, Anyway? {#1-dot-what-s-a-network-effect-anyway}


#### The Billion Users Club {#the-billion-users-club}

the [Network Effect]({{<relref "20210313214856-network_effect.md#" >}}) can be defined by breaking the term into its constituent
parts—the “network” and the “effect.”

The “network” is defined by people who use the product to interact with each
other.
These networks are counterintuitive in that they connect people, but don’t own
the underlying assets.

The “effect” part of the network effect describes how value increases as more
people start using the product.

The questions to ask are simple: First, does the product have a network?
And second, does the ability to attract new users, or to become stickier, or to
monetize, become even stronger as its network grows larger?


#### Launching New Tech Products Today Is Incredibly Challenging {#launching-new-tech-products-today-is-incredibly-challenging}

The technology ecosystem is downright hostile to new products—competition is
fierce, copycats abound, and marketing channels are ineffective.


### 2. A Brief History {#2-dot-a-brief-history}


#### The Dot-Com Boom {#the-dot-com-boom}


#### [Metcalfe's Law]({{<relref "20211230125549-metcalfe_s_law.md#" >}}) {#metcalfe-s-law--20211230125549-metcalfe-s-law-dot-md}

<a id="org602eb31">Metcalfe's Law</a>
 The law is defined below: The systemic value of compatibly communicating
 devices grows as a square of their number.

Said plainly, each time a user joins an app with a network behind it, the value
of the app is increased to n^2. That means if a network has 100 nodes and then
doubles to 200, its value more than doubles—it quadruples.


#### Metcalfe’s Flaws {#metcalfe-s-flaws}

Metcalfe’s Law is a simple, academic model that fails the test of real-life
messiness.


#### Meerkat’s Law {#meerkat-s-law}

Yes, it’s true: social animals have network effects, too.


#### The Math of Meerkats {#the-math-of-meerkats}

Allee threshold—where the animals would be safer and thus ultimately grow
faster as a population. In other words, Allee’s population curves describe a
sort of ecological version of the network effect.

As the population increases, eventually there is a natural limit based on the
environment—often called a carrying capacity. For social animals like meerkats
and goldfish, overpopulation looks like this, starting flat, then hitting a
[tipping point](#orge9a41cd) before growing quickly and then saturating and falling once again:


#### When Populations (and Networks) Collapse {#when-populations--and-networks--collapse}


#### The Allee Curve at Uber {#the-allee-curve-at-uber}


#### Meerkat’s Law versus Metcalfe’s Law {#meerkat-s-law-versus-metcalfe-s-law}

While the terms are different, the core concepts and the math are the same: The
Allee effect → The Network Effect Allee Threshold → [Tipping Point](#orge9a41cd) Carrying
capacity → Saturation


### 3. Cold Start Theory {#3-dot-cold-start-theory}


#### The Framework {#the-framework}

I call this framework [Cold Start Theory]({{<relref "20211211012938-cold_start_theory.md#" >}}), named for the first and most important
stage in building network effects.

There are five primary stages:

1.  [The Cold Start Problem](#org7ca091b)
2.  [Tipping Point](#orge9a41cd)
3.  [Escape Velocity](#org16c130f)
4.  [Hitting the Ceiling](#org5c7dbbe)
5.  [The Moat](#orgf6434c3)


#### 1. [The Cold Start Problem](#org7ca091b) {#1-dot}

<a id="org7ca091b">The Cold Start Problem</a>
Solving [the Cold Start Problem](#org7ca091b) requires getting all the right users and content
on the same network at the same time—which is difficult to execute in a launch.

<a id="org6ddbd91">Atomic Network</a> [Atomic Network]({{<relref "20211230134314-atomic_network.md#" >}})
focuses on building an “[atomic network](#org6ddbd91)”—that is, the smallest possible network
that is stable and can grow on its own.


#### 2. [Tipping Point](#orge9a41cd) {#2-dot}

<a id="orge9a41cd">Tipping Point</a>
as a network grows, each new network starts to tip faster and faster, so that
the entire market is more easily captured.

To win a market, it’s important to build many, many more networks to expand into
the market.


#### 3. [Escape Velocity](#org16c130f) {#3-dot}

<a id="org16c130f">Escape Velocity</a>
The [Escape Velocity](#org16c130f) stage is all about working furiously to strengthen network
effects and to sustain growth.

the Engagement Effect, which increases interaction between users as networks fill in

the Economic Effect, which improves monetization levels and conversion rates as
the network grows.

I redefine it so that it’s not one singular effect, but rather, three distinct,
underlying forces: the Acquisition Effect, which lets products tap into the
network to drive low-cost, highly efficient user acquisition via viral growth


#### 4. [Hitting the Ceiling](#org5c7dbbe) {#4-dot}

<a id="org5c7dbbe">Hitting the Ceiling</a>
This is driven by a variety of forces, starting with customer acquisition costs
that often spike due to market saturation, and as viral growth slows down


#### 5. [The Moat](#orgf6434c3) {#5-dot}

<a id="orgf6434c3">The Moat</a>
The final stage of the framework focuses on using network effects to fend off
competitors, which is often the focus as the network and product matures.


#### Five Stages {#five-stages}

This is the Cold Start Theory. It is made up of five stages for creating,
scaling, and defending the network effect, and aims to provide a road map for
any new product team—at a startup or larger company—to leverage in their work.

Cold Start Theory is meant to apply to a large set of companies in the
technology industry: video platforms, marketplaces, workplace collaboration
tools, bottom-up SaaS products, social networks and communications apps, and
more.

Many of these ideas generalize beyond the world of mobile apps, as my friend
Naval Ravikant, a noted investor and entrepreneur, has observed: Humans are the
networked species. Networks allow us to cooperate when we would otherwise go it
alone. And networks allocate the fruits of our cooperation. Money is a network.
Religion is a network. A corporation is a network. Roads are a network.
Electricity is a network.


## Part II: [The Cold Start Problem](#org7ca091b) {#part-ii}


### 4. Tiny Speck {#4-dot-tiny-speck}

When you start a new product with network effects, the first step is to build a
single, tiny network that’s self-sustaining on its own

The second step was a private beta-testing period with friends of the company,
where Stewart would personally reach out, try to get them to use Slack, and
iterate to add features and improve the experience.

Each of these beta customers formed an [atomic network](#org6ddbd91)—a stable, self-sustaining
group of users who can drive a network effect


#### Introducing the Cold Start {#introducing-the-cold-start}

It’s a myth that network effects are all powerful and positive forces—quite the
opposite.

because when people show up to a product and none of their friends or coworkers
are using it, they will naturally leave. What solves this? “The [Atomic
Network](#org6ddbd91)”—the smallest network where there are enough people that everyone will
stick around

These networks often have “sides,” whether they are buyers and sellers, or
content creators and consumers. Generally one side of the network will be easier
to attract—this is the easy side of the network

The Hard Side” of a network—the small percentage of people that typically end up
doing most of the work within the community
To attract the hard side, you need to “Solve a Hard Problem”—design a product
that is sufficiently compelling to the key subset of your network

When [the Cold Start Problem](#org7ca091b) is solved, a product is able to consistently create
“Magic Moments.” Users open the product and find a network that is built out,
meaning they can generally find whoever and whatever they’re looking for. The
network effects kick in, and the market hits its [Tipping Point](#orge9a41cd) as users start
coming to you.


### 5. [Anti-Network Effects](#org7e7419c) {#5-dot}

<a id="org7e7419c">Anti-Network Effects</a> [Anti-Network Effect]({{<relref "20211230131646-anti_network_effect.md#" >}})
[Anti-network effects](#org7e7419c) are the negative force that drives new networks to zero.

For Slack, it doesn’t make sense to use the product until your colleagues are
also on the platform. For Uber, you can’t use the service until there are
enough drivers, who won’t drive until there are enough rides.


#### What’s Enough? {#what-s-enough}

Stewart Butterfield, CEO of [Slack]({{<relref "20211230134357-slack.md#" >}}), answered this question for me: Slack works
with just 2 people, but it takes 3 to make it really work. There are
long-running 3 person groups that are stable—that’s the minimum required to be
called a customer.

for Slack it was approximately 2,000 messages—where they’ll stick around and
keep using the product:

How many users does your network need before the product experience becomes
good? The companies to do an analysis on the size of their networks (on the
X-axis) plotted against a set of important engagement metrics (on the Y-axis).

Eric Yuan, CEO of [Zoom]({{<relref "20211230134512-zoom.md#" >}}), said to me: You just need two people. One who wants to
call someone else and have a conversation—that’s enough for Zoom to be useful
for both people and to have them keep using it.

Chris Nakutis Taylor, one of the early general managers at [Uber]({{<relref "20211230134558-uber.md#" >}}), describes their
importance: ETAs were always terrible to start. +15 min in some areas,
especially in the suburbs. There was another key metric. Get ETAs down under 3
min on average as quickly as possible while covering the whole city. If you
could get ETAs, unfulfilleds, and surge down quickly, you’ll have a healthy
market.

William Barnes, another early GM who was one of the first fifty employees and
launched Los Angeles, describes the early ad hoc calculation: The strategy was
“let’s get a bunch of cars on the road” and try and get their ETAs and the
request conversion rate (the % who purchase a ride) to reasonable levels. In LA
and other big cities, the goal was to try to get 15–20 concurrent online cars on
the road at the same time. LA’s launch was notoriously expensive because we
worked hard to get that all in West Hollywood at launch.

For new products, it’s important to have a hypothesis for the size of your
network even before you begin. Communication apps can be 1:1, so the network is
small, and you can plan accordingly. Contrast that to products that are highly
asymmetrical, with content creators and viewers, or marketplaces with buyers and
sellers—these are likely to require a much bigger number to hit the threshold,
and require a much bigger effort to get started. The size of an initial network
helps determine a launch strategy.


#### The Antidote to [the Cold Start Problem](#org7ca091b) {#the-antidote-to}

Solving [the Cold Start Problem](#org7ca091b) requires a team to launch a network and quickly
create enough density and breadth such that the user experience can improve in
leaps and bounds

Density and interconnectedness is key.

The solution to [the Cold Start Problem](#org7ca091b) starts by understanding how to add a
small group of the right people, at the same time, using the product in the
right way


### 6. The [Atomic Network](#org6ddbd91)—Credit Cards {#6-dot-the-credit-cards}

For companies like Uber that exist both offline and online, it might seem
obvious that a city-by-city approach is the right strategy. But there’s a
history of products like Tinder and Facebook growing from tight-knit college
communities, as well as B2B companies like Slack that grow team by team within a
larger company


#### Launching the First Credit Card {#launching-the-first-credit-card}

Credit cards have network effects for the same reasons that marketplaces do:
they aggregate consumers, merchants, and other financial institutions as a
multi-sided network


#### The [Atomic Network](#org6ddbd91) {#the}

It needs to have enough density and stability to break through early
[anti-network effects](#org7e7419c), and ultimately grow on its own

Many of them are counterintuitive: The networked product should be launched in
its simplest possible form—not fully featured—so that it has a dead simple value
proposition


#### Why Starting with a Niche Works {#why-starting-with-a-niche-works}

Chris Dixon, my colleague at [a16z]({{<relref "20211211010432-andreessen_horowitz.md#" >}}), summarized the idea in an essay titled,
appropriately, “The next big thing will start out looking like a toy.”

The next big thing will start out looking like it’s for a niche network.


#### Picking Your [Atomic Network](#org6ddbd91) {#picking-your}

maybe on the order of hundreds of people, at a specific moment in time.

My advice: Your product’s first [atomic network](#org6ddbd91) is probably smaller and more
specific than you think.

The general managers and Driver Operations had an internal tool, called
Starcraft—referring to the real-time strategy game popular at the time—that
allowed them to click on a group of cars, text them “Go to the train, lots of
riders!” and direct them in real time.


#### The Power of Atomic Networks {#the-power-of-atomic-networks}

Growing city by city, campus by campus, or team by team is a surprisingly
powerful strategy


### 7. The Hard Side—Wikipedia {#7-dot-the-hard-side-wikipedia}


#### The Volunteers Who Built Wikipedia {#the-volunteers-who-built-wikipedia}

Even though there are hundreds of millions of users, there are only about
100,000 active contributors per month

This relationship exists everywhere.
There are nearly 100 million riders on Uber, but just a few million drivers


#### The Easy Side versus the Hard Side {#the-easy-side-versus-the-hard-side}

Hard sides exist because there are tasks in any networked product that just
require more work, whether that’s selling products, organizing projects, or
creating content. Users on the hard side have complex workflows, expect status
benefits as well as financial outcomes, and will try competitive products to
compare.

the hard side of the network is game developers.

the hard side of the network creates a ton more value. At the extreme
like Valve’s Steam

Consumers are generally the easy side of a network
In a less extreme example of value creation, the best Uber drivers will work
many times more hours than the average driver


#### The Hard Side of Social Content Apps {#the-hard-side-of-social-content-apps}

In a widely read essay called “Creators, Synthesizers, and Consumers,” Bradley
Horowitz, now a vice president of product at Google, described the 1 percent of
users who create versus everyone else: 1% of the user population might start a
group (or a thread within a group) 10% of the user population might participate
actively, and actually author content whether starting a thread or responding to
a thread-in-progress 100% of the user population benefits from the activities of
the above groups (lurkers)

<a id="orgd490d9c">1/10/100 rule</a> [1-10-100 Rule]({{<relref "20211230135106-1_10_100_rule.md#" >}})
the 1 percent of highly engaged users is extremely valuable.

there is a “power law” curve where the 20 percent of top influencers and content
creators end up with the vast majority of engagement.

Evan Spiegel, CEO and cofounder of [Snap]({{<relref "20211230135143-snap.md#" >}}), described his understanding of the
content creation pyramid for Snap and [Instagram]({{<relref "20211230135201-instagram.md#" >}}), versus [TikTok]({{<relref "20211230135233-tiktok.md#" >}}): You can imagine
a pyramid, if you will, of internet technology or communications technology,
where the base of the pyramid—the very broad base—is self-expression and
communication. And that’s what [Snapchat]({{<relref "20211230135303-snapchat.md#" >}}) is really about. Talking to your
friends, which is something everyone is comfortable doing. They just express how
they feel. As the pyramid gets narrower, you have the next layer, which is
status. Social media in its original construct is really about status,
representing who you are, showing people that you’re cool, getting likes and
comments. Those sorts of things. And that’s less accessible to the broad base of
humanity, and has a narrower base of appeal. [There’s a] more limited frequency
of engagement, because people only do some things that are cool once a week or
once a month, and not every day. At the top of the pyramid, which I think is
represented by TikTok, is really talent. People who have spent a couple hours
learning a new dance, or think about a funny new creative way to tell a story.
They’re really making media to entertain other people. I think that’s even
narrower.

The more difficult the work needed to be part of the hard side of a network, the
smaller the percentage of users who will participate.

The social feedback loop is a core concept because the creator/viewer network is
so ubiquitous as a network structure.

it’s all about the content creators.
It’s important to focus on this tiny slice of users so that messaging, product
functionality, and business model are all aligned to serve them.


#### Wikipedia’s Teeny, Tiny Hard Side {#wikipedia-s-teeny-tiny-hard-side}


### 8. Solve a Hard Problem—[Tinder]({{<relref "20211230135552-tinder.md#" >}}) {#8-dot-solve-a-hard-problem-tinder--20211230135552-tinder-dot-md}

The answer is by building a product that solves an important need for the hard side.


#### The Problem of Too Many Love Letters {#the-problem-of-too-many-love-letters}

[Tinder]({{<relref "20211230135552-tinder.md#" >}})’s cofounder, Sean Rad, about how Tinder innovated on the previous
generation of products. He described the combination of new ideas: The older
dating sites made it feel like you were doing work, like you were inside the
office. You’d go and do work emails during the day, then go home and write more
messages at night. Only to prospective dates rather than work colleagues. Tinder
was different—it made dating fun. You could sign up without filling in a bunch
of forms. It’s visual, you just swipe back and forth, and you could take five
minutes to do it while you were waiting in line or something like that. It’s a
form of entertainment.

Tinder started by making everyone connect their [Facebook]({{<relref "20211230140824-facebook.md#" >}}), so that we could show
the number of mutual friends you had, which built trust


#### The Hard Side for Marketplaces Is Usually the Supply Side {#the-hard-side-for-marketplaces-is-usually-the-supply-side}

For marketplaces, the hard side is usually the “supply” side of the network,
which refers to the workers and small businesses who provide the time, products,
and effort and are trying to generate income on the platform


#### Nights and Weekends {#nights-and-weekends}

how do you find a problem where the hard side of a network is engaged, but their
needs are unaddressed? The answer is to look at hobbies and side hustles.

What people are doing on their nights and weekends represents all the
underutilized time and energy in the world.

But once an [atomic network](#org6ddbd91) is established, the hard side of the network is
willing to extend their offerings and services to go into the next vertical.


#### The Hard Side of Dating Apps {#the-hard-side-of-dating-apps}


### 9. The Killer Product—[Zoom]({{<relref "20211230134512-zoom.md#" >}}) {#9-dot-the-killer-product-zoom--20211230134512-zoom-dot-md}


#### Networked Products versus Everything Else {#networked-products-versus-everything-else}


#### Why Networked Products Love to Be Free {#why-networked-products-love-to-be-free}


#### New Shifts in Behaviors and Computer Platforms {#new-shifts-in-behaviors-and-computer-platforms}


### 10. Magic Moments—[Clubhouse]({{<relref "20211230135617-clubhouse.md#" >}}) {#10-dot-magic-moments-clubhouse--20211230135617-clubhouse-dot-md}

This is the Magic Moment, when a product can deliver its core value
A product that hasn’t yet solved its Cold Start Problem will fail to deliver any
magic in its early days.


#### The Clubhouse Story {#the-clubhouse-story}


#### The Opposite of the Magic Moment {#the-opposite-of-the-magic-moment}


#### After [the Cold Start Problem](#org7ca091b) {#after}


## Part III: The [Tipping Point](#orge9a41cd) {#part-iii-the}

“[Tipping Point](#orge9a41cd),” when a product can quickly grow to take over the whole market.


### 11. [Tinder]({{<relref "20211230135552-tinder.md#" >}}) {#11-dot-tinder--20211230135552-tinder-dot-md}


#### USC Campus, 2012 {#usc-campus-2012}

The [Tinder]({{<relref "20211230135552-tinder.md#" >}}) team built one [atomic network](#org6ddbd91), but soon figured out how to build the
next one—just throw another party


#### Introducing the [Tipping Point](#orge9a41cd) {#introducing-the}


### 12. Invite-Only—[Linkedin]({{<relref "20211230140014-linkedin.md#" >}}) {#12-dot-invite-only-linkedin--20211230140014-linkedin-dot-md}

Yet this constraint is at the heart of the so called “invite-only” strategy for
launching a product. And for [Gmail]({{<relref "20211230141004-gmail.md#" >}}), [Linkedin]({{<relref "20211230140014-linkedin.md#" >}}), [Facebook]({{<relref "20211230140824-facebook.md#" >}}), and many other networked
products, it has worked. Why?

Invite mechanics work like a copy-and-paste feature—if you start with a curated
network, and give them invites, that network will copy itself over and over
automatically.

[Linkedin]({{<relref "20211230140014-linkedin.md#" >}}) thus adopted a more flexible positioning as a professional networking
service


#### The Welcome Experience {#the-welcome-experience}

Invite-only mechanics provide a better “welcome experience” for new users as
well. To explain why, imagine arriving at a large dinner party. A good friend
welcomes you at the door, and as you step in, you see acquaintances, close
friends, and a number of new people who’ve been curated to be absolutely
fascinating

Mathematically, it tends to work even better than that—the most connected people
tend to be invited earlier, and in turn they tend to invite other highly
connected people


#### Hype and Exclusivity {#hype-and-exclusivity}

You might ask, if invite-only is so great, why isn’t it used more often? There
are good reasons. It’s often seen as risky, because it can kill the top-line
growth rate of your product. It requires you to build a lot of extra
functionality, so that people who newly sign up are connected properly with
people around them


#### Curating a High-Quality Network {#curating-a-high-quality-network}


#### How Invite-Only Products Curate Their Networks {#how-invite-only-products-curate-their-networks}


### 13. Come for the Tool, Stay for the Network—[Instagram]({{<relref "20211230135201-instagram.md#" >}}) {#13-dot-come-for-the-tool-stay-for-the-network-instagram--20211230135201-instagram-dot-md}

Come for the tool, stay for the network” is one of the most famous strategies
for launching and scaling networks. Start with a great “tool”—a product
experience that is useful even for one user as a utility

Importantly, [Instagram]({{<relref "20211230135201-instagram.md#" >}}) was built with a network from day one. It had user
profiles, a feed, friend requests, invitations, and many other features of a
modern social product

A recent analysis has shown that the vast majority of photos—82 percent—had no
filter used at all. Eight years after its initial launch, network effects had
fully taken over for the utility of photo editing—it’s more network, and less
tool


#### How Great Tools Help Tip Entire Markets {#how-great-tools-help-tip-entire-markets}

“Come for the tool, stay for the network” circumvents [the Cold Start Problem](#org7ca091b) and
makes it easier to launch into an entire network—with PR, paid marketing,
influencers, sales, or any number of tried-and-true channels

Marketplaces are generally networks, not tools, from the start. But for a large
class of products centered on content creation, organization, and reference, it
can be a winning strategy


#### Underlying Patterns for Tools and Networks {#underlying-patterns-for-tools-and-networks}

Each provides a tool oriented around content editing and hosting—whether that’s
a video, photos, resumes, or documents. The tool is combined with a network that
allows people to interact with the content and by extension, other people.

Group a few other products that have a tool/network pairing, and some clusters
start to emerge:


#### Why This Strategy Works, and When It Doesn’t {#why-this-strategy-works-and-when-it-doesn-t}

Next I will discuss how, for some products, you can just go at it direct: use
money. Pay up for the launch, and subsidize usage of the network until it starts
to work. It’s expensive, but it can work.


### 14. Paying Up for Launch—[Coupons]({{<relref "20211230140052-coupons.md#" >}}) {#14-dot-paying-up-for-launch-coupons--20211230140052-coupons-dot-md}

eventually want to figure profitability out. But for networked products, in the
earliest stages, sometimes it makes sense to spend—often wildly—to pay up for
growth. The goal is to get the market to hit the [Tipping Point](#orge9a41cd), driving toward
strong positive network effects, and then pull back the subsidies

[Coca-Cola ]({{<relref "20211230141352-coca_cola.md#" >}})was soon flowing in every state across the country

Coupons were invented in 1888 by John Pemberton and Asa Candler, cofounders of
the Coca-Cola Company

The common wisdom was, “If you have a chicken and egg problem—buy the chicken.”

The next part of scaling the initial traction was to recruit a lot more drivers.
This is where the power of leveraging the network helped tremendously using
referral programs

referral programs (“Give $200, get $200 when a friend signs up to drive”)
over time structures like “Do 10 trips and get an extra $1 per trip”


### 15. Flintstoning—[Reddit]({{<relref "20211230140102-reddit.md#" >}}) {#15-dot-flintstoning-reddit--20211230140102-reddit-dot-md}

[Reddit]({{<relref "20211230140102-reddit.md#" >}}) is a perfect example of how [Flintstoning]({{<relref "20211231133355-flintstoning.md#" >}}) can be used early, and how it
evolves from manual work into automation at scale

a16z is an investor in Reddit, and over the years, I’ve gotten to know Steve and
the team

All of these dummy accounts looked and acted like real users


#### Flintstoning the Hard Side of the Network {#flintstoning-the-hard-side-of-the-network}

[Reddit]({{<relref "20211230140102-reddit.md#" >}})’s use of Flintstoning is similar to the strategy used by companies like
Yelp and Quora—to fill in the hard side of the network, which were also content
creators

Services like [DoorDash]({{<relref "20211231132728-doordash.md#" >}}) and [Postmates]({{<relref "20211231132752-postmates.md#" >}}) Flinstoned by showing a large selection of
restaurants, regardless of whether those restaurants had actually signed up

[B2B ]({{<relref "20211231132832-business_to_business.md#" >}})marketplaces exist in real estate, freight, labor, and many other large
multibillion-dollar industries, spawning billion-dollar startups like [Flexport]({{<relref "20211231133040-flexport.md#" >}})
and [Convoy]({{<relref "20211231133130-convoy.md#" >}})

but the first few years are just people powered.

<a id="org996d492">Cyborg Startups</a> [Cyborg Startup]({{<relref "20211231133225-startup.md#definition" >}})
“[cyborg startups](#org996d492),” because they combine humans (who are executing tasks
manually) with a team of software engineers who automate as much as they can
over time


#### Automation Can Scale Flintstoning {#automation-can-scale-flintstoning}

[Flintstoning]({{<relref "20211231133355-flintstoning.md#" >}}) can be thought of as a spectrum: Fully manual, human-powered efforts
Hybrid, where software suggests actions to take, but people are in the loop
Automated, powered by algorithms

Famously, PayPal built bots that would automatically buy and sell items on eBay,
but insist on transacting only with PayPal


#### The Extreme—Platforms and Their Applications {#the-extreme-platforms-and-their-applications}

Ideally, outside game developers will build for the new platform, but they often
don’t know how to take advantage of the new functionality

To break through this Cold Start Problem, Nintendo spared no expense in the
Switch launch, simultaneously releasing the latest installments of their classic
Mario and Zelda franchises—each have sold tens of millions of units

The games industry calls this “first-party content,” and it can be a serious
investment. Over the years, Microsoft Xbox has taken this strategy to an
extreme, buying a large number of studios and bringing them in-house.

this isn’t a common strategy for social networks, it’s also not crazy. In recent
years, we’ve seen players like YouTube in video and Spotify in podcasts begin to
license and create more first-party content to accelerate their services.


#### Exit Strategy {#exit-strategy}

In other words, once [the Cold Start Problem](#org7ca091b) is solved, it’s important to let the
network grow and stand up on its own—and turn off Flintstoning entirely.


### 16. Always Be Hustlin’—[Uber]({{<relref "20211230134558-uber.md#" >}}) {#16-dot-always-be-hustlin-uber--20211230134558-uber-dot-md}

Travis would regularly say to the product teams, “Product can solve problems,
but it’s slow. Ops can do it fast.”


#### The Importance of Creativity {#the-importance-of-creativity}

the Ops team would call local limo service companies one by one


#### Hustle as a System {#hustle-as-a-system}

A driver referral program like “Give $200, Get $200” could be bumped up and
turned into a New Year’s branded “Start your new year right—Give $300, Get $300”
campaign

In the end, you might ask—did Uber Ice Cream really help? As an individual
stunt, it may not have had a massive impact on the company

Most important, Uber created a system to quickly identify, execute, and iterate
on these concepts—it was supported by an entrepreneurial team culture, robust
software tooling, and an understanding that each city would be its own Cold
Start Problem.


#### Enterprise Hustle {#enterprise-hustle}

In a research study called “How today’s fastest growing B2B businesses found
their first ten customers,” startup veteran Lenny Rachitsky interviewed early
members of teams from Slack, Stripe, Figma, and Asana.

It’s a huge advantage to have a strong personal network in B2B, which you can
also build by bringing a connector investor or joining an incubator such as YC.
Getting press is rarely the way to get started

many productivity products begin by launching within online communities—like
[Twitter]({{<relref "20211231134400-twitter.md#" >}}), [Hacker News]({{<relref "20211231134430-hacker_news.md#" >}}), and [Product Hunt]({{<relref "20211231134452-product_hunt.md#" >}})—where dense pockets of early adopters are
willing to try new products. In recent years, [B2B]({{<relref "20211231132832-business_to_business.md#" >}}) products have started to
emphasize memes, funny videos, invite-only mechanics, and other tactics
traditionally associated with consumer startups

One of the most common types of advice we give at Y Combinator is to do things
that don’t scale. . . . The most common unscalable thing founders have to do at
the start is to recruit users manually. Nearly all startups have to. You can’t
wait for users to come to you. You have to go out and get them.

Graham goes on to cite examples from Stripe and Meraki as well as consumer
startups like Facebook and Airbnb, which employed this philosophy.


#### The Gray Area {#the-gray-area}

Dropbox’s folder sharing features were used early on for pirating movies and
music

When this happens, do you try to fix the loopholes or add more controls,
potentially impacting the usability of the product

Like many Cold Start examples, embracing the gray area created issues in the
early days


#### Uber 1.0 Cultural Values {#uber-1-dot-0-cultural-values}

[Uber]({{<relref "20211230134558-uber.md#" >}}) 1.0 Cultural Values:

-   Make Magic
-   Superpumped
-   Inside Out
-   Be an Owner, Not a Renter
-   Optimistic Leadership
-   Be Yourself
-   Big Bold Bets
-   Customer Obsession
-   Always Be Hustlin’
-   Let Builders Build Winning: Champion’s
-   Mindset Principled Confrontation Meritocracy and Toe-Stepping Celebrate Cities


## Part IV: [Escape Velocity](#org16c130f) {#part-iv}


### 17. [Dropbox]({{<relref "20211230140136-dropbox.md#" >}}) {#17-dot-dropbox--20211230140136-dropbox-dot-md}


### 18. The Trio of Forces {#18-dot-the-trio-of-forces}


### 19. The Engagement Effect—[Scurvy]({{<relref "20211230140201-scurvy.md#" >}}) {#19-dot-the-engagement-effect-scurvy--20211230140201-scurvy-dot-md}


### 20. The Acquisition Effect—[PayPal]({{<relref "20211230140212-paypal.md#" >}}) {#20-dot-the-acquisition-effect-paypal--20211230140212-paypal-dot-md}


### 21. The Economic Effect—[Credit Bureaus]({{<relref "20211230140236-credit_bureaus.md#" >}}) {#21-dot-the-economic-effect-credit-bureaus--20211230140236-credit-bureaus-dot-md}


## Part V: The Ceiling {#part-v-the-ceiling}


### 22. [Twitch]({{<relref "20211230140303-twitch.md#" >}}) {#22-dot-twitch--20211230140303-twitch-dot-md}


### 23. Rocketship Growth—[T2D3]({{<relref "20211230140317-t2d3.md#" >}}) {#23-dot-rocketship-growth-t2d3--20211230140317-t2d3-dot-md}


### 24. Saturation—[eBay]({{<relref "20211227192834-ebay.md#" >}}) {#24-dot-saturation-ebay--20211227192834-ebay-dot-md}


### 25. The Law of Shitty Clickthroughs—[Banner Ads]({{<relref "20211230140345-banner_ads.md#" >}}) {#25-dot-the-law-of-shitty-clickthroughs-banner-ads--20211230140345-banner-ads-dot-md}


### 26. When the Network Revolts—[Uber]({{<relref "20211230134558-uber.md#" >}}) {#26-dot-when-the-network-revolts-uber--20211230134558-uber-dot-md}


### 27. Eternal September—Usenet 28. Overcrowding—[YouTube]({{<relref "20211230140354-youtube.md#" >}}) {#27-dot-eternal-september-usenet-28-dot-overcrowding-youtube--20211230140354-youtube-dot-md}


## Part VI: [The Moat](#orgf6434c3) {#part-vi}


### 29. [Wimdu]({{<relref "20211230140440-wimdu.md#" >}}) versus [Airbnb]({{<relref "20211230140503-airbnb.md#" >}}) {#29-dot-wimdu--20211230140440-wimdu-dot-md--versus-airbnb--20211230140503-airbnb-dot-md}


### 30. Vicious Cycle, Virtuous Cycle {#30-dot-vicious-cycle-virtuous-cycle}


### 31. Cherry Picking—[Craigslist]({{<relref "20211230140524-craigslist.md#" >}}) {#31-dot-cherry-picking-craigslist--20211230140524-craigslist-dot-md}


### 32. Big Bang Failures—[Google+]({{<relref "20211230140535-google.md#" >}}) {#32-dot-big-bang-failures-google-plus--20211230140535-google-dot-md}


### 33. Competing over the Hard Side—[Uber]({{<relref "20211230134558-uber.md#" >}}) {#33-dot-competing-over-the-hard-side-uber--20211230134558-uber-dot-md}


### 34. Bundling—Microsoft Conclusion: The Future of Network Effects {#34-dot-bundling-microsoft-conclusion-the-future-of-network-effects}