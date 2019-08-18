---
layout: post
title: "Real-time Bidding Primer"
date: 2019-08-18
---

[Wikipedia](https://en.wikipedia.org/wiki/Real-time_bidding) says:

> **Real-time bidding (RTB)** is a means by which advertising inventory is bought and sold on a
> per-impression basis, via programmatic instantaneous auction, similar to financial markets.

You click a link to visit a page. As it's loading, for each spot on
that page where an ad is slated to appear, an auction is launched wherein advertisers bid to show you their
ad. The advertisers are given a whole bunch of information about you (where does _that_ come from?) and they
use it to decide how much they're willing to spend to show you their ad. The whole process takes less than 100
milliseconds (again per Wikipedia), so it all has to be automated. The advertiser needs to be running some
kind of decision system that receives these opportunities and makes a very fast determination. The advertiser
needs to provide configuration ahead of time to let the decision system know the limits of its actions.


### Where'd You Get the ~~Coconuts~~ Data?!

Wikipedia again: (I mean, this is what it's there for, right?)

> ... a bid request [includes] various pieces of data such as the user’s demographic information,
> browsing history, location, and the page being loaded.
