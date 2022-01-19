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

[The Cold Start Problem](#org4270a82) is the culmination of hundreds of interviews, three years
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

<a id="org736e9ec">Metcalfe's Law</a>
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
[tipping point](#org75e7f20) before growing quickly and then saturating and falling once again:


#### When Populations (and Networks) Collapse {#when-populations--and-networks--collapse}


#### The Allee Curve at Uber {#the-allee-curve-at-uber}


#### Meerkat’s Law versus Metcalfe’s Law {#meerkat-s-law-versus-metcalfe-s-law}

While the terms are different, the core concepts and the math are the same: The
Allee effect → The Network Effect Allee Threshold → [Tipping Point](#org75e7f20) Carrying
capacity → Saturation


### 3. Cold Start Theory {#3-dot-cold-start-theory}


#### The Framework {#the-framework}

I call this framework [Cold Start Theory]({{<relref "20211211012938-cold_start_theory.md#" >}}), named for the first and most important
stage in building network effects.

There are five primary stages:

1.  [The Cold Start Problem](#org4270a82)
2.  [Tipping Point](#org75e7f20)
3.  [Escape Velocity](#orgaa9feff)
4.  [Hitting the Ceiling](#org9c20d6f)
5.  [The Moat](#org726d630)


#### 1. [The Cold Start Problem](#org4270a82) {#1-dot}

<a id="org4270a82">The Cold Start Problem</a>
Solving [the Cold Start Problem](#org4270a82) requires getting all the right users and content
on the same network at the same time—which is difficult to execute in a launch.

<a id="org237b742">Atomic Network</a> [Atomic Network]({{<relref "20211230134314-atomic_network.md#" >}})
focuses on building an “[atomic network](#org237b742)”—that is, the smallest possible network
that is stable and can grow on its own.


#### 2. [Tipping Point](#org75e7f20) {#2-dot}

<a id="org75e7f20">Tipping Point</a>
as a network grows, each new network starts to tip faster and faster, so that
the entire market is more easily captured.

To win a market, it’s important to build many, many more networks to expand into
the market.


#### 3. [Escape Velocity](#orgaa9feff) {#3-dot}

<a id="orgaa9feff">Escape Velocity</a>
The [Escape Velocity](#orgaa9feff) stage is all about working
furiously to strengthen network
effects and to sustain growth.

the [Engagement Effect](#org1756e1b), which increases interaction between users as networks fill in

the [Economic Effect](#org70e005b), which improves monetization levels and conversion rates as
the network grows.

I redefine it so that it’s not one singular effect, but rather, three distinct,
underlying forces: the [Acquisition Effect](#orgea13efa), which lets products tap into the
network to drive low-cost, highly efficient user acquisition via viral growth


#### 4. [Hitting the Ceiling](#org9c20d6f) {#4-dot}

<a id="org9c20d6f">Hitting the Ceiling</a>
This is driven by a variety of forces, starting with customer acquisition costs
that often spike due to market saturation, and as viral growth slows down


#### 5. [The Moat](#org726d630) {#5-dot}

<a id="org726d630">The Moat</a>
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


## Part II: [The Cold Start Problem](#org4270a82) {#part-ii}


### 4. Tiny Speck {#4-dot-tiny-speck}

When you start a new product with network effects, the first step is to build a
single, tiny network that’s self-sustaining on its own

The second step was a private beta-testing period with friends of the company,
where Stewart would personally reach out, try to get them to use Slack, and
iterate to add features and improve the experience.

Each of these beta customers formed an [atomic network](#org237b742)—a stable, self-sustaining
group of users who can drive a network effect


#### Introducing the Cold Start {#introducing-the-cold-start}

It’s a myth that network effects are all powerful and positive forces—quite the
opposite.

because when people show up to a product and none of their friends or coworkers
are using it, they will naturally leave. What solves this? “The [Atomic
Network](#org237b742)”—the smallest network where there are enough people that everyone will
stick around

These networks often have “sides,” whether they are buyers and sellers, or
content creators and consumers. Generally one side of the network will be easier
to attract—this is the easy side of the network

The Hard Side” of a network—the small percentage of people that typically end up
doing most of the work within the community
To attract the hard side, you need to “Solve a Hard Problem”—design a product
that is sufficiently compelling to the key subset of your network

When [the Cold Start Problem](#org4270a82) is solved, a product is able to consistently create
“Magic Moments.” Users open the product and find a network that is built out,
meaning they can generally find whoever and whatever they’re looking for. The
network effects kick in, and the market hits its [Tipping Point](#org75e7f20) as users start
coming to you.


### 5. [Anti-Network Effects](#org56fa12c) {#5-dot}

<a id="org56fa12c">Anti-Network Effects</a> [Anti-Network Effect]({{<relref "20211230131646-anti_network_effect.md#" >}})
[Anti-network effects](#org56fa12c) are the negative force that drives new networks to zero.

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


#### The Antidote to [the Cold Start Problem](#org4270a82) {#the-antidote-to}

Solving [the Cold Start Problem](#org4270a82) requires a team to launch a network and quickly
create enough density and breadth such that the user experience can improve in
leaps and bounds

Density and interconnectedness is key.

The solution to [the Cold Start Problem](#org4270a82) starts by understanding how to add a
small group of the right people, at the same time, using the product in the
right way


### 6. The [Atomic Network](#org237b742)—Credit Cards {#6-dot-the-credit-cards}

For companies like Uber that exist both offline and online, it might seem
obvious that a city-by-city approach is the right strategy. But there’s a
history of products like Tinder and Facebook growing from tight-knit college
communities, as well as B2B companies like Slack that grow team by team within a
larger company


#### Launching the First Credit Card {#launching-the-first-credit-card}

Credit cards have network effects for the same reasons that marketplaces do:
they aggregate consumers, merchants, and other financial institutions as a
multi-sided network


#### The [Atomic Network](#org237b742) {#the}

It needs to have enough density and stability to break through early
[anti-network effects](#org56fa12c), and ultimately grow on its own

Many of them are counterintuitive: The networked product should be launched in
its simplest possible form—not fully featured—so that it has a dead simple value
proposition


#### Why Starting with a Niche Works {#why-starting-with-a-niche-works}

Chris Dixon, my colleague at [a16z]({{<relref "20211211010432-andreessen_horowitz.md#" >}}), summarized the idea in an essay titled,
appropriately, “The next big thing will start out looking like a toy.”

The next big thing will start out looking like it’s for a niche network.


#### Picking Your [Atomic Network](#org237b742) {#picking-your}

maybe on the order of hundreds of people, at a specific moment in time.

My advice: Your product’s first [atomic network](#org237b742) is probably smaller and more
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

<a id="org9a2758e">1/10/100 rule</a> [1-10-100 Rule]({{<relref "20211230135106-1_10_100_rule.md#" >}})
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

But once an [atomic network](#org237b742) is established, the hard side of the network is
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

[Clubhouse]({{<relref "20211230135617-clubhouse.md#" >}}) launched in 2020
Before Clubhouse, there were other apps focused on connecting people through
audio. Years before, Rohan had worked on Phone-a-friend, an app to connect
groups of friends over audio.
People could quickly start a podcast, record with hosts, edit, and publish, all
in the same app. Talkshow had all the tools in one place.
Talkshow, which made it much easier to produce podcasts. People could quickly
start a podcast, record with hosts, edit, and publish, all in the same app.
Talkshow had all the tools in one place.

how do you get to something magical faster?
they needed to radically simplify. To make sure creators had a lightweight
experience, it would be ideal to easily create content with people already
hanging out in the app—that way, it avoided the coordination problem of getting
your friends into an app at the same time.

Great products take time to figure out, and Clubhouse is no different. It was an
overnight success that took years.


#### The Opposite of the Magic Moment {#the-opposite-of-the-magic-moment}

The Magic Moment is a nice concept, but it would be even more useful if you
could measure it. The way to best do this might be surprising—you start with the
opposite of magic, the moments where the network has broken down, and you start
solving the problem from there.


#### After [the Cold Start Problem](#org4270a82) {#after}

When a networked product finally starts to generate Magic Moments, it feels
really good. Often, this is called [Product-Market Fit]({{<relref "20210806234604-product_market_fit.md#" >}}).


## Part III: The [Tipping Point](#org75e7f20) {#part-iii-the}

“[Tipping Point](#org75e7f20),” when a product can quickly grow to take over the whole market.


### 11. [Tinder]({{<relref "20211230135552-tinder.md#" >}}) {#11-dot-tinder--20211230135552-tinder-dot-md}


#### USC Campus, 2012 {#usc-campus-2012}

The answer to this conundrum was the University of Southern California, which in
many ways was an ideal place for Tinder to get started...Both Sean and Justin
had gone to USC, and more important, Justin had a younger sibling going to the
college at the time. And they concocted a plan: Tinder would work with Justin’s
younger brother to throw a birthday party for one of his popular, hyperconnected
friends on campus, and use it to promote Tinder.

> There was one catch with the party: First, you had to download the Tinder app to
> get in. We put a bouncer in the house to check that you had done it.

The [Tinder]({{<relref "20211230135552-tinder.md#" >}}) team built one [atomic network](#org237b742), but soon figured out how to build the
next one—just throw another party.


#### Introducing the [Tipping Point](#org75e7f20) {#introducing-the}

To begin the discussion of the [Tipping Point](#org75e7f20), I’ll start with a prominent
strategy, “Invite-Only,” that is often used to suck in a large network through
viral growth.

Another method to tip over a market is with a “Come for the Tool, Stay for the
Network” strategy.

some products can always just spend money to build out their network, with a
strategy of just “Paying Up for Launch.”

If the hard side of the network isn’t yet activated, a team can just fill in
their gaps themselves, using the technique of “Flintstoning”

In the end, all of these strategies require enormous creativity. And to close
out the [Tipping Point](#org75e7f20) section of the book, I introduce Uber’s core ethos of
“Always Be Hustlin’”—describing the creativity and decentralized set of teams,
all with its own strategies that were localized to each region.


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

[Hipstamatic]({{<relref "20220109154355-hipstamatic.md#" >}}) was created by two friends from Wisconsin, Ryan Dorshorst and Lucas
Buick, and showed the enormous appetite people would have for mobile photography
in the coming years. In 2010, in its inaugural “Apps of the Year,”

Importantly, [Instagram]({{<relref "20211230135201-instagram.md#" >}}) was built with a network from day one. It had user
profiles, a feed, friend requests, invitations, and many other features of a
modern social product.
[Instagram]({{<relref "20211230135201-instagram.md#" >}}) launched on October 6, 2010, to the App Store, and at the end of the
first week, it had been downloaded over 100,000 times.
Six months after the app’s launch, an article on Techcrunch by analytics firm RJ
Metrics analyzed data from Instagram’s APIs and concluded that 65 percent of
users were not yet following other people on the network.
in 2011, tennis player Serena Williams and singers [Drake]({{<relref "20220109154634-drake.md#" >}}), [Justin Bieber]({{<relref "20220109154706-justin_bieber.md#" >}}), and

[Britney Spears]({{<relref "20220109154723-britney_spears.md#" >}}) would all post their first photos. Popular Instagram accounts of
cute dogs, travel destinations, and models would eventually turn into the
“influencers” that would define the platform. These influencers, celebrities,
companies, meme accounts, and many others would all join to create content,
building network density and increasing engagement.

Similarly, over time, the “tool” part of the product—the photo filters—have
waned in importance, as users often post photos with the “#nofilter” tag. A
recent analysis has shown that the vast majority of photos—82 percent—had no
filter used at all. Eight years after its initial launch, network effects had
fully taken over for the utility of photo editing—it’s more network, and less
tool.


#### How Great Tools Help Tip Entire Markets {#how-great-tools-help-tip-entire-markets}

“Come for the tool, stay for the network” circumvents [the Cold Start Problem](#org4270a82) and
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
growth. The goal is to get the market to hit the [Tipping Point](#org75e7f20), driving toward
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

<a id="orge736c9f">Cyborg Startups</a> [Cyborg Startup]({{<relref "20211231133225-startup.md#definition" >}})
“[cyborg startups](#orge736c9f),” because they combine humans (who are executing tasks
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

In other words, once [the Cold Start Problem](#org4270a82) is solved, it’s important to let the
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
-   Let Builders Build
-   Winning: Champion’s Mindset
-   Principled Confrontation
-   Meritocracy and Toe-Stepping
-   Celebrate Cities


## Part IV: [Escape Velocity](#orgaa9feff) {#part-iv}


### 17. [Dropbox]({{<relref "20211230140136-dropbox.md#" >}}) {#17-dot-dropbox--20211230140136-dropbox-dot-md}

[Dropbox]({{<relref "20211230140136-dropbox.md#" >}}) had initially been built on [Amazon]({{<relref "20210822220641-amazon.md#" >}})’s cloud platform, and the product was
growing so fast that the hosting bills had become very expensive.

To kick off an effort to generate more revenue, a cross-functional Growth and
Monetization team was convened...growth teams have emerged across the industry
as a focused way to scale products toward [Escape Velocity](#orgaa9feff).
In parallel, the team began to explore the data, looking for critical insights
that made one user more valuable than another. Not every user is the same, nor
is every network the same.

Dropbox’s insights on this were profound: some users joined Dropbox as part of
the “come for the tool” strategy—but stayed with the tool without increasing
their engagement by sharing folders and documents with others. In contrast, the
ones who used Dropbox for collaboration and sharing—the network features—became
significantly more valuable over time. Dropbox’s users could be divided into
High-Value Actives (HVAs) and Low-Value Actives (LVAs), which was useful as a
quality indicator.

Data could be misleading sometimes, too. In the early days, Dropbox was growing
so fast that it was often hard to do analyses on what types of content people
were putting in their folders.

First, the team surveyed users and realized that many High-Value Actives were
upgrading their Dropbox accounts for use at work

The right question was: Which files did people tend to go back and edit or move,
again and again? What types of files did multiple users within a network tend to
share, collaboratively edit, and interact with?


#### Introducing [Escape Velocity](#orgaa9feff) {#introducing}

When new products see success and start to scale, it’s often called hitting
“[Escape Velocity](#orgaa9feff).
In the [Escape Velocity](#orgaa9feff) phase, the company needed to continue scaling the use
base, and ultimately build a real revenue-generating business.

To make it concrete enough for product teams to act upon, I argue that there are
a trio of network effects: Engagement, Acquisition, and Economics.

The <a id="org1756e1b">Engagement Effect</a> is what happens when a product gets stickier, and more
engaging, as more users join.

The <a id="org70e005b">Economic Effect</a> Network effects can help improve business models over
time, in the form of improved feed algorithms, increased conversion rates,
premium pricing, and more.

The <a id="orgea13efa">Acquisition Effect</a> on the other hand, is the network effect that powers
the acquisition of new customers into your product—in other words, viral growth.


### 18. The Trio of Forces {#18-dot-the-trio-of-forces}

[Escape velocity](#orgaa9feff) is often described as a kind of end state, the moment when a
product becomes dominant in the market, where everything gets easier.


#### Three Systems Underlying the Network Effect {#three-systems-underlying-the-network-effect}

the network effect is not one effect. Instead, the network effect is a broader
umbrella term that can be broken down into a trio of underlying forces:

-   the Acquisition network effect
-   the Engagement network effect
-   the Economic network effect

The “[Acquisition Effect]({{<relref "20220108105957-acquisition_effect.md#" >}})” is the ability for a product to tap into its network to
acquire new customers.

The “[Engagement Effect]({{<relref "20220108110020-engagement_effect.md#" >}})” describes how a denser network creates higher stickiness
and usage from its users—it is a more specific form of the classic description
of network effects that I covered at the beginning of the book, “the more users
that join the network, the more useful it gets.”
In turn, these elevated use cases drive key metrics, as more engagement directly
maps to number of sessions per user, or the number of days per month that you’re
active in the product.

The “[Economic Effect]({{<relref "20220108110033-economic_effect.md#" >}})” is the ability for a networked product to accelerate its
monetization, reduce its costs, and otherwise improve its business model, as its
network grows.

<!--list-separator-->

-  The Growth Accounting Equation

    I use Engagement, Acquisition, and Economic network effects as the core taxonomy
    for the reason that they map to the key outputs that product teams care most
    about: active users and revenue, and the leading indicators to these metrics.

    Gain or loss in active users = New + Reactivated − Churned

    This month’s actives = Last month’s actives + gain or loss


### 19. The [Engagement Effect](#org1756e1b)—[Scurvy]({{<relref "20211230140201-scurvy.md#" >}}) {#19-dot-the-scurvy--20211230140201-scurvy-dot-md}

In the modern usage, users are often divided into separate groups—called
cohorts—which then allow them to be measured separately.


#### The Sad Truth about the Stickiness of New Products {#the-sad-truth-about-the-stickiness-of-new-products}

[Retention]({{<relref "20210731183135-retention.md#" >}}) is the most critical metric in understanding a product, but most of
the time, the data is not pretty.

In collaboration with Ankit Jain, a former product manager at Google Play, I
published an essay titled “Losing 80% of mobile users is normal,” which
illustrated the rapid decay that happens right after a new user signs up to a
product.
Of the users who install an app, 70 percent of them aren’t active the next day,
and by the first three months, 96 percent of users are no longer active.
Data from analytics company comScore, revealed that people spend 80 percent with
just three apps51—and I’m sure you can guess which ones.

As a rough benchmark for evaluating startups at Andreessen Horowitz, I often
look for a minimum baseline of 60 percent retention after day 1, 30 percent
after day 7, and 15 percent at day 30, where the curve eventually levels out.

Their unique ability to tap into the Engagement network effect lets them drive
up retention over time—first, by creating new use cases as the network develops;
then by reinforcing the core “loop” of the product; and lastly, by reactivating
churned users. I’ll unpack how these levers work.

<!--list-separator-->

-  How New Use Cases Drive More Engagement

    The first lever comes from the [Engagement Effect](#org1756e1b)’s ability to raise retention
    curves by layering on use cases.

    As an example, when a small team first adopts a chat product like Slack—before
    the rest of the company does—they might just use a few channels to discuss items
    relevant to the team. But as more of the company also onboards employees onto
    the product, new use cases are unlocked.

    What starts as infrequent and noncommittal usage often deepens into daily usage.

    to do this, teams have to do what Dropbox did and find a way to segment higher
    versus lower value users. Monetary value might not be the right segmentation—it
    might be something else, like frequency, lifetime value, use cases, or some
    other defining characteristic.

    For example, [Linkedin]({{<relref "20211230140014-linkedin.md#" >}})’s user base was tiered based on frequent usage, as my good
    friend Aatif Awan—the former vice president of growth at LinkedIn—describes: At
    LinkedIn, we segmented our users as: Active the last 7 days out of the last week
    Active the last 6 days Active the last 5 days . . . and so on. This let us dig
    into each segment separately and understand their needs, motivations, and what
    it would take to move them up in engagement

    But it’s often not all the same lever—depending on the type of users, and their
    motivations and intent, different approaches will work. Awan describes this in
    the context of LinkedIn’s strategy to increase frequency:
    This is where the [A/B Test]({{<relref "20220108110426-a_b_test.md#" >}}) becomes so valuable. Just as James Lind did with her
    scurvy experiment, users can be randomly divided into separate cohorts and given
    different experiences. A correlation like “High-value LinkedIn users connect to
    other users at a higher rate than low-value users” can then be converted into a
    real lever.

    The question then becomes how to get these users to take the various actions
    that will make them higher value. This usually happens in the form of educating
    users.

    In Dropbox’s case, this segmentation revealed that a user who has installed the
    product across multiple devices—home and work computers, or on their mobile
    devices—is more valuable than someone who just has a single device and uses the
    service for backup.

<!--list-separator-->

-  Engagement Loops

    Engagement network effect makes products stickier over time, but how?

    <a id="org782e93d">Engagement Loop</a>
    describes how users derive value from others in a network in a step-by-step
    process.

    Users need to trust the loop to rely on it. If the network is too small or too
    inactive and the loop breaks, then users will be less likely to use it in the
    future.

    The [Escape Velocity](#orgaa9feff) phase is about accelerating these loops, by making each
    stage of the loop perform better.

<!--list-separator-->

-  Back from the Dead

    The Engagement network effect has the superpower of being able to [reactivate]({{<relref "20210902090220-user_reactivation.md#" >}})
    [Churned Customer]({{<relref "20210803120415-churn.md#dimensions" >}}), which in turn grows the active user count.

    data I’ve seen from startups, a typical product might only have 25–50 percent of
    its registered users active in any given month, expressed as a ratio of actives
    divided by signups.
    Traditional products that lack networks often struggle with this, because they
    rely on spammy emails, discounts, and push notifications to entice users back.
    A notification that a close friend just joined an app you tried a month ago is a
    lot more engaging than an announcement about new features. And the more dense
    the network is around a churned user, the more likely they are to receive this
    type of interaction.

<!--list-separator-->

-  The Impact of the [Engagement Effect](#org1756e1b)

    tech companies can reason by analogy: create user cohorts by levels of
    engagement, and analyze what differentiates high value users from lower value
    ones.


### 20. The [Acquisition Effect](#orgea13efa)—[PayPal]({{<relref "20211230140212-paypal.md#" >}}) {#20-dot-the-paypal--20211230140212-paypal-dot-md}

This is one of the most magical, explosive forces in the technology world: viral
growth.


#### The PayPal Mafia {#the-paypal-mafia}

One example is the embeddable player for YouTube

PayPal started with a product called FieldLink, which let people send and
receive money on Palm Pilots and other PDAs (personal digital assistants)
but importantly, no internet access
FieldLink was not going to work, and in the search for a new idea, PayPal was
born.

early days PayPal’s growth was still slow. The value proposition was vague,
since the web was still in its infancy. Users didn’t quite know why they would
pay each other—the product had not found its killer use case.
eBay PowerSeller changed all of that. The seller had designed a “We accept
PayPal” button by themselves, and asked to use it on their auction listings
There was natural virality emerging, and it was up to the team to supercharge it
The eBay community was a tight-knit network, and PayPal quickly spread. The
initial product had fewer than 10,000 users. Within a few months, PayPal had
100,000 users. A few months after that, 1 million. Within a year, 5 million

most viral products ever created—like WhatsApp—have been able to generate over 1
million installs per day, without paid marketing.

Viral growth builds on the power of networks to acquire users, often free of charge.


#### Product-Driven Viral Growth {#product-driven-viral-growth}

This is the Product/Network Duo at work again, where the product has features to
attract people to the network, while the network brings more value to the
product.


#### Amplifying the Viral Factor, One Step at a Time {#amplifying-the-viral-factor-one-step-at-a-time}

For example, consider this process: A new user hears about a service, signs up,
finds value in it, and shares the product with their friends/colleagues, who
also sign up. These new users then repeat the same steps—this is the viral loop.

Uber’s viral loop for drivers involved a referral program that was exposed
during the onboarding process.


#### Measuring the Acquisition Network Effect {#measuring-the-acquisition-network-effect}

1000 users download the new app. A percentage of these users invite their
colleagues and friends, and over the next month, 500 users download and sign
up—what happens next? Well, those 500 users then invite their friends, and get
250 to sign up, who create another 125 sign-ups, and so on.
Pay attention to the ratios between each set of users—1000 to 500 to 250. This
ratio is often called the viral factor, and in this case can be calculated at
0.5, because each cohort of users generates 0.5 of the next cohort
A higher ratio is better, since it means each cohort is more efficiently
bringing on the next batch of users

If you increase the viral factor of your product to 0.6, then the product will
2.5x the users you bring. At 0.7, then the product will 3.3x the users you
bring. The real magic starts to happen as the viral factor starts to approach 1.
After all, at a viral factor of 0.95, 1,000 users show up and then bring 950 of
their friends, who will then bring 900, and so on—ultimately the amplification
will be 20x. This is the mathematical expression of when a product “goes viral”
and starts growing incredibly fast.


#### Acquisition Can’t Exist without Engagement {#acquisition-can-t-exist-without-engagement}


#### The Impact of the [Acquisition Effect](#orgea13efa) {#the-impact-of-the}


### 21. The [Economic Effect](#org70e005b)—[Credit Bureaus]({{<relref "20211230140236-credit_bureaus.md#" >}}) {#21-dot-the-credit-bureaus--20211230140236-credit-bureaus-dot-md}


#### Credit Bureaus {#credit-bureaus}

Economic network effect, which is how a business model—including profitability
and unit economics—improves over time as a network grows.


#### The Network Effects of Lending {#the-network-effects-of-lending}

These bureaus tended to combine into larger bureaus over time because of what’s
often described as a “data network effect.” When a bureau works with more
merchants, it means more data, which means the risk predictions on loans will be
more accurate.


#### Efficiency over Subsidy {#efficiency-over-subsidy}

launching a new network often requires subsidies for the hard side, which are
paid back over time.

when Microsoft introduced a new livestreaming service to compete with Twitch, it
guaranteed Ninja, a streamer with millions of followers, a deal worth tens of
millions.

eventually combining with Didi after burning nearly $50 million a week in rider
and driver incentives to launch the market. This effort totaled over a billion
dollars of cash burn that year.

focused first and foremost on “Efficiency over Subsidy”—improving Uber’s unit
economics.

The math around Uber’s marketplace subsidies looked like this, at a high level:
Offer a $25/hour guarantee to drivers

-   A small network might provide 1 trip per hour
-   Let’s say drivers earn, on average, $10/trip
-   This means drivers can earn $10/hour, so to hit the guarantee, the company
    must subsidize an additional +$15/hour to make up the difference
-   This means the “Burn per Trip” is $15. Ouch!

Uber could provide far more trips to drivers: Same guarantee: $25/hour to
drivers

-   However, a larger network provides 2 trips per hour to drivers
-   At $10/trip, the larger network generates $20/hour—much better!
-   At $20/hour and a $25/hour guarantee, the subsidy is only $5/hour
-   In other words, only $2.50 Burn per Trip

This is a clear example of the [Economic Effect](#org70e005b), where a larger network has much
higher efficiency than a small one—the company burns significantly less per
trip, because the network can deliver more demand on an hourly basis. It also
means that a bigger network could give even larger incentives, allowing it to
efficiently win over drivers who are the hard side of the network.


#### Higher Conversion Rates as the Network Grows {#higher-conversion-rates-as-the-network-grows}

Dropbox’s High-Value Active Users is an example of this—users were found to
upgrade into paid subscriptions when they had collaborative use cases with their
coworkers, like shared folders and collaboration around documents.

networked products like marketplaces and app stores—though for different
reasons. When more sellers are part of a marketplace, there’s more selection,
availability, and comprehensive reviews/ratings—meaning people are more likely
to find what they want, and each session is more likely to convert into a
purchase.


#### The Impact of the [Economic Effect](#org70e005b) {#the-impact-of-the}

The Economic network effect, alongside its siblings in acquisition and
engagement, provide a strong defense against potential upstarts.

[Economic Effect](#org70e005b) means that the leading network often has a better business
model. Products with a strong [Economic Effect](#org70e005b) are able to maintain premium
pricing as their networks grow, because switching costs become higher for
participants who might be looking to join other networks.

However, this trio of network effects does not create permanent invincibility in
the market. While a large network often enjoys years of uncontested dominance
during the scaling phase, eventually it gets harder. So hard, in fact, that
growth might slow to zero.


## Part V: The Ceiling {#part-v-the-ceiling}


### 22. [Twitch]({{<relref "20211230140303-twitch.md#" >}}) {#22-dot-twitch--20211230140303-twitch-dot-md}

But as a product reaches scale, its growth curve eventually reaches a point
where it teeters on the edge between expansion and contraction—bursting into
expansion during some phases, and then contracting in others.

Ship the right innovative features, and the ceiling is pushed off—only to return
again awhile later in a different form.

CEO and cofounder Justin Kan described the situation:

> About the end of 2010, the company turned profitable. We did a ton of hard work
> to make it profitable, but we were at an impasse. We weren’t growing very much.
> Actually, we weren’t growing at all. When something’s not growing on the
> Internet, it’s basically on the brink of declining, precipitously.

Thus, Xarth.tv—yes, that’s what Twitch was originally called—was born.
Unfortunately for the team, the board of directors hated the plan. This new plan
would turn a profitable startup into one losing millions of dollars, and it
wasn’t yet obvious it would work.

As Emmett would recount to me at Twitch’s purple-clad offices several years
later, this new strategy had some key differences to Justin.tv’s original one:

> We did a lot different with Twitch than Justin.tv. The biggest thing was to
> focus on streamers, whereas originally it was more about the audience. This
> meant we worked on tools for streamers, which we improved over time. Making
> money was important to streamers, even small amounts, so we added tipping
> features.

All of these product changes made it easier for the best and most popular
streamers to quickly gain a following.

The new features and functionality were built on the observation that the [atomic
network](#org237b742) for Twitch could be as few as just one streamer and one viewer watching
them.

Kevin added:

> The real magic starts to happen once [you] have enough followers on Twitch, and
> you consistently have viewers every time you start streaming. Then every session
> on Twitch becomes fun, since there’s always an audience. But it’s even more fun
> to make money. Once there’s enough viewers, then you’ll eventually make your
> first dollar. This is a real aha moment—our streamers talk about how making even
> $20 or $50 a month is an eye-opener. But then build enough of an audience, and
> eventually, it’s possible to “go pro” and just work by streaming full-time.

after Twitch’s launch that the top streamers began to make $300,000+ per year.

Within a month after launch, Twitch had 8 million unique viewers, and within a
year after that, it had doubled to 20 million. And then doubled again, and so
on, so that today it is one of the most highly trafficked websites in the world.

It’s not just consumer companies that face this—workplace products and bottom-up
[SaaS]({{<relref "20210701230836-saas.md#" >}}) startups use their network effects to grow virally, but eventually saturate
their initial market of startups and early adopters. Then they need to learn how
to sell into the enterprise to build the next phase of their business. We see
this all the time at [Andreessen Horowitz]({{<relref "20211211010432-andreessen_horowitz.md#" >}}), where my colleague David Ulevitch
says: In the early days, startups often see success as other startups and small
businesses adopt their product—this is the “bottom-up” distribution model that
has propelled Slack, Zoom, Dropbox, and many others. Problem is, smaller
customers are always churning out because they’re price sensitive, running out
of money, and changing their business model—sometimes all three! Larger
enterprise customers, on the other hand, are sometimes harder to break into but
can grow revenue over time as more and more users adopt it within a company.
Thus it’s natural for B2B startups to begin with a bottom-up sales motion but
eventually add expertise to sell into enterprises.


#### Introducing the Ceiling {#introducing-the-ceiling}

It happens for a variety of reasons, including market saturation, degradation of
marketing channels, overcrowding, spam, and so on.

In “Rocketship Growth,” I’ll start by defining success—what it means to be on
track, versus [hitting the ceiling](#org9c20d6f).

First among the causes of slowdown is “Saturation.”
At the same time this is happening, the network itself is changing.
While the hard side evolves, the rest of the network is changing as well.
And finally, I describe how discovery of relevant people and content becomes
hard—I call this the “Overcrowding” dynamic within networks.


### 23. Rocketship Growth—[T2D3]({{<relref "20211230140317-t2d3.md#" >}}) {#23-dot-rocketship-growth-t2d3--20211230140317-t2d3-dot-md}

In the United States, there are roughly 6 million new businesses started each
year...These startups are then referred to about 1,000 active venture capital
firms...there are about 5,000 venture capital investments per year available to
new and early-stage startups...only 1 in 20 venture-backed startups end up with
the > 10x exits the industry is focused on.

The team at [Horsley Bridge]({{<relref "20220111225630-horsley_bridge_partners.md#" >}})—a high-profile investor in venture capital funds—has
shown that industry-wide the failure rate of venture-backed startups is over 50
percent. There are many reasons why this happens, but generally, the outcome is
the same: they stop growing, peter out, and never achieve success.

The biggest companies each year eventually come to employ over a hundred
thousand people, like Amazon, Oracle, Microsoft, Apple, Intel, Google, and
others. They represent nearly 20 percent of the [S&P 500]({{<relref "20220111225739-s_p_500.md#" >}}) and several of them
became worth more than a trillion dollars at the start of 2020. These outsized
returns are why Stanford researchers have ascribed 57 percent of the value of
the US stock market to companies initially backed by venture capital.63 These
companies employ over 4 million people, investing $454 billion on R&D.
Incredible.


#### The [Rocketship Growth Rate](#org82d003a) {#the}

<a id="org82d003a">Rocketship Growth Rate</a>
the precise pace at which a startup must grow to break out.

Hitting a $1 billion [Valuation]({{<relref "20210802204348-valuation.md#" >}}) generally requires at least $100 million in
top-line [Annually Recurring Revenue]({{<relref "20210807103748-annualized_run_rate.md#" >}}), based on the rough market multiple of 10x
revenue.

[Neeraj Agarwal]({{<relref "20220111230254-neeraj_agarwal.md#" >}}), a venture capitalist and investor in B2B companies, first
calculated this growth rate by arguing that [SaaS]({{<relref "20210701230836-saas.md#" >}}) companies in particular need to
follow a precise path to reach these numbers:

-   Establish great [Product-Market Fit]({{<relref "20210806234604-product_market_fit.md#" >}})
-   Get to $2 million in ARR
-   Triple to $6 million in ARR
-   Triple to $18 million
-   Double to $36 million
-   Double to $72 million
-   Double to $144 million.

The first phase, in which the team initially gets to [Product-Market Fit]({{<relref "20210806234604-product_market_fit.md#" >}}), takes
1–3 years...SaaS companies like [Marketo]({{<relref "20220111230441-marketo.md#" >}}), [Netsuite]({{<relref "20220111230456-netsuite.md#" >}}), [Workday]({{<relref "20220111230521-workday.md#" >}}), [Salesforce]({{<relref "20210704214558-salesforce.md#" >}}), [Zendesk]({{<relref "20220111230550-zendesk.md#" >}}),
and others have all roughly followed this curve.

Add on the time to reach the rest of the growth milestones, and the entire
process might take 6–9 years.

after year 10, the company might still be growing quickly, though it’s more
common for it to be growing 50 percent annualized rather than doubling.

For those seeking venture capital, it is a pretty standard minimum bar to get to
$1 billion in valuation over ten years.

The [Rocketship Growth Rate](#org82d003a) was originally developed for SaaS software companies
where the business model is powered by a subscription, and so for companies like
Dropbox, Zoom, Slack, and DocuSign it’s directly applicable.


#### Rocketship Growth Rates for Marketplaces {#rocketship-growth-rates-for-marketplaces}

for marketplace companies, gross merchandise value ([GMV]({{<relref "20210819201307-gross_merchandise_volume.md#" >}})) or net revenue is often
used—that maps to that [Valuation]({{<relref "20210802204348-valuation.md#" >}}).

An equation to calculate the target growth rate is handy here. The equation
looks like this:

\\(Rocketship\ growth\ rate = (\frac{target\ revenue-starting\ revenue}{starting\ revenue})^\frac{1}{years}\\)

Or filling in our numbers: [Rocketship growth rate](#org82d003a) = (($200M − $1M) / $1M)^(1/6) = 2.4x


#### Why the Rocketship Trajectory Is Tough {#why-the-rocketship-trajectory-is-tough}

[Rocketship Growth Rate](#org82d003a) is very hard. And even while each year’s goal tends to
triple or double, a company will simultaneously face countervailing
forces—saturation of the market slows down growth, marketing channels degrade in
performance, and product development never keeps up with user demands. The
cardinal rule is that growth rates tend to drop over time, even as more
investment is poured into adding employees, building the product, and servicing
customers.


#### The Good News, and the Bad {#the-good-news-and-the-bad}

The reason is straightforward—teams tend to use all the obvious growth levers
they can in the first few years, which quickly run out over time.

Networked products, on the other hand, have a massive advantage—they can tap
into their network effects to fight the slowdown. For example, while the steady
decline of marketing channels is inevitable, teams can amplify viral growth by
optimizing sign-up funnels, recommendations for friends to invite, and so on.


### 24. Saturation—[eBay]({{<relref "20211227192834-ebay.md#" >}}) {#24-dot-saturation-ebay--20211227192834-ebay-dot-md}

Success comes with an inevitable problem: market saturation.

Eventually this stops working because nearly everyone in the target market has
joined the network, and there are not enough potential customers left.

Eventually this stops working because nearly everyone in the target market has
joined the network, and there are not enough potential customers left. From
here, the focus has to shift from adding new customers to layering on more
services and revenue opportunities with existing ones.

It was in 2000, and for the first time ever, eBay’s US business failed to grow
on a month-over-month basis.

Jeff shared what the team did to find the next phase of growth for the company:

> Launching “Buy It Now” was a large change that touched every transaction, but
> the eBay team also innovated across the experience for both sellers and buyers
> as well.

![](/ox-hugo/2022-01-11_23-26-41_f0255-01.jpg)
eBay Revenue


#### Network Saturation versus Market Saturation {#network-saturation-versus-market-saturation}

Although this entire phenomenon is often called market saturation...I think of
it as network saturation, not just market saturation. Here’s how I define this
term: the 100th connection for any given participant is likely less impactful
than the first few, and as the network gets more dense over time, its associated
network effects become less incrementally powerful.

Social apps have a similar dynamic, where each additional friend connection is
not as valuable as the previous one. In an internal memo to the Snapchat team,
CEO Evan Spiegel reported on the diminishing returns of connections: Your top
friend in a given week contributes 25% of Snap send volume. By the time you get
to 18 friends, each incremental friend contributes less than 1% of total Snap
send volume each.

[Snapchat]({{<relref "20211230135303-snapchat.md#" >}}) team, CEO [Evan Spiegel]({{<relref "20220111233612-evan_spiegel.md#" >}}) reported on the diminishing returns of
connections:

> Your top friend in a given week contributes 25% of Snap send volume. By the time
> you get to 18 friends, each incremental friend contributes less than 1% of total
> Snap send volume each.


#### New, Adjacent Networks {#new-adjacent-networks}

Understanding these adjacent networks is key, so that they can be targeted one
by one to expand and fight saturation.

Understanding these adjacent networks is key, so that they can be targeted one
by one to expand and fight saturation. My friend Bangaly Kaba, formerly head of
growth at Instagram, called this idea the theory of “Adjacent Users.” He
describes his experience at Instagram, which several years post-launch was
growing fast but not at rocketship speed:

> Our success was anchored on what I now call The Adjacent User Theory. The
> Adjacent Users are aware of a product and possibly tried using it, but are not
> able to successfully become an engaged user. This is typically because the
> current product positioning or experience has too many barriers to adoption for
> them. While Instagram had product-market fit for 400+ million people, we
> discovered new groups of billions of users who didn’t quite understand Instagram
> and how it fit into their lives.

Bangaly describes this approach:

> When I started at Instagram, the Adjacent User was women 35–45 years old in the
> US who had a Facebook account but didn’t see the value of Instagram. By the time
> I left Instagram, the Adjacent User was women in Jakarta, on an older 3G Android
> phone with a prepaid mobile plan. There were probably 8 different types of
> Adjacent Users that we solved for in-between those two points.


#### New Formats {#new-formats}

The beauty of something like eBay’s “Buy It Now” and “Stores” efforts is that
they still fundamentally tap into the same network of buyers and sellers, but
provide a new interaction that might better support new use cases.


#### New Geographies {#new-geographies}

Layering on new geographies—as eBay did by adding international regions—is
another way to build up the layer cake.

Regional expansion is easier when networks grow into directly adjacent networks

However, there are failure cases as well. A highly urban market like San
Francisco possesses many unique factors: lots of early adopters, a high cost of
living, a mostly urban environment, and a very educated consumer market

Layering on growth from faraway geographies is far harder. This usually requires
the team to start their network from zero once again, on top of all of the
additional work: localizing content, finding local partners, implementing new
payment methods, and potentially iterating on the product concept itself—because
sometimes the idea doesn’t fully translate.

Laying on completely new international markets is hard because it generally
requires a combined effort from many different team functions.


#### Why Fighting Market Saturation Is So Hard {#why-fighting-market-saturation-is-so-hard}

The solutions to market saturation might sound straightforward—add new
geographies, support more formats and business models, and other tips that sound
like common sense.


### 25. [The Law of Shitty Clickthroughs](#org0a51084)—[Banner Ads]({{<relref "20211230140345-banner_ads.md#" >}}) {#25-dot-banner-ads--20211230140345-banner-ads-dot-md}

<a id="org0a51084">The Law of Shitty Clickthroughs</a>
[The Law of Shitty Clickthroughs](#org0a51084) says every marketing channel degrades over time.
This means lower clickthrough, engagement, and conversion rates, regardless of
if you’re talking about email, paid marketing, social media, or video. This is a
core reason why products hit growth ceilings—when marketing channels stop
performing, the growth curve starts to bend downward.

Consumers first experienced banner ads on Hotwired, the first commercial web
magazine.

The advertisers launched the first campaign that included a banner ad that asked
the viewer, “Have you ever clicked your mouse right HERE? You will.”

Today, banner advertising clickthrough rates usually hover around 0.3–1 percent,
but the first ads ever had incredible engagement: 78 percent at the start!

It’s not just online advertising that followed this trend—email did, too.

ClickZ, an industry blog, published a graph showing that over a nearly decade
time span, email marketing clickthrough rates dropped from 30 percent to under
half that—13 percent.

The same can be found for nearly all growth channels over time.


#### Degrading the Network {#degrading-the-network}

The degradation of marketing channels is an existential threat to a product’s
network effects.


#### Layering on New Growth Strategies {#layering-on-new-growth-strategies}

When new products launch, there are usually one or two acquisition channels that
work—but they might not scale. In Dropbox’s case, the initial wait list was
formed by users who watched the announcement video about the product.

The best practice is for products—whether they have network effects or not—to
constantly layer on new channels.

The key for a new product team is to understand which channels best fit its
product, and to hire the relevant people who’ve already done it.

For workplace/B2B products, the focus will often turn toward adding a direct
sales channel in combination with the other various “bottom-up” consumer-like
acquisition channels, so that it all works in an integrated way. There is
sometimes low-hanging fruit. Often, it’s as easy as looking at all the users who
are signing up or who are active, and checking out their email domains to figure
out which companies to sell into. Or maybe just asking these users for their
company name and team size—and then start emailing them to sell. Another quick
fix is to add a “Contact us” tier of service on the pricing page. At the same
time, run a parallel effort that emphasizes content marketing, events, and other
programs that drive more top of funnel leads. Build a growth team that can score
individual accounts and add life cycle triggers so that the sales team sees when
the product reaches a certain footprint inside an organization. In doing all of
this, multiple channels can be combined into a broader strategy.

new B2B startups have started to embrace referral programs, memes, emojis, video
clips, and other tactics previously reserved for consumer products.


#### Tapping into the Acquisition Network Effect {#tapping-into-the-acquisition-network-effect}


### 26. When the Network Revolts—[Uber]({{<relref "20211230134558-uber.md#" >}}) {#26-dot-when-the-network-revolts-uber--20211230134558-uber-dot-md}


#### The Hard Thing about the Hard Side {#the-hard-thing-about-the-hard-side}

A well-organized revolt by the major members of its hard side can kill a product
entirely.

The numbers are similarly concentrated: Slack’s S-1 filing showed less than 1
percent of Slack’s total customers accounted for 40 percent of the revenue, and
Zoom’s indicated that 30 percent of revenue came from just 344 accounts, again
less than 1 percent of their customer base.

The numbers are similarly concentrated: Slack’s S-1 filing showed less than 1
percent of Slack’s total customers accounted for 40 percent of the revenue, and
Zoom’s indicated that 30 percent of revenue came from just 344 accounts, again
less than 1 percent of their customer base

About half the top iOS apps are developed by a small group of elite developers:
Google, Facebook, Microsoft, Amazon, and a few others. Just twenty apps drive 15
percent of all app downloads!

The most organized YouTube channels and Instagram influencers might start out as
individuals, but eventually scale their production so that their millions of
viewers see professionally created content. Reddit has these dynamics within
moderators, who organize the largest communities with 20 million subscribers
each! However, look further down the list and the numbers rapidly fall off in
exponential fashion, such that a top 98th percentile community—ranked 20,000 out
of over 2 million subreddits—has just a few thousand subscribers.

A networked product generally wants to nudge its ecosystem toward
professionalization, because it helps scale the hard side

The company might offer training, documentation, and monetization

Up-front investment to try to professionalize the supply side early on in a
network’s development inevitably comes with risk. In a well-publicized misstep
for Uber, the company sought to expand its supply side by financing vehicles to
provide cars to potential drivers who didn’t own vehicles, a program called
XChange Leasing

XChange Leasing unfortunately lost $525 million and failed to professionalize
the driver side of the market. The problem was, it attracted drivers highly
motivated by money—usually a positive—but who didn’t have high credit scores for
good reason

However, I argue that there’s no choice but to embrace this.


#### How Professionalization Happens {#how-professionalization-happens}

Professionalization happens in two ways: homegrown professionals, and
off-network professionals

When a network’s biggest members become large, they can often become high-scale,
investor-backed startups on their own.

When a network becomes large, rich, and diverse, it’s often described as an
“Economy”—you may have heard about the Gig Economy, the Attention Economy, the
Creator Economy, and so on.


#### No Choice but to Scale {#no-choice-but-to-scale}

What might have been a $70 Craigslist ad to recruit a driver in the early days
eventually became $1,000+ per active driver from every direction—paid marketing,
referrals, even TV and radio ads.

It needed to grow the market, and onboard a larger and more mainstream segment
of users. This segment of drivers required more education, more vetting, and
more encouragement on how they should interact with riders

Embrace the professionalization of the hard side, and reap the benefits of
increasing scale.


### 27. Eternal September—Usenet {#27-dot-eternal-september-usenet}

Created in the early days of the internet in 1980, Usenet was the first
worldwide distributed discussion system, hosting newsgroups like talk.politics,
rec.arts.movies, rec.crafts.winemaking, and a hundred other topics.

Early internet users even made up a term, called “Godwin’s Law”—the observation
that every heated digital conversation devolves into comparisons with Nazis—to
describe the vicious debates that happened on Usenet in the 1980s.


#### Context Collapse {#context-collapse}

Let’s use a story to describe how it happens—this one from Adam D’Angelo, CEO of
Quora and ex-CTO of Facebook. He explains how it affects social and
communication products: When you first join a social network with your close
friends, it’s easy to use it a lot. You might post photos and comments all the
time—full of in-jokes and shared stories. You and your friends like it so much
you invite your other friends, and then their siblings, too. And so on. But
eventually, photos and content meant for your close friends might attract
comments from people you don’t know well. Your parents get invited, and maybe
your teachers, or your boss. Those photos of a party you went to might get you
in trouble.


#### Networks of Networks . . . of Networks {#networks-of-networks-dot-dot-dot-of-networks}

Products like iMessage or WhatsApp give us a clue. Messaging apps are resistant
to context collapse. You talk to your dozen or so friends and family, and even
if the network adds millions more people, it doesn’t change your experience.

In other words, not all networked products experience context collapse as
rapidly as others.


#### The Power of the Downvote {#the-power-of-the-downvote}


#### Usenet’s Collapse, in Hindsight {#usenet-s-collapse-in-hindsight}


### 28. Overcrowding—[YouTube]({{<relref "20211230140354-youtube.md#" >}}) {#28-dot-overcrowding-youtube--20211230140354-youtube-dot-md}

Too many videos on YouTube is a specific case of a broader phenomenon of
overcrowding, which can hurt network effects and ultimately make a product
unusable.


#### The Early Days of Organizing Videos {#the-early-days-of-organizing-videos}

YouTube as a dating site didn’t last long, and within a few weeks

The YouTube team rolled out solution after solution to solve overcrowding, but
focused on the simple ones first—displaying a list of recently uploaded videos,
followed by a popularity-based sort, and eventually country segmentation.


#### The Rich Get Richer' {#the-rich-get-richer}

Overcrowding works in a different way for creators than for viewers. For
creators, the problem becomes—how do you stand out?

Eventually, the problem becomes, how does a new member of the network break in?


#### The Power of Data and Algorithms {#the-power-of-data-and-algorithms}

In the years following the acquisition, Steve described the company’s focus very
simply: “We were just trying to keep up with all the traffic.”

One notable example of this is the ever present “People You May Know” or “Friend
suggestions” feature

TikTok’s relevance algorithms make sure that even as hundreds of millions of
videos are added over time, creators will still be matched with viewers who want
to consume their content—and vice versa. “Data network effects” are often
invoked as a path for networks to solve relevance and overcrowding issues that
emerge over time.


#### Algorithms Aren’t a Silver Bullet {#algorithms-aren-t-a-silver-bullet}

To me, the key learning from the YouTube story is the journey that every
networked product has to take. When they started out, they needed very little
organization, but as the network grew, more and more structure was applied—first
by editors, moderators, and users—and then by data and algorithms. The earliest
iterations weren’t sophisticated, just whatever got the job done. Algori54-thms
came later, and even years later, keeping the network healthy is still an
everyday battle.


## Part VI: [The Moat](#org726d630) {#part-vi}


### 29. [Wimdu]({{<relref "20211230140440-wimdu.md#" >}}) versus [Airbnb]({{<relref "20211230140503-airbnb.md#" >}}) {#29-dot-wimdu--20211230140440-wimdu-dot-md--versus-airbnb--20211230140503-airbnb-dot-md}

If your product has network effects, your competitors likely have them,
too—which can create a dangerous situation.

[Wimdu]({{<relref "20211230140440-wimdu.md#" >}}) was a direct copy of Airbnb focused initially on the European market, and
from day one, it was a scary competitor—it launched with $90 million in funding,
the largest investment in a European startup ever, and within less than one
hundred days, the company already hired over 400 people and had thousands of
properties on its marketplace.
At that point, Airbnb was only two and a half years old, had 40 employees, and
had raised a small venture capital round. It only supported payments in USD, no
European currencies, and hadn’t been translated to any languages beyond English.

When Airbnb first launched, there were already several adjacent competitors.
First, VRBO...but the product UI was less polished, with more friction to list
and transact. VRBO was later merged with HomeAway, and more important, the
network focused on vacation rentals located in out-of-the-way destinations
rather than Airbnb’s early focus on shared spaces within dense urban
cities...Another product, Couchsurfing, already existed as well, and was an
indirect competitor, albeit a peculiar one. Founded in 2003 as a nonprofit,
Couchsurfing allowed for people to crash on each other’s sofa while traveling
but did not require payment.

By mid-2011, Wimdu was aggressive in taking on the European market...automated
side, Wimdu built bots that would scrape listings—mirroring descriptions,
photos, and availability so that if hosts wanted to maintain listings on both
platforms...there were reports from the community that sometimes the listings
were just fake...On the ground, Wimdu would pose as guests and rent from Airbnb
hosts, and during the process try to convince them to also list on Wimdu...the
company built over 50,000 listings and was on its way to $130 million in gross
revenue in its first year of operations.

It took just two years for Wimdu to unravel. Incredibly by 2014, it was laying
off employees and accepting that it had lost leadership in the European market.
Eventually, through several rounds of M&A, all the employees were laid off
in 2018.

Michael Schaecher, an early employee at Airbnb (#17) who headed up some of the
international efforts in the competitive response, said of Wimdu’s strategy:

> All supply isn’t created equal. Wimdu’s top 10% of inventory was at the bottom
> 10% of Airbnb’s. They went for numbers, but recruited large property owners that
> managed hundreds of units in the form of low-end hostels. They went the easy
> route and would get 1000 listings via 10 property owners, but the experience for
> customers was disappointing. In the early days at Airbnb, we would always talk
> about creating a positive “Expectations Gap.” In the early days, when we were
> new, guests go in with low expectations, but then would be blown away by the
> experience. You need this high NPS to get people to tell their friends, and it
> makes hosts more likely to join too. Our competitors who took shortcuts couldn’t
> deliver here.


#### Introducing [the Moat](#org726d630) {#introducing}

[the moat](#org726d630), I will describe what happens when networks compete with other
networks, and why this form of competition is so unique

To introduce the nature of network-based competition, I describe why it’s
high-stakes, where the loser can go to zero while the victor taps into its
network effects to win the market—this is the “Vicious Cycle, Virtuous Cycle.”

One of the core strategies in network-based competition is “Cherry Picking.”

[The moat](#org726d630) is about a successful network that defends its turf, using network
effects in a perpetual battle against smaller networks trying to enter the
market.


### 30. Vicious Cycle, Virtuous Cycle {#30-dot-vicious-cycle-virtuous-cycle}

[Warren Buffett]({{<relref "20210203011532-warren_buffett.md#" >}}) popularized the concept of the competitive [Economic Moat]({{<relref "20210206215201-economic_moat.md#" >}}), as he
described his investing strategy:

> The key to investing is not assessing how much an industry is going to affect
> society, or how much it will grow, but rather determining the competitive
> advantage of any given company and, above all, the durability of that advantage.
> The products or services that have wide, sustainable moats around them are the
> ones that deliver rewards to investors.

It’s the difficulty of cloning their network that makes these types of products
highly defensible.

In the modern era, cloning software features is usually not the hard part

Because Buffett generally invests in low-tech companies like See’s Candies or
Coca-Cola, [the moat](#org726d630) he refers to is often a strong brand or a unique business
model.

But once Airbnb has reached [Escape Velocity](#orgaa9feff) in a market, [the Cold Start Problem](#org4270a82)
creates the defense against new entrants. After all, every new competitor
entering the city will need to solve [the Cold Start Problem](#org4270a82) and build up the
same density—as hard as it was for your product to go from zero to a [Tipping
Point](#org75e7f20), it will be even harder for competitors starting from a disadvantage.

This is literally [the moat](#org726d630), and reframes [the Cold Start Problem](#org4270a82) for Airbnb’s
competitors


#### The Battle of Networks {#the-battle-of-networks}

lean toward “winner take all.” When one product emerges as the winner in an
[atomic network](#org237b742), that’s just the group choosing their favorite app. But repeat
that enough times, and that becomes the playbook for a product to win across the
entire market—and that’s a monopoly

But how does the competitive playbook work in a world with network effects?
First, I’ll tell you what it’s not: it’s certainly not a contest to see who can
ship more features

it’s often the dynamics of the underlying network that make all the difference

Network-based competition is unique, and has its own dynamics


#### Your Competition Has Network Effects, Too {#your-competition-has-network-effects-too}

To figure out a response, it’s important to acknowledge a common myth about
defensibility and moats: that somehow, network effects will magically help you
fend off competition

Effective competitive strategy is about who scales and leverages their network
effects in the best way possible.


#### Network Collapse {#network-collapse}


#### David versus Goliath {#david-versus-goliath}

Startups have fewer resources—capital, employees, distribution—but have
important advantages in the context of building new networks: speed and a lack
of sacred cows


### 31. Cherry Picking—[Craigslist]({{<relref "20211230140524-craigslist.md#" >}}) {#31-dot-cherry-picking-craigslist--20211230140524-craigslist-dot-md}

[Craigslist]({{<relref "20211230140524-craigslist.md#" >}}) is a classifieds listing site that is an embodiment of a paradox.

a long line of startups have cherry-picked some of its most valuable
audiences—famously referred to as the “unbundling of Craigslist.”

Craigslist should not be thought of as a single, monolithic network built on a
unified classifieds product, but rather as a network of networks—the people who
use the Seattle Craigslist are not the same as users in Miami.

Every dominant network might seem invincible, but the networks-of-networks
framing argues that some parts of the network are weaker than others.

The opportunity to unbundle these larger networks requires both building the
necessary product features to support these splinter communities and also taking
the direct action to message, advertise, or otherwise convince members of the
larger horizontal community to shift over.


#### Finding the Soft Spot {#finding-the-soft-spot}

The question is, which [atomic network](#org237b742) do you pick?

As another example, let’s examine Snapchat. The product’s photo messaging
features could be seen as just a feature of a larger social network product
since, at the time, photos were one of many media types shared on Facebook,
Twitter, MySpace, and other platforms.


#### Switching over Entire Networks {#switching-over-entire-networks}

When an incumbent has its network cherry-picked, it’s extra painful along two
dimensions: First, any network that is lost is unlikely to be regained, as
[anti-network effects](#org56fa12c) kick back in. And second, the decline in market share hits
doubly hard, which has implications for being able to raise money.

For Craigslist to get this market back, they’ll have to solve [the Cold Start
Problem](#org4270a82) again—except this time with a competitor also in the market who might
react with incentives and product features to counter.


#### The Danger of Platform Dependence {#the-danger-of-platform-dependence}

Of course, cherry picking is not without its risks.

Any new product that starts to cherry-pick must eventually be able to build its
own stand-alone destination and scale it.


### 32. Big Bang Failures—[Google+]({{<relref "20211230140535-google.md#" >}}) {#32-dot-big-bang-failures-google-plus--20211230140535-google-dot-md}

The Big Bang Launch is often the strategy of the larger player in a market,
which uses its advantages in size and scale to quickly overwhelm an opponent.


#### [Anti-Network Effects](#org56fa12c) Hit the Google+ Launch {#hit-the-google-plus-launch}

In a Wall Street Journal article by Amir Efrati, Google+ was described as a
ghost town even while the executives touted large top-line numbers

At its peak, Google+ claimed to have 300 million active users—by the top-line
metrics, it was on its way to success. But network effects rely on the quality
of the growth and not just its quantity. Eventually the collection of weak
networks and high churn caught up, and in 2019, Google+ finally shut down after
years of meandering irrelevance.


#### The Problem with the Big Bang {#the-problem-with-the-big-bang}

The problem with the Big Bang approach to building networks is twofold: First,
it is built on broadcast channels. The weakness of media coverage, conferences,
or advertising is that while it might generate a large spike of users when
successful, it is necessarily untargeted.

The second issue is that it takes time for a product to have the right features,
but also to have enough built out to drive viral growth—such as sharing,
invites, and collaboration.

Most important, though, you aren’t Apple. So don’t try to copy them without
having their kinds of products.


#### The Paradox of Small Markets {#the-paradox-of-small-markets}

Startups, on the other hand, have the advantage that they can start small, and
grow, which is why some of the largest networked products in the industry—eBay,
Facebook, Uber, Airbnb, and TikTok—started with small, atomic networks.


#### The Allure of the Big Bang Launch {#the-allure-of-the-big-bang-launch}

The dynamics of larger, established companies make the big launch particularly
attractive. They try to jump from zero to the [Tipping Point](#org75e7f20) in one bang, because
of the internal pressures of starting and building a new product internally.


### 33. Competing over the Hard Side—[Uber]({{<relref "20211230134558-uber.md#" >}}) {#33-dot-competing-over-the-hard-side-uber--20211230134558-uber-dot-md}

The eventual winners in these product categories were not the first to market,
nor did they invent most of the underlying mechanics, but they still upended the
big guys.

The eventual winners in these product categories were not the first to market,
nor did they invent most of the underlying mechanics, but they still upended the
big guys. If network effects are so powerful, why are the larger networks so
vulnerable?


#### North American Championship Series {#north-american-championship-series}

Airbnb, PayPal, and other products with global network effects connect people
from all over the world into a single network—or at least big, regional
networks. In contrast, Uber’s networks stood segmented from each other in a
city-by-city fashion.


#### Finding the Competitive Levers {#finding-the-competitive-levers}

On Android, there were direct APIs that could tell if someone was running Uber
and Lyft at the same time. Eventually a large number of these signals were fed
into a machine learning model where each driver would receive a score based on
how likely they were to be a dual apper.

To reinforce stickiness, one set of offers would ask them to drive as many hours
in a week as possible for Uber rather than for rivals. Sometimes these were
simple bonuses, called “Do X Get Y” (DxGy) offers, where a $100 bonus would be
added once the driver hit 50 trips in a week.


#### Competitive Intelligence {#competitive-intelligence}

There was an estimate of Uber’s trips that week, and the trips of the largest
competitors, providing a network-by-network market share report. There was a set
of ratios, like the percentage of times users’ trips ended up being “surge
priced,” an indicator there weren’t enough drivers on the road.

Think of these as “Nielsen ratings” for consumer credit card spend, where a
small panel of a few million users could give you a sample for a much broader
market

any product that’s in a head-to-head race with competitors should track the
outcomes—market share, active users, engagement, or otherwise—while they execute
in the market, to put together cause and effect.


#### Competing over the Hard Side {#competing-over-the-hard-side}

As the runway got short, if pressure was applied at the right moments—using
incentives and product improvements—Uber’s competitors would find it hard to
show consistent growth.

Yet for all of the time and effort that was put into the competitive efforts, it
didn’t always work.


### 34. Bundling—Microsoft Conclusion: The Future of Network Effects {#34-dot-bundling-microsoft-conclusion-the-future-of-network-effects}

Bundling has been at the center of many of the biggest battles in the technology
industry, particularly the ones involving Microsoft.

To learn why bundling sometimes works, and other times doesn’t, I went to the source.
Brad Silverberg, who in his decade at Microsoft headed up some of the company’s
most important product efforts—including the much-celebrated release of Windows
95...he’s skeptical of the power of bundling: Bundling a product is not the silver
bullet everyone thinks. If it were that easy, the version 1.0 for Internet
Explorer would have won, by simply bundling it with Windows. It didn’t—IE 1.0
only got to 3% or 4% market share, because it just wasn’t good enough yet. Bing
is another example

Even if bundling gets you a lot of new users trying out a product, they won’t
stick around if there’s a huge gap in features.


#### The Importance of a Killer Product {#the-importance-of-a-killer-product}

[Microsoft Office]({{<relref "20220117204908-microsoft_office.md#" >}}) is another famous example of bundling within the technology
industry.

[Steven Sinofsky]({{<relref "20220117205114-steven_sinofsky.md#" >}}), now a colleague at [Andreessen Horowitz]({{<relref "20211211010432-andreessen_horowitz.md#" >}}), who previously spent
decades at [Microsoft]({{<relref "20220117204930-microsoft.md#" >}}) shipping six major releases of Office.

Much effort was put toward making each application within the suite work with
each other. For example, an [Excel]({{<relref "20220117204908-microsoft_office.md#products" >}}) chart would be embedded within a Microsoftz3
Word document—this was called Object Linking and Embedding (OLE)—which made the
combination of the products more powerful.

bundling can provide a huge distribution advantage, but it can only go so far.


#### Competing with a Network, Not Just Features {#competing-with-a-network-not-just-features}

While this helps generate a nice bump of new users, it doesn’t solve [the Cold
Start Problem](#org4270a82) unless atomic networks are quickly formed.

Instagram is a great example of bundling done well, and why a networked product
that launches another networked product is at a huge advantage.


#### Locking In the Hard Side {#locking-in-the-hard-side}

Brad described the importance of Visual Basic (VB) in particular, to the Windows
strategy: Visual Basic was a key part of the flywheel for Windows. Every
business, and especially small businesses, had all these programs that are part
of their daily workflow.

With Visual Basic, an infinite number of niche use cases, particularly within
companies, could be automated. Thus the quote from early Microsoft execs, “For
every copy of VB we sell, there are ten copies of Windows that go along with
it.”


#### Microsoft Takes on the Web {#microsoft-takes-on-the-web}


#### The Drawbacks of Bundling {#the-drawbacks-of-bundling}

Bundling has both helped and hurt companies implementing it over the years. Many
of Microsoft’s security issues, instability, and less elegant interfaces can be
traced directly back to the decision to focus on the needs of developers,
particularly enterprise customers who made big investments in custom software
that required reverse compatibility.


### Conclusion The Future of Network Effects {#conclusion-the-future-of-network-effects}

n late 2018, Uber had a new CEO and executive team, a new set of cultural
values, and a new emphasis on profitability. It was telling that the War Room
had been renamed the Peace Room, to reflect the “Uber 2.0” priorities.


### Acknowledgments {#acknowledgments}