---
title: Get up to speed with Kubernetes
date: 2019-02-17 13:31:25
tags:
---

I've been working with kubernetes for the past few weeks and am very impressed with its potential to orchestrate containerized microservices applications.

Although for beginners like me, in order to learn as much as possible about it,   I'd recommend trying to use kubectl (kubernetes official CLI tool) for everything, I understand that after a while, the work of editing and updating resources manually becomes a dull job.

In this post, I want to present to you some tools that are going to make your devops life much easier and productive.

* * *

### kubectx and kubens
Changing Contexts and Namespaces Faster

#### Contexts
Usually, when working with more than one cluster we need to switch between contexts: