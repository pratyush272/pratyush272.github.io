---
layout: post
title: "How to code efficiently"
date: 2017-01-21
categories:
  - Programming
description: 
image: https://source.unsplash.com/xekxE_VR0Ec/2000x1200
image-sm: https://source.unsplash.com/xekxE_VR0Ec/500x300
---
I like coding. I don’t wait and plan and draw flowcharts and dry run algorithms. It takes the fun out of it. Adding an extra feature is usually not a problem at all. However changing the way you solved a module and adopting a new method (upon direction from a supervisor), which is not the way you would rather do it, is very frustrating. I consider programming as an art, which just like art forms expresses your personality. So there shouldn’t be a check list. There are indeed certain things that must be kept in mind, if it doesn’t come naturally. That however doesn’t mean you have to figure out every detail beforehand.

1. The code must be readable, maintainable, optimum and efficient. All of these are entirely different things and usually equally important. 
2. An algorithm must be analysed to determine its resource usage. Which algo is more efficient can not be determined by comparing various resources directly.
3. If the length of code is important, it would need through planning. However the the code footprint is no indication of how lightweight your app is going to be.
4. I never try to tackle the whole problem right away. I code modules to arrive at an intermediate solution and then call the modules. Such modules are independent of each other and it makes it easy to add a new feature later. Plus it helps in avoiding redo of a procedure.
5. Choice between universality and efficiency should be based on the kind of app, its memory footprint and resources available (eg. amount of RAM). In case an app has to run for a long time (may be in background) memory leak is the most imp. thing that need to be planned.
6. To check memory leak, here are some points to keep in mind- Avoid using unnecessary pointers, Avoid using statements that result in too many machine instructions (eg. Clever use of static mapping between keys and values can avoid many else-if , try not to use multiple variables to represent the same state, remember to reclaim the unused memory.
7. I improve my code in iterations. Solve the problem anyhow, fix bugs, patch up leakages, rip out the vestigial parts and at the same time keep thinking of a new way to solve a module.
