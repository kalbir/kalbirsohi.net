---
layout: post
title:  "5 articles that shaped my thinking about platform as a service"
date:   2016-03-29 10:38:42 +0000
categories: writing platform tech
---

(cross posted on <a href="https://blog.drie.co/5-articles-that-shaped-my-thinking-about-platform-as-a-service-88480dab4ed5">the drie blog</a>)

Here at <a href="http://drie.co">drie</a> we think that platform as a service is genuinely effective as one tool in your toolkit for solving a wider business problem &#8212; how do I make the cost of IT change small.

<!--more-->

If you can make the cost of IT change small you can reduce risks in systems that you run and get interesting, novel and useful products in front of your customers quickly. You can test ideas without spending too much money and build on the ones that work.

Understanding how platform as a service fits into this can be difficult, and no number of "IaaS vs PaaS vs SaaS" slidedecks are going to get you there. Here are 5 thought provoking, well written, articles that have shaped my thinking about platforms and how they can help you to achieve genuine value in delivering IT:

## 1. <a href="http://pmarchive.com/three_kinds_of_platforms_you_meet_on_the_internet.html">3 kinds of platform you meet on the internet</a>

This was recommended to me by <a href="https://twitter.com/ejhp">Etienne Pollard</a> (along with <a href="https://gist.github.com/kislayverma/d48b84db1ac5d737715e8319bd4dd368">Steve Yegges's rant</a>) as my starting point for thinking about the technical underpinnings of digital services. Marc Andreessen sets out a clear statement of what a platform is, for those of us sufficiently opinionated to care:

> If you can program it, then it's a platform. If you can't, then it's not.

Andreessen explains that a platform is a system that can be customised by developers and in doing so lays out some of the key principles to have at the forefront of your mind when building an effective platform as a service: your system is running <i>other people's</i> code and your users are people in the business of writing code.

## 2. <a href="https://blog.heroku.com/archives/2009/2/23/why_instant_deployment_matters">Why instant deployment matters</a>


I remember this short, data driven post from Heroku feeling super provocative when it came out, but the idea that we should be able to measure how long a deployment takes in seconds rather than minutes or hours is reasonably commonplace now. However, the reasoning behind that idea is key. This post sets out how as we decrease the cost of IT change in other areas infrastructure can remain a bottleneck and why that is not good enough when we are aiming for small, speedy and safe changes.

## 3. <a href="http://www.annashipman.co.uk/jfdi/building-a-paas.html">Building a platform to host digital services</a>


<a href="https://twitter.com/annashipman">Anna Shipman's</a> blogpost (also on the <a href="https://gds.blog.gov.uk/2015/09/08/building-a-platform-to-host-digital-services/">Government Digital Service blog</a>) gives a clear and succinct outline of some of the business problems that you can solve by building a platform, not least that you don't have multiple teams solving the same problem (e.g. how to deploy an application) over and over again.

Anna also captures some interesting features of a platform that are important to government (and I expect, lots of big organisations) users; multi-tenancy and self service. She has written follow up posts on the topic that show the evolution of the thinking of the government platform as a service team at GDS: <a href="https://gdstechnology.blog.gov.uk/2015/10/27/looking-at-open-source-paas-technologies/">here</a> and <a href="https://gdstechnology.blog.gov.uk/2015/10/27/looking-at-open-source-paas-technologies/">here</a>

## 4. <a href="http://continuousdelivery.com/2012/10/theres-no-such-thing-as-a-devops-team/#more-827">There's no such thing as a devops team</a>

This post by <a href="https://twitter.com/jezhumble?lang=en-gb">Jez Humble</a> echoes sounds like a rant but it at its heart a subtle re-statement of what is important about movements like devops and continuous delivery: making it safe, reliable and fast to make IT changes. Jez uses the provocative title to walk through key points about effective software delivery including the danger of building functional silos.

He brings it all back together at the end of the post by restating what an operations team can do to be an effective part of the software delivery chain, something that resonates very strongly with me as it is almost exactly the way we were set up to deliver in <a href="https://hmrcdigital.blog.gov.uk/2015/07/30/laying-the-foundations-for-hmrcs-digital-services/">my previous role</a>.

## 5. <a href="http://www.wired.com/2015/03/disney-magicband/">Disney's $1bn bet on a magical wristband</a>

A little bit leftfield for my final selection but an article that has had a profound impact on my thinking about platforms over the last year, so much so that I started an internal "Wristband" project at HMRC to try to implement some of the core ideas here. This Wired article describes how Disney went about radically reworking the way that people interact with their theme parks to make a single interface to control all customer interactions with the park.

Disney's thinking here was bold and revolutionary but also driven by business realities. The article is peppered with examples of how data and interaction design allowed Disney to improve customer experience in the parks:  making it easier for people to pay for their drinks meant that they bought more of them, tracking where people where in the park at a meta level allowed Disney to better manage traffic flow and put their employees in the right place at the right time.

"How does all of this related to platform as a service?!" You may ask. The wristband that Disney invented is a system for making it easier for customers to complete tasks that were slowing them down without them realising it, reducing the flow of people through the Disney experience and making it harder for Disney to focus on their core business: delighting people. If that isn't a great metaphor for how platforms can improve your business model, I don't know what is!
