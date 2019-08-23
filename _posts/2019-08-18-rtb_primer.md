---
layout: post
title: "What the Deal with Real-time Bidding?"
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

I think most of this stuff comes, directly on indirectly, from the so-called tracking cookies. The tracking
cookies help in assembling a browsing history (I think), and also contribute to correlating you to some kind
of unique ID on the advertising platform side. Your ID on the platform associates you to all sorts of
**inferred** categories, such as demographics and interests. Google does this, for example, and you can see
what they've inferred about you on their site. (As an aside, learning about how all this ad stuff works makes
Google's claim that they'll never sell your information very funny to me: of _course_ they won't sell it, they
give it away every time you see an ad in order to sell the page real estate!) Anyway, I emphasized "inferred"
before because there's a lot of concern out there about all this private information being sent around to
advertisers. While I do understand the concerns, and in general support greater transparency and education
of the general user public regarding the degree to which "free" sites monetize them, it's important to
differentiate between a company sharing your private data and a company sharing _its_ conclusions about what
your private data may be.


### Google Sent Me Everything It Knows About You -- Now What?

Now we get to the meat of the matter: how do I crunch all that data about you and decide how much your
eyeballs are worth to me _right now_ in less than 50 milliseconds?
