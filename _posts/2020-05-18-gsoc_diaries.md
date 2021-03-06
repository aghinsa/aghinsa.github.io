---
layout: page
title:  "My GSoC Diaries"
date:   2020-05-18 10:00:55 +0530
tags:   gsoc,2020,gsoc2020,google summer of code
image: '/assets/img/posts/gsoc20/cover.png'
---

#### Links to follow ups
- [Weekly check in #0](/2020/05/18/gsoc_weekly_checkin_0/)  

Hey all,

I got to know about Google Summer of Code aka GSoC, from a friend of mine who had been selected the previous year.
I've been planning to explore open source and get the feel of things for a while, and here he's telling me that not only can I contribute to awesome projects but also get paid for it, *Hell yeah!!*. I started searching among previous GSoC projects to find something along my interests and expertise, that's when I stumbled upon [DataFlow Facilitator For Machine Learning (DFFML)](https://github.com/intel/dffml/), which takes part in GSoC as a sub org under [Python Software Foundation](https://python-gsoc.org/). DFFML makes it easy to generate datasets, train, use, deploy machine learning models, and integrate machine learning into new or existing applications. It's plugin based so you can define and add features, or easily adapt existing ones to your needs. Do check it out!

 At the time (which was almost a year ago) I was starting to dive more into Deep/Machine/Reinforcement learning and DFFML felt perfect. It was going to be [my first open-source interaction](https://github.com/intel/dffml/issues/29#issuecomment-539133619) and I was kinda nervous on how to start. Luckily the community has been very kind, especially John whos the maintainer of the repo. I've been part of the community since and been working on different parts of the code base, currently I'm mostly focused on the *DataFlow* side of things.

## My GSoC Project

 [Project proposal](https://summerofcode.withgoogle.com/projects/#5892754623692800)

 I'll be working on setting up a *Distributed Orchestrator* (I'll be using this term a lot, 1. it sounds fancy, 2. can't find anything else which is short and to the point :D). Currently the whole workflow of DFFML runs in a single machine, the crux of the project is to enable the DataFlow to run in multiple nodes. You'll get to know more about the project in the upcoming posts.