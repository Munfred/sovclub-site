---
title: Learning things "Empirically"
subtitle: " (with data - shocking, I know) 📊📶 📉 📈 💹 📋 🏢"
category:
  - Weekly Discussions
author: Eduardo
date: 2020-04-15T21:00:00.000Z
featureImage: /uploads/sovball.png
---
Over the past week and a half or so, I have been becoming acquainted with some of the field of the social sciences. For example, I learned that when you do an "empirical" study, that means doing linear regression on some dataset that you found, got access to, or somehow compiled. It seem's that's where all the non theoretical quantitative knowledge we have about society came from. I learned all that from reading [four papers](https://drive.google.com/open?id=1LWNRGxaEREhD-ZNOXF_gZgp2-IEe4d8u) and [trashing](https://drive.google.com/file/d/1X9Ned0Lh-oTdK131te4X-VPzWZf7plnY/view?usp=sharing) [one](https://drive.google.com/file/d/1LWNRGxaEREhD-ZNOXF_gZgp2-IEe4d8u/view?usp=sharing) of them.



That is an...enlightening realization. It is also somewhat enticing. It might be that the bar for making real progress in the social sciences is so low that it might be underground. I keep thinking that if you just sprinkle some blockchain machine learning fairy dust on a social science dataset you might actually get a paper. Don't believe me? Think things can't be so easy? Well, let me tell you this inspiring story then: Caltech has this prediction challenge class [CS156b](http://cs156.caltech.edu/covid/) where anyone at Caltech, enrolled or not, can take a stab at predicting the future of Coronavirus deaths in the US. Last week our very own Michael submitted the following braindead model, just so **sovclub** (yes that is the team name) would get something in. In his own words:



> *"It's really brain dead simple: I assume a constant fraction of everyone who's going to die on day i would already have gotten tested by day i-n, where n <= 14 days. I plot (deaths on day i) vs. (cases on day i-n) for all counties, and for each num. cases, I calculate the percentiles of deaths and then the prediction would simply be looking at how many confirmed cases there are today and calculating the percentiles likewise. So anything else we come up with should beat this benchmark, or else it's not worth pursuing.” <- He just said what everyone else did is not worth pursuing, you'll see in a second.*
>
>

And then this week we got an email titled **"sovclub report"**. And my first reaction was thinking *"Oh shit, I always knew sovclub wasn't a real safespace, I couldn't just say whatever I wanted, darn, it was really a kind of public forum and even with the first amendment, in a university setting, if people take offense, in the current climate..."* and then I open the email and realize that it's taking about sovclub ***the team*** and that ***report*** refers to providing a report describing the model submitted because we got...first place. Yeah. Half of the Caltech undergrads competing in this class, and then some, and it's the team with me and Dylan on it that get first place? [The take home message here is very clear.](https://docs.google.com/document/d/1KgarjUbmeWHhUzMDuL23L8s3hVDxaN7YXFJFGTgv3CU/edit?usp=sharing)



If the bar for the realm of stuff literally the entire world and the smartest people in the world are thinking about is this low, what about the bar for the realm where almost exclusive non quantitative social and political science majors think about? How much low hanging fruit - its actually probably on the ground really - is there to grab?



To that end, this week I'd like to get the smart, eclectic membership of sovclub thinking about the datasets about the social aspects of the world that we have out there, and what kind of clever things we could do with them. One interesting website providing tons of nice data is [Gapmider](https://www.gapminder.org/). It has [loads of data for download in csv or excel format](http://gapminder.org/data/) ready to be loaded into Python. But they also have some interesting stuff to make you think about the world, you know, like this [dollar street](https://www.gapminder.org/dollar-street/matrix) project where they went to the houses of hundreds of families across the world over different income levels and took thousands of pictures of everything in their homes. It's kinda like an economic voyeur fetish kinda thing. I liked it, not gonna lie.



And another database I learned about last week is this [Luxembourg Income Study Database (LIS)](https://www.lisdatacenter.org/our-data/lis-database/) where they got some really detailed economic data on dozens of countries over several years. The data seems to be really good, but unfortunately it's shockingly not directly accessible. You need to write a script in [R, SAS, SPSS or Stata](https://www.lisdatacenter.org/data-access/lissy/) (\*ugh\*) to query the data and only get aggregate results. I can only imagine this is a cumbersome annoying process to iterate over, and you can't use Python. You see why progress in the social sciences is so slow and haphazard... on the upside, I managed to get an account and I guess I can submit jobs there now, if I could be bothered to learn their syntax and suffer through R...and so could you, I guess. But anyway,



Join us Wednesday April 16 at 6PM PST on this link [https://caltech.zoom.us/j/​4359087668](https://caltech.zoom.us/j/4359087668) to talk about learning things with data! And beer! (or any alcohol of your choice).



In Sovereignty,



Eduardo





PS: I've been rather disappointed with the **lack** of virtual happy hours and socializations happening since the beginning of the great lockdown... So I'd like to take upon myself (and all of you) to rectify that. Would people be keen on having a **regular sovbeer bullshit exclusive hour** on Friday, Saturday or Sunday, in addition to the Wednesday calls? Let me know.



PSS: In lieu of the physicality of Mr. Raffles, we might have created a new virtual mascot, **[sovball](https://docs.google.com/presentation/d/1V49UVANpeuGn00t4qEyJka1So26oxbi43mls8ImrHnU/edit?usp=sharing),** which can be readily inserted into any imaginary narratives, ideally involving country balls. Can you surprise us with any?