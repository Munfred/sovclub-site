---
title: Quadratic voting and quadratic funding!
subtitle: ⬛ ◼️ ◾▪️ 🗳 = (∑√cᵢ)² ▫️◽ ◻️ ⬜
category:
  - Weekly Discussions
author: Eduardo
date: 2020-05-05T21:00:00.000Z
featureImage: /uploads/sovball.png
---
Let us say (since, shockingly, some of you only show up for 🍻 🍕 and 🐂 💩) that you're an aspiring benevolent autocrat. Now that you have control over policies and the populace, how do you maximize utility? How do you know what is best for everyone?

\
It is a notorious problem in game theory that it is tricky to make agents disclose their true preferences. As an autocrat, if you knew everyone's utility curves, it would be easy peasy lemon squeezy to allocate resources optimally 🥜 🍋. Alas you don't.



But one thing that you could do, is make everybody a "[credible promise](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3364031)" that you'll do a certain thing based on what they tell you. You tell them the resource allocation is a function of what they tell you. Now you need to figure out which function makes them tell the truth - you need to align incentives so that individual utility will be maximized when that individual discloses their true preferences.



There is, it seems, a whole field devoted to figuring that out. "Inverse game theory" - figuring out the rules of the game - is called [mechanism design](https://en.wikipedia.org/wiki/Mechanism_design). And the "mechanism" (not [The Mechanism](https://en.wikipedia.org/wiki/The_Mechanism_(TV_series)), which you should watch - although come to think of it, it is the same thing except the goal is rent seeking...) is the function that processes the messages you got from the populace.



Back in the day, the ancient greeks devised a great such mechanism to make you do your taxes properly. They had a kind of progressive taxation where the wealthiest people, the *lithurgy* paid more taxes to fund public works and such. But how to make people tell you how much wealth they have, and pay taxes on them? [Well](https://books.google.com.br/books?id=JOmRDwAAQBAJ&pg=PT48&lpg=PT48&dq=%22According+to+Demosthenes,+any+member+of+the+liturgical+class+could+challenge+any+other+citizen+he+believed+was+wealthier+to+antidosis+or+%E2%80%9Cexchange.%E2%80%9D36+The+person+being+challenged+would+have+to+either+assume+the+liturgical+responsibility+or+exchange+all+possessions+with+the+challenger.%22&source=bl&ots=Dix7qbe0EI&sig=ACfU3U3Pc-jMs88Hgz04FQGcnjeQ8fd3wg&hl=en&sa=X&ved=2ahUKEwjc-MqTn5vpAhWCGbkGHbQLB20Q6AEwAHoECAIQAQ#v=onepage&q=%22According%20to%20Demosthenes%2C%20any%20member%20of%20the%20liturgical%20class%20could%20challenge%20any%20other%20citizen%20he%20believed%20was%20wealthier%20to%20antidosis%20or%20%E2%80%9Cexchange.%E2%80%9D36%20The%20person%20being%20challenged%20would%20have%20to%20either%20assume%20the%20liturgical%20responsibility%20or%20exchange%20all%20possessions%20with%20the%20challenger.%22&f=false):



> *According to Demosthenes, any member of the liturgical class could challenge any other citizen he believed was wealthier to antidosis or “exchange.” The person being challenged would have to either assume the liturgical responsibility or exchange all possessions with the challenger. The system gives everyone an incentive to be honest despite the burdens of the liturgy. If you falsely claimed to be poorer than the top 1,000 so as to avoid the liturgical burdens, then you could end up being forced to exchange your possessions with someone who is poorer than you are.*



No auditing, no [IRS](https://www.bloomberg.com/opinion/articles/2018-04-17/the-irs-computer-system-is-the-oldest-in-the-government), no nothing! Talk about a clever mechanism...



Makes you wonder, "what other kinds of wonky mechanisms could we devise for improving general welfare, which maybe were too clunky to do properly until recently, but now we can do using \_\_\_\_\_\_ technology?". Fill in the blank as you please, but the truth is, most of our social mechanisms (e.g. 1 person 1 vote choice mechanisms) have been around for a long time, and maybe surely we can do better. Things like [ranked voting](https://en.wikipedia.org/wiki/Ranked_voting) have also been around (mostly as an idea) for a while.



But what about solving really hard problems with clever mechanisms, like [the tragedy of the commons](https://en.wikipedia.org/wiki/Tragedy_of_the_commons)? How do we provide "public goods" (things that benefit everyone and have zero marginal cost) in a sustainable manner? And if we have many public goods, how to prioritize which ones to provide more? And if these public goods are like open source software where people have a tendency to forever fork projects and keep them going (much like religions), can we incentivize them to, you know, maybe work together on things that are kinda the same? Could we devise a mechanism to solve all those problems? And make people pay for it? Apparently, yes.



***Introducing the "liberal radical" mechanism, a.k.a. "quadratic voting/funding":***

![image.png](https://mail.google.com/mail/u/0?ui=2&ik=731b35a246&attid=0.1&permmsgid=msg-a:r4571912949660444234&th=171e73a80c1bb003&view=fimg&sz=s0-l75-ft&attbid=ANGjdJ_cwzfexIPcgoVduXHlDzXvr7grfn-4qetHSAO1jfUHJr6rawZhc67bhQpHmEDbLKt5Bzk3SaTAeW2tFROXSPDunlfMdrlg6U9sNzDOE4LHbL47uK081mNuQVw&disp=emb&realattid=ii_k9uii6dq0)

Where project **p** receives funding/endorsement **Fp** . Each citizen **i** can decide how much money/votes (**cip**) they want to contribute to public good **p**, then you take the square root of that, sum these square roots of individual contributions for a given public good, then take the square of that, and that's how much funding/votes/endorsement that public good received.



If you're a benevolent dictator which would like to exhort people to voluntarily contribute to public goods projects they think are good, so that you too can support the things people think are good, this is a pretty interesting way to do it! Here's what it looks like graphically, [as explained by Vitalik Buterin](https://vitalik.ca/general/2019/12/07/quadratic.html):



![image.png](https://mail.google.com/mail/u/0?ui=2&ik=731b35a246&attid=0.2&permmsgid=msg-a:r4571912949660444234&th=171e73a80c1bb003&view=fimg&sz=s0-l75-ft&attbid=ANGjdJ--U9T6sbj-Pax6iCzu4tUMZ0KG7F4vOafrvCK2Ta_uU-JVjkkrVcMm1WaAfaW3Z_YdXoJkajeZEIKqifPm77fOhfDS_ot_gumIP4Tj6UYM_-jGq5qyusucsQQ&disp=emb&realattid=ii_k9uiqanb1)



By staring at this picture, you can immediately see some of the most interesting properties of quadratic voting/funding:

* You get more endorsement/funding(if we're talking about voting/funding respectively) per vote/buck if several people vote/invest a small number of votes/bucks instead of a few people giving a large number.
* If you have two projects (public goods) of equal size (meaning the total contributions + subsidy) you can get twice as much by combining them into a project double the size

And if you think some more you also see a big red flag: if you can split votes/bucks over identities, or simply collude with other people to vote a certain way, you can significantly benefit the projects of your interest. But other voting systems also [suffer from the identity issue](https://www.bbc.com/news/world-us-canada-38746559). And we should note that it becomes harder to collude as we get more and more people voting.



These, and many other properties of quadratic voting/funding, plus some extra possibilities and adaptations, is explored in detail in a lovely paper (it was published by SSRN but the preprint is better as usual) by Vitalik Buterin, Zoë Hitzig and Eric Glen Wey with the funny title (explained in the conclusion) *[Liberal Radicalism: Formal Rules for a Society Neutral among Communities](https://arxiv.org/pdf/1809.06421.pdf)*



[](https://arxiv.org/pdf/1809.06421.pdf)Sounds good you say, but what about trying it out in practice? Well! Turns out that they've been using such a mechanism to get people to donate to software projects (mostly related to ethereum) and decide how to allocate an extra pool of money over the projects using a platform called [gitcoin](https://gitcoin.co/results) (poorly named, it's not yet another crypto scam, it runs on ethereum). They've had 5 rounds of funding, with tweaks in the mechanism between each round, and Vitalik wrote about rounds [3](https://vitalik.ca/general/2019/10/24/gitcoin.html), [4](https://vitalik.ca/general/2020/01/28/round4.html) and [5](https://vitalik.ca/general/2020/04/30/round5.html). The latest addition is "negative funding", so that you can short things you don't believe in (like Bitcoin) or that are a net negative to society (like hate speech).



Love it? Hate it? Don't really care? Well you should come to sovcall tomorrow all the same! Join us at [https://caltech.zoom.us/j/​4359087668](https://caltech.zoom.us/j/4359087668), Wednesday 6PM PST, wherever you are.





See you then



Eduardo



PS: I've only been learning about this stuff since...Saturday. That's why the email was so short. Expect me to continue blabbering about this for weeks to come, unless someone volunteers to present something else. In the unlikely even you did get really hooked into this mechanism design stuff ideas, take a look at [this 20 page summary](https://vitalik.ca/general/2020/04/30/round5.html), compiled by the Economics Nobel prize committee, because in 2007 they gave the prize to the guys that laid the foundation of mechanism design.