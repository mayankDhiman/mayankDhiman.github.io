---
layout: post
title:  "Week 1 to 3 aerspaceresearch.net"
date:   2019-06-19 03:10:14 +0530
tags: nothing
categories: jekyll update
---
This blog post is intended to pen down my experience of working with aerospaceresearch.net and on VisMa – Visual Math as a part of Google Summer of Code 2019. A part of this blog post will be about how it feels to be working here & other parts will focus on technicalities of the project (about how VisMa has been improved over the past three weeks).

Firstly, working with aerospaceresearch.net has been a great experience. The mentors of the project Shantanu, Manfred & Siddharth are very helpful. We almost regularly have chat on Zulip (& sometimes on WhatsApp) wherein we discuss the plans for the project and about implementation. Owing to these healthy discussions the project development is going at a fast rate (which is indeed a good thing!). The code base of VisMa is very well written and the complex task of simplifying mathematical equations has been beautifully coded. About the workload, I work regularly for 5 – 6 hours, but sometimes when a crucial bug finds its way in, the work time has to be increased. Overall it’s a Fun & Learn experience.

Now let’s talk about what we **(the VisMa Team)** have achieved so far. During the Community Bonding Period, I spend my time to get equipped with basics of PyQt (on which the GUI of VisMa is based) and spend the remaining time studying the tokenizing and simplify modules. Honestly, these modules were hard to understand. But the effort turned fruitful during the coding period. Also, I completed the task of simultaneous equation solver during this time. The logic was easy to frame, but the inclusion of comments and animations was tricky and involved the entire redesigning of the LaTex generator module (the part which created the final latex to be displayed in GUI).

Over to the first week of the coding period, the task which was decided was to re-design all the simplify module in an object-oriented fashion, which before coding period I believed would be most difficult to write *(after all more than 2000 lines of complex Pythonic logic, to be honest, was scary)*. But, efforts to understand module during the Community Bonding Period turned out to be fruitful, and I was happy to achieve this task in the desired time. Like any other programming project, there are some minor bugs out there, which will be fixed in the upcoming time!

Coming to week second, we decided to work on *Expression* Simplification. Now, what *Expression* is, briefly (& vaguely) any part of inputted equation enclosed in brackets can be termed as an *Expression*. So like when we solve an equation by hand, we solve the bracket part first, our task was to make visma do same! Earlier it didn’t support *Expression* simplification. For that, we decided to go for a complex recursive logic (solving the inner *Expression* first then the outer *Expression*s & so on). Recursive logic was complex & time consuming to implement, taking care of all comments & animations during recursion was a challenge. It took somewhat 9 days to come up with something fruitful. But yes it was worth it, VisMa could easily solve *Expression*s now. **A happy moment indeed!** 🙂

Next phase was to include a new module to VisMa. It was decided it has to be a Discrete Math module ('cause why the heck not!). We decided to go for Combinatorics stuff first, thus implementing Combinations & Permutation stuff. These modules require factorial of a number, I got this idea why not to implement factorial as a separate module and then use in Permutations & Combinations stuff. This added the factorial feature to VisMa!

For now, I am working of adding triple degree equation solvers to project. We as of now have decided to do so using Cardano Algorithm. If this turns out well it will also be done for four-degree equations. After this will be done, VisMa will be capable of solving & showing detailed steps for up to 4-degree equations.

**Chears to `Code`, Space & Maths!**