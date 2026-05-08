# Recognizing and Responding to Burnout

<p class="subtitle" markdown="1">the difference between tired and burned out matters</p>

## Learning Objectives

-   Distinguish burnout from ordinary fatigue and underperformance.
-   Identify early warning signs in yourself and your team members.
-   Take at least one concrete protective action for your team this week.

## When the Pattern Changes (10 min)

Over the course of three months, Ren's commit frequency dropped by 70%. His pull
request descriptions, which had been detailed and clear, became one-liners. He stopped
asking questions in code review. He replied to Slack messages in the evenings instead
of during working hours. Jess noticed the commit frequency because she looked at the
contributor graph. She didn't notice anything else until Ren told her at a 1:1 that
he was thinking about leaving.

Tahia was working weekends. Jess knew because Tahia's commits had weekend timestamps.
Jess had interpreted this as dedication. Tahia was trying to stay ahead of a growing
maintenance burden that she didn't feel she could raise with Jess because the last
time she'd mentioned it, Jess had said "yeah, that stuff piles up" and moved on.

Jess herself had not taken a day off since the post-doc started. She didn't think of
this as a problem. She thought of it as commitment.

[%b Maslach2016 %] describes burnout as having three dimensions: emotional exhaustion
(feeling drained by your work rather than energized by it), depersonalization (becoming
cynical or detached from the people and purpose of your work), and reduced personal
accomplishment (feeling like your effort doesn't matter or produce results). People who
are simply tired recover with rest. People who are burned out don't---or don't
quickly---because the problem is not a deficit of rest but a chronic mismatch between
what their work demands and what their work provides.

For managers of research software projects, the relevant populations are three:

*Yourself*: researchers who manage are often also expected to write code, publish,
teach, and attend conferences. The expectation that you will do all of these at the
same level as before you had management responsibilities is usually not stated explicitly
and never revised downward. You have to revise it yourself.

*Your team members*: RSEs in research environments often carry an invisible maintenance
burden---the work that keeps existing software running---alongside new development work.
Maintenance is rarely recognized or celebrated. It accumulates silently. The person
doing it often doesn't raise it because it feels like complaining.

*External contributors*: volunteer contributors to open source research software burn
out too, and their burnout is invisible in a different way. They simply stop showing up.

### Warning Signs

In others: declining engagement (fewer commits, shorter messages, slower responses),
working at unusual hours as the only way to keep up, declining to take on new things
without explanation, increased negativity in code review.

In yourself: dreading work you used to find interesting, feeling like nothing you do
is enough, losing the ability to tell a good week from a bad one because they all feel
the same, working more hours and producing less.

<div class="callout" markdown="1">

Burnout looks like underperformance. The response to underperformance is typically
increased pressure, clearer expectations, and more frequent check-ins. Applied to
someone who is burned out, this response makes things worse. Before treating someone
as underperforming, ask: has their engagement pattern changed? Have the demands on
them changed? Is there something I should have noticed earlier and didn't? Sometimes
the answer is yes, and the person doing the work is not the problem.

</div>

### What Managers Can Do

-   Make maintenance work visible. Count it, acknowledge it, and allocate time for it
    explicitly in planning meetings.
-   Protect time. A team member who is working 60-hour weeks is not more productive
    than one working 40; they are accumulating a debt that will be called in later.
-   Create explicit permission to not respond after hours. If you send emails at 11pm,
    your team will feel pressure to respond at 11pm even if you tell them they don't
    have to.
-   Check in about workload, not just work. "How are things going?" is not a workload
    check. "Is the amount of work you have right now sustainable?" is.

### Jess's Situation

After the conversation with Ren, Jess did three things. She added a standing agenda
item to every 1:1: "Is your current workload sustainable?" She moved maintenance work
into the milestone tracker so it was visible alongside feature work. And she took a
week off. She did not check Slack. When she came back, she noticed that Tahia had
handled everything competently and that nobody had emailed her to say the project was
collapsing. She took this as evidence that she was less of a single point of failure
than she'd feared, and more of an obstacle to her team's autonomy than she'd realized.

<section class="exercise" markdown="1">

### Exercise A: Personal Sustainability Check (8 min)

Answer honestly:

1.  How many hours did you work last week? Is that typical?
2.  In the last month, have you done something purely for enjoyment that had nothing
    to do with work?
3.  Name one thing that used to energize you about this project that currently doesn't.
4.  If a team member were behaving the way you currently are, what would you say to them?

You don't need to share your answers. Write them for yourself.

Suggested LLM prompt (optional):

> "I'm going to describe my current work situation. Tell me whether any of what I
> describe sounds like early-stage burnout, and if so, what one thing I should do
> differently this week. My situation: [describe briefly]."

Deliverable: four honest answers, kept private.

</section>

<section class="exercise" markdown="1">

### Exercise B: Team Protection Plan (12 min)

In pairs:

1.  (5 min) Describe one person on your team whose workload you are not sure is
    sustainable. What do you know about their current situation? What don't you know?

2.  (5 min) Write three concrete things you could do this week to make their situation
    more sustainable or to find out whether it is. Be specific: not "check in with
    them" but "at tomorrow's 1:1, ask whether the amount of work they currently have
    is sustainable, and listen to the answer without immediately offering solutions."

3.  (2 min) Write: "The LLM got [X] wrong because it didn't know [Y]."

Deliverable: three specific actions for this week.

</section>

## Debrief (5 min)

-   Maintenance work that is invisible is maintenance work that accumulates into burnout.
    Making it visible is not bureaucracy; it is protection.
-   The sustainability check question---"is your current workload sustainable?"---is
    most useful when asked regularly enough that the answer "no" doesn't feel like a
    crisis confession.
