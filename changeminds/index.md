# Why Facts Don't Change Minds

<p class="subtitle" markdown="1">arguing with the wrong model of belief</p>

## Learning Objectives

-   Explain why evidence alone rarely changes beliefs that are tied to group membership.
-   Recognize [%g motivated-reasoning "motivated reasoning" %] and the [%g backfire-effect "backfire effect" %] in technical and community disagreements.
-   Choose communication strategies based on how belief actually changes rather than how we wish it did.

## The Wrong Model (15 min)

Jess had been tracking a performance bug for two weeks. She had profiling data, a clear reproduction case, and a pull request with a fix and tests. She posted it to the mailing list. Within an hour, a long-term contributor had replied with three objections---none of them new, all of them already addressed in the pull request. Over the next three days, every time someone acknowledged the evidence, the objector became more confident in his position, not less.

This is not unusual, and it is not stupidity. Most scientists and programmers have an implicit model of belief that is roughly Bayesian: when someone receives new evidence, they update their beliefs in the direction the evidence points. This model is mostly true in domains that people are not invested in emotionally, but fails in predictable ways for beliefs tied to group membership.

Research in social psychology has established that beliefs about contested issues in a community function primarily as signals of group identity rather than as conclusions from evidence [%b Achen2017 Kahneman2011 %]. Holding the wrong belief does not just mean being misinformed: it puts you outside the group, so updating the belief means leaving the group. The social cost of updating is therefore often higher than the mental cost of the cognitive dissonance incurred by staying wrong.

The [%g backfire-effect "backfire effect" %] is the most striking manifestation of this pattern. In a range of experimental settings, presenting people with accurate evidence that contradicts a strongly held belief does not lead to belief updating. Instead, the person exposed to the corrective information often becomes *more* confident in the original belief [%b SteinLubrano2024 %].

[%g motivated-reasoning "Motivated reasoning" %] is a related and better-established phenomenon. People do not evaluate arguments neutrally. They are significantly better at identifying flaws in arguments that lead to conclusions they dislike than in arguments that support conclusions they already hold. This is not dishonesty in the ordinary sense---the person does not know they are doing it. The flaws they find are often genuine flaws. But the asymmetric attention means they have reached a conclusion before their evaluation begins.

<div class="callout" markdown="1">

A colleague once said that people want data, but believe stories. This makes sense in light of motivated reasoning: data provides cover for a decision already reached on other grounds, while stories transmit the emotional and social context that actually drives belief change. It is also why the most effective public health campaigns do not focus on statistics. They present specific, named people in specific situations.

</div>

## What Actually Works (10 min)

If you want to change someone's mind, finding and presenting better evidence is rarely the right strategy---at least, not by itself. What the research suggests instead [%b Hoffer2010 Robin2017 %]:

*Find trusted messengers.* A person is more likely to update a belief when the messenger is inside their community. The same argument lands differently from a colleague they respect than from someone they perceive as an outsider attacking their work.

*Reframe so updating doesn't require betrayal.* If accepting your evidence means admitting that someone was wrong about something they cared about, the cost of updating is high. Framing new information as "here is something we can add to what we already know" is more effective than "here is why the previous approach was wrong."

*Use stories, not statistics.* Data provides cover for a decision already made; stories change the underlying context. If you want to change a norm in your project community, find or tell a story that illustrates the norm you want, not a table that proves it is statistically common.

### Jess's Situation

Jess stopped arguing with the objecting contributor and started talking to two people he regularly agreed with. She explained the bug in terms of what it would mean for downstream users---and asked each of them if they had seen the same issue in their work. Both had. When they brought it up in the mailing list thread, the objection quietly disappeared.

<section class="exercise" markdown="1">

### Exercise A: Identify the Identity (10 min)

Think of a technical or process disagreement in your community that has persisted despite evidence. Pick one person on the side you disagree with.

Suggested LLM prompt:

> "I'm trying to understand why someone holds a position that seems inconsistent with the available evidence. The position is [describe it]. The evidence against it includes [describe it]. What group identity or community membership might this position be signaling? What would it cost this person, socially, to update their position? What could someone say that would make updating feel safe rather than like a betrayal?"

Steps:

1.  (5 min) Run the prompt. Does it identify a group identity you hadn't named? Does it suggest a reframing you hadn't considered?

2.  (5 min) Who, specifically, would be a credible messenger for this person? What story---not statistic---might change the context in which they hold the belief?

Deliverable: one reframing and one potential messenger.

</section>

<section class="exercise" markdown="1">

### Exercise B: The Story Version (10 min)

Take something you have been trying to convince people of using data or technical arguments. Rewrite it as a story about a specific person in a specific situation.

Rules: no statistics. No phrases like "studies show" or "the evidence suggests." One named person, one specific moment, what happened to them.

Deliverable: a story of about 100 words that conveys the same point as the argument you have been making with data.

</section>

## Debrief (5 min)

-   Evidence rarely changes beliefs that are bound up with identity. This is a predictable feature of human cognition, not a bug.
-   The right strategy is not better evidence---it is finding trusted messengers, reframing to reduce the cost of updating, and using stories instead of statistics.
-   This is not manipulation. It is taking the actual psychology of belief change seriously rather than the model we wish were true.

[%b Achen2017 Hoffer2010 Kahneman2011 Robin2017 SteinLubrano2024 %]
