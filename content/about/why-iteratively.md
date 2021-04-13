+++
author = "Matt Wildoer"
title = "Why Iteratively"
date = "2020-03-13"
description = "What I do best"
tags = [
    "R&D", "Right First Time", "Fail Fast",
]
+++

**Right time time vs. fail fast**

German engineering is renounded world-wide as the most rigorous, precise and high-quality. Undeniable drivers behind this rigour are the strong cultural traits of planning, rule-following and strong self-discipline. The cliched German waiting at the pedestrian lights in the middle of the night in pouring rain does, at least in broard strokes, rings true - especially regarding work. Engineering can be considered an exercise in rigorously planning. How strong is a material? What load will an component see in its life? High-quality manufacturing can be seen as meerly an exercise in precision rule-following, seeking and eliminating and deviation. 

So what's the problem? Create a plan, execute the plan, profit. Right?

Well, sort of... To quote Mike Tyson; "Everyone has a plan until they get punched in the mouth." And boy, I'm not sure about you, but I have never been on an aggressive R&D project without a couple of whammies.

The first issue here is that most of the time you're unlikely to even know what you are precisely trying to achieve, your destination if you will. Perhaps you aren't even yet sure how to define it! In aerospace and automative this issue is heavily alleviated for safety and reliability. Billions of dollars have been poured directly into creating high-quality guidance and regulation based on hard-learned lessons from past mistakes, in an effort to avoid repeating them. The same cannot be said for when business gets involved with cost targets, weight targets or - god forbid - "user experience" 😉. Beyond the sheer complexity of integrating so many factors into a single equation, the cost of doing so is enormous. These factors cannot simply be ignored or left to the personal preference of the engineering implementing the design. Poor safety or reliability are both great reasons to *avoid* a product or service, but a good user experience or exceptional performance are the factors which actively *compel* a customer to buy your product - after all, often enough "no purchase" is also a frequently available option. The pitfalls of letting engineers collectively design a product to their individual preferences should be evident to anyone who has spent any time in an engineer's home. 

The second issue is the accuracy of data. The premise of R&D is that you're doing something new, something novel, something innovative and - hopefully - something uniquely valuable. If you can confidently specify precisely what you're creating and how you're going to create it, that's great! But if it is sufficiently novel, innovative or new you'll be hard-pressed justifying that confidence. The compounding uncertainties introduced as you extrapolate further away from solid ground make claims that you can confidently engineer a safe, reliable, high-performance, manufacturable and wonderful-to-use system based on this information dubious at best. 

This leads my do my "exponential cost-complexity hypothesis"; as the complexity of a system increases, it's development cost increases exponentially. Complexity shouldn't be considered as things as obvious and mundane as part count either. No, complexity entails all the factors you haven't already specified completely; missing requirements, inaccuracy of data, UX, GUI, manufacturing, maintenance, deployment, supply chain or otherwise. If you're uncertain, all these factors quickly multiply because there are at least two candidate solutions for each unknown. If you double the complexity of your project through uncertainty, your development cost to resolve a functional solution, let-alone an even minimally optimised one, will grow exponentially. 

Okay, so I'm doing a lot of complaining, but how do we develop novel things better then?

You have to be willing to fail. 

