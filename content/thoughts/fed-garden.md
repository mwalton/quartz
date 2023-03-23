---
title: "Federated Digital Gardens"
date: 2023-03-22
tags:
- seed
---
## Observations:
1. **federation is cool but**: much of the [fediverse](https://fediverse.party/) consists of federated alternatives to centralized applications (mastadon v twitter, peertube v youtube, pixelfed v instagram). this is great and all; but for non-technical users w/ little concern over digital autonomy / privacy / data sovereignty there isn't much value add to migrate off an easy to setup centralized platform. what seems to be missing is a *novel* application that the fediverse could provide (bonus points if the use case technically *requires* federation to work)
2. **digital gardens are cool but:** they would be even cooler if they talked to each other! One can, of course, link to pages in another person's digital garden; but this is treated the same as a link to any other webpage (doesn't carry all the rich metadata the internal links within the garden have)

## Idea
use federation protocols like [activitypub](https://www.w3.org/TR/activitypub/) to link digital gardens together! a similar structure to mastadon servers could be applied:
1. servers host participant gardens and organize around shared themes & interests
2. participants can link to pages in anyone's garden and have that connectivity reflected in their own graph (perhaps visualizing the edges distinctly to show the various garden / server associations)
3. hashtags function the same and participants can query based on them (perhaps depth limited or iteratively expanding to prevent multi-hop explosions if someone is densely connected outside their own garden)

I could see the appeal of organizing around this idea (since there is already a strong oss base around quartz / obsidian w/ common interests). There is also a value incentive to pull in new users as spinning up your own connects you to richer ways to interoperate w/ others' gardens than external sites. If the servers organize as non-profits or coops, this could potentially grow organically in a non-financiallized way. 