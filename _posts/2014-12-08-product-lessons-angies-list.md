---
layout: post
title: Product Lessons I learned at Angie's List
permalink: product-lessons-angies-list
---

These are product lessons I learned while working at Angie's List. They have very little to do with Angie's List (the company) or the products that I was fortunate enough to work on.  Most of these lessons have been echoed by someone else (or multiple people) somewhere on the internet but seeing them firsthand makes a world of difference.

## PM's are judged by the outcomes of their product(s)
The most important lesson I learned is that PM's are judged by the outcomes of their product(s).  It doesn't matter how hard you work, if you're smart or if you have lots of good ideas. The product's metrics / success of the product is one and the same with the measure of a PM's performance.  Therefore, you should hang your hat on the final product, regardless of where ideas came from or how you got there.

## Your engineers aren't slow
It's easy to point at your team's engineers, say "see Joel Spolsky says better engineers go faster" based on data from Professor Stanley Eisenstat’s CS 323 class at Yale where all students have the exact same set of assignments [link](http://www.joelonsoftware.com/articles/HighNotes.html):

> The fastest students were finishing three or four times faster than the average students and as much as ten times faster than the slowest students.

However, changing requirements on work that's already in progress, vague user stories / tasks, scenarios that weren't thought through, not bundling similar tasks together, and changing your mind all slow down your team.

Here are two Justin Jackson posts that explain this better than me:

- [Your developers aren’t slow](https://sprint.ly/blog/your-developers-arent-slow/)
- [Don’t leave developers in the dark](https://sprint.ly/blog/dark/)

## Think about the entire experience
Just like [Jeff Bezos](http://blog.idonethis.com/the-dullest-most-vital-skill-you-need-to-become-a/) said:

> There is no way to write a six-page, narratively structured memo and not have clear thinking.

There's no way you can go through documenting the entire experience of a feature or improvement and not have thought through the edge cases, the error states, different user roles, etc.  A lot of the churn, vagueness in stories can be resolved by thinking through the entire experience you want to deliver first.

There's also a sense of correctness and confidence your engineers have that you're building the right thing and have thought through every scenario and shown real care for your user - error states, active/inactive items, etc.

## Good PM's write
This is a Ben Horowitz-ism from ["Good Product Manager, Bad Product Manager"](http://web.stanford.edu/class/e140/e140a/handouts/ProductMgmt.txt) (and pretty self-explanatory)

> Good product managers communicate crisply to engineering in writing as well as verbally. Good product managers don't give direction informally.

Also echoed by Andy Grove (in [High Output Management](/high-output-management/)):

> As they are written and formulated, the author is forced to be more precise than he might be verbally. Hence their value stems from the discipline and the thinking the writer is forced to impose upon himself as he identifies and deals with trouble spots in his presentation. Reports are more a medium of self-discipline than a way to communicate information. Writing the report is important; reading it often is not.

## Problem driven product development

This is a lesson from [Dan Storms](http://twitter.com/startstorms) who was always asking "what problem is this solving?" about any potential usage of engineering resources. It's been the one of the best frameworks for prioritization and clarity on building the 'right thing'. This also orients towards a roadmap that is more focused on 'what problems are we solving next?' versus 'what features are we building next?'

## Looking at your metrics and analytics about your product is a habit

Another prioritization question is constantly asking 'What metric is this moving?' or 'What does success look like?'

[Marty Cagan](http://www.svproduct.com/good-product-team-bad-product-team/):

> Good teams celebrate when they achieve a significant impact to the business KPI's. Bad teams celebrate when they finally release something.

It's easy to set up your events in [Segment](http://segment.com) and flip on the switches to services like [MixPanel](http://mixpanel.com). It's such a buzzword in 2014 to be data driven in your decision-making, but looking at your metrics and analytics about your product is a habit.

## Being technical definitely helps but isn't required
It's easy to see what Ken Norton is such an advocate of technical [PM](https://www.kennethnorton.com/essays/productmanager.html)'s.

Being technical helps with

1. Communication with engineers
2. Finding the minimal solution to solve the problem & understanding tradeoffs between implementations
3. ^ which inevitably helps the team move faster

## Success always feels one feature away
"If only our product had this one more feature, Company XYZ has promised us they would become a customer." It seems like reasonable logic to build that one additional feature that will make all the difference in our product and make us successful.

However in hindsight, if I could go back and do it again, my time would have been almost entirely focused on refining and improving existing features / functionality and not bolting on new features. No one has ever won from having the most features.
