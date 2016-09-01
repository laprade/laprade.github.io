---
layout: post
title: (DRAFT) QA Metrics
permalink: qa-metrics
---

_Apps have betas, so why can't blog posts have "draft" status while they are WIP?_ 

The outcome we all want is to **rapidly ship working software**: something everyone at Dispatch is tired of me always saying every day.

Where does the ownership of each part of that statement lie between the Product / Engineering / QA teams?

![Rapidly ship working software](/images/rapidly-ship-working-software.png)

**Rapidly**: Co-owned by everyone.

* *Product*: Choose a good scope that is iterative/incremental and follows the (cliche) build-measure-learn loop espoused by lean startup.
* *Engineering*: Scream if you see a better solution, don’t rabbit hole, don’t let PR’s sit open/unreviewed for a long time, etc.
* *QA*: Don’t let tickets or release candidates get stale sitting in an branch when it could be in a user’s hands making their lives better.

**Ship**: Owned by product as part of the “release” process. Done isn't done until it is in a user’s hands.

**Working**: Owned by QA (with some supplemental help from engineering). We want confidence the code works as expected = between a combination of manual tests and automated tests.

**Software**: The thing produced by our engineers (and the most important part of any of this).

## So what are the metric(s) that matter for QA to help us achieve the goal we all want?

It's not the number of tickets created, bugs found, time spent testing or test cases executed. It's  things that directly contribute to the outcome we all want - rapidly shipping working software.

> If you ask anyone at a well-run organization what the company’s top goals are, not only can they tell you what they are, but they can tell you exactly how their own work feeds into them. - [Keith Rabois](http://techcrunch.com/2016/05/12/lattice-be-productive/)

1. **Bugs in production that require a hot fix**. There are always going to be bugs. As long as [a] we know where the bodies are buried ahead of time and [b] don’t introduce bugs that require hot fixes (since we don’t currently have a good sev1, sev2, sev3, etc. definition). Desired outcome: confidence in what we are ship being "high quality"

2. **Time from when a release candidate is in a staging environment to when it has been fully tested**. Note: not time until green lit - just fully tested. Desired outcome: every day code is sitting in a release candidate branch, it grows stale when it could be helping make our users’ lives better. Let's deploy it or fix it. Don't let it just sit there.

3. **Time from when a ticket is merged into a dev environment to when the ticket is accepted or re-opened**. Desired outcome: context switching is tough for an engineer. We should strive to accept or re-open the ticket when the work is as fresh as possible in the engineer’s head.