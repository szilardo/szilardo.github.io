---
title: Profit Drain
author: Szilard
layout: post
---

It is good fun working on projects that present interesting challenges. One of the best feelings I can get is 
when I can make significant progress in a short period on the project itself, 
without having to constantly change things in build systems or other non product related things. 
Unfortunately many projects have problems that involve these bothersome auxiliary systems. 

One of these problems that drives me nuts is build times. Having to wait multiple hours 
for builds to finish, after making only a few changes, is no fun. 
Sometimes there is nothing one can do, or people might not want to make larger changes in their build setups. 
Fixing the issue is a worthwhile investment for myself, it can improve the quality of life by a huge amount. 
Luckily people on these kind of projects tend to agree that shorter build times are a good thing. 
I know it improves my morale when I work on the project that previously built in hours and now can be built in a few minutes 
or even seconds. Improving the situation can sometimes be a huge pain, 
but there are a few ways to improve these build times: by splitting the project, building only what changes, 
using unity builds, caching object files, deduplicating code, dropping heavy templates, using precompiled headers or using 
distributed builds. 
If nothing can be done, in time the frustration caused by the bullshit will eventually lead to 
the conclusion that life might also be too short to work on these projects. People get angry, break down, and leave..

Having had worked with multiple slow building projects has frustrated me enough to try to increase the urgency of 
fixing long build times. One approach is to measure build times and show the business oriented people 
how much time is spent on builds every day. In many cases these slow builds block people from doing work
(waiting on the build to test something?), or it makes people work on something else in the mean time
(but context switching breaks developer focus). The wasted time keeps increasing and so does the co$t. 
I've written a small tool to do the measurements and I'd like to share it with other people 
that may be suffering: [Profit Drain](https://github.com/szilardo/profitDrain).

Till next time! See ya round..

Szilard
