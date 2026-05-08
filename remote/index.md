# Remote and Distributed Collaboration

<p class="subtitle" markdown="1">most of your contributors have never been in the same room</p>

## Learning Objectives

-   Identify the specific failure modes of distributed research software teams.
-   Apply async-first practices to reduce latency and improve inclusion.
-   Design a communication structure that works across time zones.

## When the Team Is Everywhere (10 min)

The simulator's contributor base had spread without anyone planning it. Carlos was in
São Paulo, nine hours ahead of the lab. Fatima was in Rabat, six hours ahead. A
contributor named Ji-ho had joined from Seoul, fourteen hours ahead. Jess was in
Toronto. The four of them had never been in the same meeting. Carlos's pull requests
sat for twenty-four hours before anyone reviewed them because by the time Jess's
workday started, Carlos had finished his and gone home. Ji-ho had stopped asking
questions in GitHub issues because the answers typically arrived while he was asleep
and the thread had moved on by the time he responded.

The failure modes of distributed teams are predictable and mostly not about technology.
They are about the implicit assumption that the team shares a working day.

*Review latency*: pull requests that sit for more than 48 hours create a feedback loop
that discourages contribution. The contributor finishes work, waits, forgets the
context, gets the review, has to re-read everything, and produces a smaller next
contribution. Across a time zone gap, this is the default behavior unless something
actively prevents it.

*Synchronous-first culture*: when the default answer to "how do we decide this?" is
"we'll talk about it in the meeting," everyone who can't attend that meeting is excluded
from the decision. Research software projects often run meetings at times convenient
for the lead's institution, which means contributors in other time zones either
attend at bad hours or don't attend---and then discover that decisions were made
without them.

*Invisible contribution*: code review, answering questions, updating documentation,
and triaging issues are often done asynchronously and leave less visible trace than
committed code. In distributed teams these contributions are even harder to see because
the people doing them are also not in meetings where they might be acknowledged.

*Trust without familiarity*: co-located teams build trust through incidental contact.
Distributed teams have to build it deliberately through code review, written
communication, and the consistency of showing up. A new contributor who gets good
code review feedback on their first three PRs will contribute more than one who gets
silence or generic approval.

### What Async-First Means in Practice

Async-first does not mean "no meetings." It means that meetings are for things that
genuinely require real-time discussion, and everything else is handled in writing
where it is searchable, accessible to people in other time zones, and not dependent
on everyone being available simultaneously.

-   Decisions are written down in issues or a decision log before they are acted on,
    not announced in meetings and then minuted.
-   Code review responses are expected within 48 hours, not "whenever."
-   Status updates are written, not spoken---the three-column format from Session 8
    works asynchronously by default.
-   Questions asked in writing get answers in the same thread, not in a Slack message
    that disappears.

<div class="callout" markdown="1">

"No mixed-mode meetings"---where some participants are in a room and others are
remote---is the rule most often violated and the one with the largest effect. In a
mixed-mode meeting, the people in the room dominate by default: they can see each
other's reactions, they can interrupt more easily, and the conversation moves at
their pace. If you can't have everyone in person, have everyone remote. The meeting
will be worse in some ways and much fairer in all of them.

</div>

### Jess's Situation

Jess moved the simulator to a 48-hour review policy: any PR open for 48 hours without
a review got pinged in the contributor's time zone via a GitHub notification. She
moved the weekly status update to a shared document that contributors could fill in
whenever their working day started rather than requiring synchronous attendance. She
scheduled one video call per month at a time that rotated to share the inconvenience
across time zones. Ji-ho started asking questions again within two weeks of the policy
change. He said the previous silence had felt like indifference.

<section class="exercise" markdown="1">

### Exercise A: Communication Audit (10 min)

Answer these questions for your project:

1.  What is the longest a pull request or issue comment has gone without a response
    in the last three months? What time zone was the contributor in?
2.  When are your regular meetings scheduled? Which contributors can't attend at that
    time without rearranging their workday?
3.  Where are decisions made? Are they accessible to contributors who weren't in the
    meeting?
4.  Which contributors haven't engaged in the last month? What do you know about why?

Suggested LLM prompt:

> "I manage a distributed research software team with contributors in [list time zones].
> Our current practices are [describe briefly]. What specific failure modes should I
> watch for, and what are the three highest-priority changes to make?"

Compare the LLM's suggestions to your audit answers. Write: "The LLM got [X] wrong
because it didn't know [Y]."

Deliverable: a list of at least two failure modes specific to your project.

</section>

<section class="exercise" markdown="1">

### Exercise B: Design a Communication Structure (10 min)

Design a communication structure for a team with contributors in at least three time
zones (use your own project, or use Jess's team: Toronto, São Paulo, Rabat, Seoul).

Specify:

-   How often synchronous meetings happen and when (rotate or fixed?).
-   How decisions are made for things that can't wait for a meeting.
-   What the expected response time is for code reviews and issues.
-   How contributors who miss a meeting find out what was decided.

Compare your structure with a partner's. Identify one thing they included that you
missed.

Deliverable: a one-page communication structure document.

</section>

## Debrief (5 min)

-   The 48-hour review policy is the single change that most improves distributed
    contributor engagement.
-   The time zone rotation for meetings signals that the project values contributors
    in all locations. Not doing it signals the opposite, even if unintentionally.
