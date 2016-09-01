---
layout: post
title: (DRAFT) QA Metrics
permalink: qa-metrics
---

_Apps have betas, so why can't blog posts have "draft" status while they are WIP?_ 

The outcome we all want is to **Rapidly Ship Working Software** - something everyone is tired of me always saying every day.

Where does the ownership of each part of that statement lie  between Product / Engineering / QA?

![Rapidly ship working software](/images/rapidly-ship-working-software.png)

**Rapidly**: Co-owned by everyone.

* *Product*: Choose a good scope that is iterative/incremental and follow the (cliche) build-measure-learn loop.
* *Engineering*: Scream if you see a better solution, don’t rabbit hole, don’t let PR’s sit open/unreviewed for a long time.
* *QA*: Don’t let tickets or RC’s get stale sitting in an branch when it could be in a user’s hands making their lives better.

**Ship**: Owned by product as part of the “release” process. Done isn’t done until it is in a user’s hands.

**Working**: Owned by QA (with some supplemental help from engineering). The desired outcome is being confident that the code works as expected - between a combination of manual tests and automated tests.

**Software**: The thing that is produced by our engineers (and most important part of any of this).

The metric(s) that matter for QA to help us achieve the goal we all want.

It's  not around number of tickets created, bugs found or tests executed - it's about things that contribute to the outcome we all want - rapidly shipping working software.


> If you ask anyone at a well-run organization what the company’s top goals are, not only can they tell you what they are, but they can tell you exactly how their own work feeds into them. - [Keith Rabois](http://techcrunch.com/2016/05/12/lattice-be-productive/)

1. Bugs in production that require a hot fix (there’s always going to be bugs - as long as we know where the bodies are buried ahead of time or don’t introduce bugs that require hot fixes since we don’t have a good sev1, sev2, sev3, etc. definition). Desired outcome: is what we are shipping "high quality"?

2. Time from a release candidate is in an environment to when it has been fully tested (Note: Not GL - just fully tested. Desired outcome: every day code is sitting in an RC branch, it grows stale when it could be helping make our users’ lives better).

3. Time from a ticket is in a dev environment to when it is accepted or re-opened (Desired outcome: context switching is tough for an engineer, we should try to accept or re-open the ticket when the work is fresh in the engineer’s head).

