# Story-Nanoslicing
*originally Posted on August 11th, 2020*
<img width="1600" height="900" alt="story_nanoslicing1" src="https://github.com/user-attachments/assets/e24d3eea-fc78-408c-8f20-6fdafb44ff3c" />

It’s the start of a new project for our team, and we’re all excited to get development rolling. The Product Owner’s grand vision sounds great, but how do we get from that vision to the day-to-day detailed stories we’ll need to work on? We’re not about to go off into a cave to build in isolation for months, since we know our understanding of the problem will evolve over time. We want to get a Minimally Viable Product live, see what makes customers happy, and adjust the parts that aren’t satisfying or profitable.

That overall strategy is sound, but “Make the MVP” doesn’t give us a clear direction for our first iteration. To start, we want to break down the problem into simpler pieces, but we’re not sure how. As folks grow impatient to get the meetings done with and start work, the easy way out is to proceed even though some of our User Stories still have ambiguous deliverables or a laundry list of requirements. [But making complex things simple isn’t easy](https://www.infoq.com/presentations/Simple-Made-Easy/).

We don’t have trouble making stories larger. Story review can wind up adding some scope or complexity creep. Working on one part of the app makes it tempting to do just a little more while you’re in the same spot. Sometimes an edge-case is front-of-mind at the moment, and we want to deal with it while we remember it. This is natural and common, but can escalate into stories we can’t manage.

If we don’t break up oversized stories into more manageable pieces, we’ll have to deal with the problems that come with larger and longer-lived ones:

* blocking our other work
* poor visibility to the rest of our team
* less transparent velocity for planning
* longer delay to acceptance feedback from our Product Managers
* longer delay to production feedback from our customers

There may be legitimate reasons to have large stories based on our team’s situation, but we always want to **consciously** decide to allow a large story.

> [!IMPORTANT]
> The only reason we should have a big story is that we choose to make a story big, not that we don’t know how to split it.

## Inspiration for the Road Ahead

There’s a [parable](https://en.wikipedia.org/wiki/Blind_men_and_an_elephant) that tells of scholars who encounter an elephant for the first time without being able to see it. As they describe the elephant, each gives the rest a piece of the greater idea, though no one of them has the whole concept yet. Extending that metaphor, Software Engineering is the reverse process — we’re trying to cobble together a working elephant from numerous partial descriptions. Making our stories smaller will help us adjust as we go, to better match the elephant we’re striving to build.

<img width="1435" height="986" alt="story_nanoslicing2" src="https://github.com/user-attachments/assets/9520cbb6-3b27-401a-9fcc-a1f0633ea16c" />

## Chipping Away

To give us clear direction as we build, an ideal story would satisfy all of the [INVEST](https://en.wikipedia.org/wiki/INVEST_(mnemonic)) criteria as [coined by Bill Wake](https://xp123.com/articles/invest-in-good-stories-and-smart-tasks/):

* **Independent**, so it can be rearranged with respect to the stories around it
* **Negotiable**, so it can be canceled or significantly deferred without impacting other work
* **Valuable** (or **Vertical**), so it implements something through the entire stack, giving end-users the benefit of the new functionality and the team a chance to learn from reality
* **Estimable**, so we know enough to say how complex it is compared to other estimated stories
* **Small**, so you can get through it within an iteration
* **Testable**, so we have a way to tell whether the result functions as intended or not

Breaking things down that far takes some additional planning effort, and necessarily involves further discussion. What bite-sized bits of user functionality can we deliver in isolation from other parts of the application? What work gives us the highest value at this moment? It’s up to our team to talk through these issues until we’ve established a common understanding.

In exchange for this, we build and deploy these smaller things faster. Granular deployments mean faster production feedback about the most essential parts of the product and reduced risk from the uncertainty of having features in-flight. They also reduce the Product Management burden of feature acceptance, since there’s less to confirm at a time. Devs and QA in turn get an easier debugging process, having fewer places to check for the cause of a newly-introduced issue.

We get better at this through practice, applying the Agile principle that [Frequency Reduces Difficulty](https://martinfowler.com/bliki/FrequencyReducesDifficulty.html). Getting our team together to run a rapid-fire story-splitting exercise in an isolated context will help us prepare to apply the same skills on real projects. If we know we can break down a sample problem ad absurdum, we can proceed with confidence that we’ll avoid cumbersome ones when a complex problem rears its elephantine head.

*Illustrations by [Erin Murphy](https://www.linkedin.com/in/erin-murphy-design/).*
