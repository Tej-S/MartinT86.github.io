---
layout: post
title: "Delivering Value"
description: "Delivering value consistently is important but you must look at where the value is coming from"
tags: [Value, Delivery]
---

Delivering value in small, consistent amounts is an important feature of working in a lean manner and enabling a good feedback loop to ensure you are delivering the most value possible. However, I was taught a lesson recently in thinking about my approach and not thinking one approach will fit every situation.

## Continuous delivery

Continuous delivery is where you aim to always keep your software in a deployable state, have the ability to complete automated deployments easily, and release small value changes often rather than large infrequent deployments. I'm a huge believer in the benefits of continuous delivery and it's something I always try and work towards whatever project I am working on.

Continuous delivery is a topic in itself so I'm not going to go in to too much detail here; Martin Fowler goes in to further detail [here](https://martinfowler.com/bliki/ContinuousDelivery.html).

## What is value?

Value can mean different things to different people. 

Gaining value from releases can be in the form of increased conversion, learning more about your market, or performance improvements to name just a few.

These are all valuable outcomes of releasing software, however it is important to keep in mind the actual goal of the software. If you haven't read [The Goal](http://martint86.github.io/the-goal/) you should definitely add it to your reading list. It warns of focusing on efficiencies in the wrong parts of your system. For example spending time making one part of your process super efficient when you have a bottle neck further down the production line is effort wasted. Similarly having a focus on the reduction in waste may seem like value added; however if that reduction in waste has a negative impact on your overall output it may actually be reducing value overall.

## My lesson learned

For a while now I've been working mainly on web projects where continously delivering tiny iterations can work brilliantly. Recently however I've been working on some native app projects. My immediate reaction was to "ship all the thingz" but I was reminded that native apps are not the web. A release will not mean refreshing the browser for a user but having to install an update. Not many users would want to update an app several times a day.

This is what made me start thinking of how the value is generated. In this instance value is generated from users using the app. I was too focused on releasing the software quickly, because something is not done until it is live. However, in my push for continuous delivery I was in danger of forgetting about where the real value came from. I was trying to optimise the wrong part of the system.

## Examples

After the revelation of getting a lots of tiny incremental updates out super fast isn't alway sthe best approach I thought I would have a look at how often some of the apps I use release updates.

Below are the average, maximum, and minimum number of days between the last 10 deployments for Netflix, Spotify and Twitter.

| Days between releases        | Netflix           | Spotify   | Twitter |
| ------------- |:-------------:|:-----:|:-----:|
| Average     | 3.5 | 4.4 | 6.5 |
| Max      | 11      |   11 | 8 |
| Min | 1      |    1 | 3 |

The data for this was collected from [APK Mirror](www.apkmirror.com).

These release times seem short and appear to contradict my eariler that delivering small incremental amounts doesn't work too well when not working on a web project. These times are short and I'm sure there are many teams out there who would be proud to be averaging a release every 4 days.

However, when compared to some of Netflix's deployment pipelines, 4 days is very long. For example, [here](https://medium.com/netflix-techblog/how-we-build-code-at-netflix-c5d9bd727f15) it shows that in some instances for Netflix, it takes 16 minutes from code check in to live deployment. 

## Don't get too stuck in your ways

This was a really welcome lesson of not getting too stuck in your ways and "this is the way things should be done".

Every situation is different and you always need to be looking at how value is generated and how it can be maximised. So in my situation, I guess it's important to find that balance between deploying quickly and efficiently while still making the end users happy by delivering updates that they will find valuable.
