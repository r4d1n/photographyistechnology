---
title: "Cloud City"
author: Jared Radin
layout: post
permalink: /2015/cloud-city/

categories:
- technology
tags:
- paradigm shift
- industry
- silicon valley
- amazon
- cities
- artificial intelligence
- big tech companies
- internet
- web
- economy
- the cloud
---
<figure>
<img src="/assets/2015/10/aws-loft/pop-up-loft-sign.jpeg" alt="outside the amazon web services pop-up loft on Market Street in San Francisco" />
</figure>

As far as I can tell, most people who don't work in technology are unaware of Amazon Web Services, the company's cloud-computing infrastructure, which ([according to Wikipedia](https://en.wikipedia.org/wiki/Amazon_Web_Services)) was productized as a source of additional revenue after being designed and built initially to support Amazon's retail operations.
Apparently (again, skimming the Wikipedia) some of the more high profile customers include not only Pinterest and Netflix, but also NASA and the CIA.

The infrastructure on offer for on-demand, ad-hoc use is actually kind of amazing, and enables individuals to do incredible things (of course, so long as those things require stuff like virtual computing power, vast networking capabilities, and/or highly available storage). So when I had the opportunity to attend a training session at the Amazon Web Services "Pop Up Loft" in San Francisco, I was eager to attend both for technical reasons and because the company is an intriguing agent in the unfolding present day.

One of my coworkers who is a big fan of AWS likes to say that it makes developers into a one person army. It is indeed a powerful feeling to spin up and destroy virtual servers en masse, to set rules that will do so automatically, to quickly connect to various types of basically bottomless storage, and to make it all accessible from anywhere in the world. Basically, computing infrastructure that would have been massively complicated and expensive to build ten years ago can be orchestrated from a laptop without getting out of bed.

[This lecture by Douglas Crockford](https://youtu.be/JxAXlJEmNMg) contains a great history of the development of personal computers and the web. He describes various iterations of computers such as single processors that took up whole rooms and required specialized facilities to run, and teletype terminals from which one could utilize a mainframe computer remotely, paying to use computing power when necessary without owning or maintaining the entire machine.

In a way, the rise of cloud computing seems like a shift back to a paradigm like terminals and mainframes. Nowadays, many people use smaller, less powerful computers like smartphones and tablets, not just alongside but instead of laptops or desktop PCs.
Some applications on smartphones are mainly used on the device itself, like games or photo editors, but for the most part such devices are typically used to access a variety of web services, like email, social media, file storage, banking, shopping, etc. The phone runs a client app (or is pointed at a website) that communicates over the network with a central system where the main computation happens and information is stored.
I think the similarity to a mainframe with a teletype terminal is most apparent in Chromebooks, which are designed to be used almost exclusively with an Internet connection, since cloud storage and applications like Google Docs are integrated directly into their operating systems, but the idea is still pretty similar to how phones are used, except they also double as point-and-shoot cameras.

A shift is thus occurring in the whole definition of personal computing and the place of general purpose computers in society going forward. My "real" computer is at this point used almost entirely for particular purposes that require local computational power -- photo and video editing, programming, games -- and I noticed when I first got a smartphone that I ended up spending a lot less time sitting at my desk aimlessly browsing the web after checking my email, because I no longer sat down at my desk to check my email at all.

This is pretty cool, but at the same time it also means that a lot more people who use computers will not necessarily be able to tinker and understand how they work, because these devices are usually more locked down than a full-blown machine where it's easy enough to install your own operating system and any software you want. This is good for security and reliability but I do worry about the obfuscation of underlying mechanisms and the propagation of the sense that technology really is magic.

From my perspective as a developer and as an artist who is interested in incorporating computers into my practice, the cloud represents both a tremendous potential asset and a fascinating subject in and of itself. At the workshop I learned some of the basics of using the primary AWS offerings, like EC2 servers, load balancers, and the managed relational database service, and also gained some insight into what the plethora of other services are used for. The whole thing is an astounding technical achievement and I am looking forward to hosting sites or applications of my own on AWS, or maybe making use of EC2 or Lambda to run some web scrapers.
Better understanding the scope of Amazon's cloud business also gave me a lot to think about in terms of the role of infrastructure companies in shaping how the Internet is organized and run, and the differences between physical infrastructure and the infrastructure that has unfolded for the web.

In the physical world, infrastructure like roads and bridges are built and maintained by the government.
It seems important that these are part of the commons, even if they are frequently hindered by corruption and negligence, [if not outright disregarded](http://www.infrastructurereportcard.org/).
The roads in my current neighborhood are not well maintained and apparently [even the new Bay Bridge has some serious flaws](http://www.sfgate.com/bayarea/article/Fears-of-failure-grow-for-rods-on-Bay-Bridge-6588743.php). Still, the idea of private roads and bridges seems kind of dystopian.
But then no public service come close to something like AWS, which is obsessively engineered to be excellent and work perfectly 99.9999% of the time.

The libertarian idea that government can't do anything but hinder beautiful private innovation is common in Silicon Vally, and the tension between public and private projects is a frequently debated, highly contentious subject in modern American politics. Personally, [I am starting to feel that there is rarely a catch-all solution to political problems and the best way lies in flexible acceptance of diverse answers as necessary depending on the task at hand](https://youtu.be/wY6454QetqM). But that may be a little subtle for the mainstream discourse at this time.

Though ARPANET was a government project, the modern web is largely governed by privately held companies, from Service Providers, to hosting companies, to web-based applications, services, and stores. While anyone can still set up a computer at home to serve their hand-rolled personal site, entities like Google or Facebook, who have made the web more usable and useful to billions of people, maintain control over what is widely disseminated. This can all get very meta very quickly, when your social network is running on AWS servers, and users are accessing them over AT&T wireless connections, and the switches there are tapped...

The network gets Pynchonian pretty fast.

As I am a curious person, I have a lot of questions about all this that will probably never be answered.

Is the difference between the execution of the Bay Bridge versus AWS (to simplify things dramatically) inherent in the institutions that built them?

Both AWS and the Bay Bridge were built by hierarchical organizations. One is fueled by data, motivated by the prerogatives of the marketplaces; the other is organized by Caltrans, a state agency, but contracted out to construction firms. What is interesting about putting it in these terms is that it seems like Amazon has a clearer reason to deliver the best possible result. They have to, in order to keep existing. But Caltrans has its sanctioned responsibilities, and that bureaucracy will continue to exist no matter what happens. This, of course, is part of the libertarian line of thought, which is compelling but again not wholly convincing since, from what I can tell, [there is as much incompetence and malfeasance in the corporate world as there is in politics](https://en.wikipedia.org/wiki/Financial_crisis_of_2007%E2%80%9308).

Can there be democratic organizations that are also resilient and resolute enough to bend, grow, and shed as unpredictable scenarios demand?

Will they be capable of making the technological leaps that may be required, say, to create the sorts of sustainable mega-cities that will likely characterize a successful human future over the next 20 years?

Uber is a really interesting example here, because it seems like their blue sky ambition for the long term is to build a network of autonomous bus-cars around the world. Basically physical infrastructure, more closely aligned to areas that the state already controls.

But then, why can't there just be high speed trains that go from any part of a city to any other part?

Who decided that so many American cities and suburbs should be organized around roads, and the ownership of cars? Was that a good idea in the first place?

Uber raised venture capital; government agencies take taxes. That's definitely near the root of the aggression toward public services that appears among some American policymakers, entrepreneurs, and (especially) grassroots conservatives. Uber started from scratch a few years ago, while Caltrans is a legacy institution dealing with legacy infrastructure is not in the cloud but stamped across the landscape already. That's not really an accident, though, or an excuse. Why are there broken bolts on a brand new, $6.5 billion bridge?

In Ursula Leguin's book *The Dispossessed*, a non-hierarchical anarchist society on a barren moon is run with the help of an AI that was originally developed on the Earth-like, state-dominated planet from whence the anarchists came. The computer organizes everything and assigns people work so they can collectively survive with few resources in a difficult natural environment. While anyone is free to ask for a different assignment or refuse to work outright, a culture in which individuals are shamed for endangering the group enforces conformity.
I find this book really interesting because a) it shows how the utopian society I sometimes dream of might actually be miserable and b) it predicates that society's development on the prior existence of a technologically advanced capitalist system, which ultimately made it possible for the moon colony to survive.

It seems like [artificial intelligence will be critical to the operation of successful cities](https://www.newscientist.com/article/mg22329764-000-the-ai-boss-that-deploys-hong-kongs-subway-engineers/) going forward.

What will cities run by software be like?

Will they make life great, like the experience of using Amazon Web Services to do powerful computing in the cloud?

Will there still be mistakes, like using bolts with the wrong threads to rebuild the collapsed Bay Bridge?

Will there be more or less accountability than there is today?

Who will live in the cloud city?

<br />

<figure>
  <img src="/assets/2015/10/aws-loft/cloud-kegerator.jpg" />
  <figcaption>
    In addition to co-working space, technical tutorials, and one-on-one consultations with AWS experts, the loft has a cloud connected kegerator that uses several AWS products to track and visualize the duration and volume of beer pours.
  </figcaption>
</figure>
