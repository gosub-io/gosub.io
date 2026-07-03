---
title: "Code freeze: time to clean up"
metatitle: "Time for some code cleanup"
description: "We are entering a code freeze to clean up our codebase and prepare for the next phase of development."
date: 2026-07-03
author: "Joshua Thijssen"
---

The last few weeks have been pretty hectic on the development front. Our big merge of the different components into the 
engine meant we could finally start working toward getting the engine to render things properly. So we've put a lot of 
work into CSS and HTML rendering, using a few sites as a baseline to test against. Take a simple yet tricky site like 
[Hacker News](https://news.ycombinator.com): it uses tables for layout, which is one thing our layouter can't handle. So 
we came up with a simple table layout system that works alongside taffy to deal with tables. It's not perfect, but it 
works fine for now.

We're also moving our network code out of the engine itself and into a separate component, 
[gosub-sonar](https://github.com/gosub-io/gosub-sonar), so systems other than the engine can use it too. This should 
also increase our visibility to the outside world.

We've added a lot of documentation to the codebase in our 
[/docs](https://github.com/gosub-io/gosub-engine/tree/main/docs) folder to make it easier for new contributors to get 
started. We've also added plenty of comments throughout the code itself, so it's easier to understand why certain things 
are done the way they are.

At this point the engine can render some sites correctly and a lot of sites incorrectly, but somehow visibly enough. 
We're still missing a lot of things like JavaScript, forms, and more, but for now we're entering a code freeze to clean 
up and review our codebase. This lets us focus on keeping ownership of the codebase and making sure it stays clean and 
maintainable. It also gives us a chance to identify things that need fixing or implementing later on.

After the code freeze, we'll kick off a campaign to get the word out about Gosub, which is a lot easier now that we can 
actually show results from our work. This held us back massively in the past. Hopefully we can welcome more developers 
to the project and get more people involved in the development of Gosub.