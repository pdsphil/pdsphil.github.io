---
title: Optimizing Heroku Apps
permalink: /optimizingherokuapps/
---

# Optimizing Heroku Apps

## Who and Why?

Who is this Phil guy and what does he know about optimizing Heroku apps? I got involved with Rails in 2004, and went on to do freelance Rails work full-time for over five years. More recently, I helped start the Support team at Heroku, built and grew the Customer Solutions Architecture team, then stepped aside to start a new role at Heroku, the Data Solutions Architect. During this time, I’ve worked with a huge variety of customers and their apps. At Heroku alone, I calculate I’ve worked with well over 5,000 different applications.

A few years ago, after talking with Heroku customers at meetups and conferences, I began to realize I was in a somewhat unique position: I had expert technical knowledge of how to support and scale Rails applications (and other frameworks, but my strengths are definitely in the Rails world), yet I also had the experience of countless interactions with actual customers of Heroku, either through support tickets, phone calls, or in-person.

I began to see common issues and topics emerge in these conversations. Some of these issues were resolved or made easier-to-fix via work on the Heroku side - updates to Dev Center articles, changes to the Heroku CLI, etc. But despite continuous Heroku improvements, other issues are destined to be encountered by nearly all active Heroku applications at some point. I looked at these other issues, and started thinking about how I could do my small part to address them.

The result is the [Optimizing Heroku Applications](/OptimizingHerokuApps.pdf "Optimizing Heroku Apps Guide") guide.

## The Guide

I wrote the guide in mid 2013, so it’s a bit dated now. However, many of the concepts and topics I discuss are still relevant. Active apps will always have issues pop up (whether on Heroku or elsewhere), and this guide provides a good overview of how to diagnose those issues.

I self-published the guide, which was an interesting project on its own. I made some money, but I never had the marketing machine behind it that one needs to make serious money. It was a nice side project, and it even got me a conversation with a leading tech publisher about turning the guide into a full-on “Heroku book”. That’s a story for another time though.

In the end, I decided to shut down the project after about two years and focus on something else. There’s still a lot of good content and topics in the guide for Heroku customers, so I wanted to make the guide [freely available](/OptimizingHerokuApps.pdf "Optimizing Heroku Apps").

So what exactly is this guide? Let’s start with what the guide isn’t. This guide is not an introduction to Heroku. It’s not an all-encompassing guide to the entire Heroku platform. There are plenty of guides or books in the community if this is what you are looking for. In particular, I recommend the following if you are looking for a ‘Heroku 101’ style overview:

- [Professional Heroku Programming](https://www.kobo.com/us/en/ebook/professional-heroku-programming "Profession Heroku Programming Book")
- [Heroku Up & Running](http://shop.oreilly.com/product/0636920027409.do "Heroku Up & Running")
- [The Heroku Hacker’s Guide](https://gumroad.com/l/zvMS "The Heroku Hacker's Guide")

Now, for what this guide is. If you are running production applications on Heroku, this guide is for you. I cover some basic concepts, some common errors you’ll likely encounter, then I look at some scenarios your app will likely see over its lifetime. I also cover some more advanced topics in later chapters.

The guide is [freely available here](/OptimizingHerokuApps.pdf "Optimizing Heroku Apps").
