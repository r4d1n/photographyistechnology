---
title: "Exploring the Amazonian Cloud"
author: Jared Radin
layout: post
permalink: /2015/the-amazonian-cloud/

categories:
- technology
tags:
- paradigm shift
- industry
- silicon valley
- amazon
- big tech companies
- internet
- web
- economy
- the cloud
---
<figure>
<img src="/assets/2015/10/aws-loft/pop-up-loft-sign.jpeg" alt="outside the amazon web services pop-up loft on Market Street in San Francisco" />
</figure>

Amazon is a high profile company with a lot of customers, that faces criticism (from critical folks) for its labor politics (but not as much as Uber). This was highlighted most recently in a New York Times piece about the experiences of some white collar employees in Seattle, though by all accounts working in the warehouse is more brutal.
However, as far as I can tell, most people who don't work in technology are unaware of Amazon Web Services, the company's cloud-computing infrastructure, which ([according to Wikipedia](https://en.wikipedia.org/wiki/Amazon_Web_Services)) was productized as a source of additional revenue after being designed and built initially to support Amazon's retail operations.
Apparently (again, skimming the Wikipedia) customers include not only Pinterest and Netflix, but also NASA and the CIA.

<!--more-->

The platform and its many services are actually kind of amazing and enable individuals to do incredible things (of course, so long as those things require on-demand computing power, vast networking capabilities, and/or highly available storage). So when I had the opportunity to attend a training session at the Amazon Web Services "Pop Up Loft" in San Francisco, I was eager to attend both for technical reasons and because the company is an intriguing agent in the unfolding present day.
I have purchased a wide variety of goods from Amazon, but the company runs no physical store. The closest thing there is to going "to" Amazon, aside from infiltrating an office, would be browsing to their website. I was curious to see what this space would be like, and excited to learn how to make use of the cloud.

One of my coworkers who is a big fan of AWS likes to say that it makes developers into a one person army. It is indeed a powerful feeling to spin up and destroy virtual servers en masse, to set rules that will do so automatically, to quickly connect to various types of basically bottomless storage, and to make it all accessible from anywhere in the world. Basically, things that would have required massive expense and the commissioning of physical computers (perhaps even buildings) ten years ago.

[This lecture by Douglas Crockford](https://youtu.be/JxAXlJEmNMg) contains a great history of the development of personal computers and the web that describes various iterations of computers such as single processors requiring highly specialized facilities to run, as well as the use of teletype terminals from which one could utilize a mainframe computer remotely, paying to use its computing power when necessary without owning the entire machine.

In a way, the rise of cloud computing seems like a shift to a paradigm that parallels that of terminals and mainframes. Nowadays, many people use smaller, less powerful computers like smartphones and tablets, not just alongside but instead of laptops or desktop PCs.
Some applications on smartphones are mainly used on the device itself, like games or photo editors, but for the most part such devices are typically used to access a variety of web services, like email, social media, file storage, banking, shopping, etc. The phone runs a client app (or is pointed at a website) that communicates over the network with a central system where the main computation happens and information is stored.
I think the similarity to a mainframe with a teletype terminal is most apparent in Chromebooks, which have are designed to be used almost exclusively with and Internet connection, since the use of cloud storage and applications like Google Docs integrated directly into their operating systems, but the idea is still pretty similar to how phones are used, except they also double as point-and-shoot cameras.

A shift is thus occurring in the whole definition of personal computing and the place of general purpose computers in society going forward. My "real" computer is at this point used almost entirely for particular purposes that require local computational power -- either photo and video editing or programming -- and I noticed when I first got a smartphone that I ended up spending a lot less time sitting at my desk aimlessly browsing the web after checking my email, because I no longer sat down at my desk to check my email at all.

This is pretty cool, but at the same time it also means that a lot more people who use computers will not necessarily be able to tinker and understand how they work, because these devices are usually more locked down than a full-blown machine where it's easy enough to install your own operating system and any software you want. This is good for security and reliability but I do worry about the obfuscation of underlying mechanisms and the propagation of the sense that technology really is magic.

From my perspective as a developer and as an artist who is interested in incorporating computers into my practice, the cloud represents both a tremendous potential asset and a fascinating subject in and of itself. At the workshop I learned some of the basics of using the primary AWS offerings, like EC2 servers, load balancers, and the managed relational database service, and also gained some insight into what the plethora of other services are used for. The whole thing is an astounding technical achievement and I am looking forward to hosting sites or applications of my own on AWS, or maybe making use of EC2 or Lambda to run some web scrapers.
Better understanding the scope of Amazon's cloud business also gave me a lot to think about in terms of the role of infrastructure companies in shaping how the Internet is organized and run, and the differences between physical infrastructure and the infrastructure that has unfolded for the web.

In the physical world, infrastructure like roads and bridges are built and maintained by the government.
It seems important that these are part of the commons, even if they are frequently hindered by corruption and negligence, [if not outright disregarded](http://www.infrastructurereportcard.org/).
The roads in my current neighborhood are not well maintained and apparently [even the new Bay Bridge has some serious flaws](http://sfist.com/2015/06/24/bay_bridge_bolts_show_more_ominous.php). Still, the idea of private roads and bridges seems kind of dystopian.
But then no public service come close to something like AWS, which is obsessively engineered to be excellent and work perfectly 99.9999% of the time.

The libertarian idea that government can't do anything but hinder beautiful private innovation is common in Silicon Vally, and the tension between public and private projects is a frequently debated, highly contentious subject in modern American politics. Personally, [I am starting to feel that there is rarely a catch-all solution to political problems and the best way lies in flexible acceptance of diverse answers as necessary depending on the task at hand](https://youtu.be/wY6454QetqM). But that may be a little subtle for the mainstream discourse at this time.

Though ARPANET was a government project, the modern web is largely governed by privately held companies, from Service Providers, to hosting companies, to web-based applications, services, and stores. While anyone can still set up a computer at home to serve their hand-rolled personal site, entities like Google or Facebook, who have made the web more usable and useful to billions of people, maintain control over what is widely disseminated. This can all get very meta very quickly, when your social network is running on AWS servers, and users are accessing them over AT&T connections, and the switches there are tapped...

The network gets Pynchonian pretty fast.

Mostly what I am curious about now is if the difference between the execution of the Bay Bridge versus AWS (to simplify things dramatically) is inherent in the two styles of institutions, and whether there can be democratic organizations that are also resilient and resolute enough to bend, grow, shed as the scenario demands.
Would they be able to make the technological leaps that may be required, say, to create the sorts of sustainable mega-cities that would characterize a more successful human future?

Uber is a really interesting example here, because it seems like their blue sky ambition for the long term is to build basically a network of autonomous buses around the world. Basically physical infrastructure, more closely aligned to areas that the state already controls. But then, why can't there just be high speed trains that go from any part of a city to any other part? Are cities that depend on cars really a good idea in the first place?

I wouldn't argue that BART is a very successful service, but is that because of the nature of government, or because of the way it's viewed and treated? Uber raised venture capital, public services take taxes. That's definitely near the root of the aggression toward public services that appears among some American policymakers, entrepreneurs, and (especially) grassroots conservatives. Uber started from scratch a few years ago, the government and BART are working with legacy institutions and infrastructure that was not necessarily planned with the unfolding present or impending future in mind. That's not really an accident, though, or an excuse. Why are there broken bolts on a brand new bridge?



<figure>
  <img src="/assets/2015/10/aws-loft/cloud-kegerator.jpg" />
  <figcaption>
    In addition to co-working space, technical tutorials, and one-on-one consultations with AWS experts, the loft has a cloud connected kegerator that uses several AWS products to track and visualize the duration and volume of beer pours.
  </figcaption>
</figure>
