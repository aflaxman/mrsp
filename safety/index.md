# Psychological Safety

<p class="subtitle" markdown="1">why your team won't tell you what you need to know</p>

## Learning Objectives

-   Describe what psychological safety is and why it predicts team performance.
-   Identify specific behaviors that create or destroy it.
-   Change one practice in your own project to make it safer to admit uncertainty.

## When People Stop Telling You Things (10 min)

Jess had been noticing for a month that Ren only brought problems to her after they had
become crises. A dependency incompatibility that could have been flagged in a day had
sat for two weeks while Ren tried to fix it alone. A misunderstanding about a data
format had gone three sprints before he mentioned it. In both cases, he had known
something was wrong much earlier than Jess found out.

When Jess asked him about it, his answer was simple: the last time he'd admitted he
didn't know how to do something, she had said "you're the programmer, figure it out"
and ended the conversation. He had spent three hours figuring it out, filed it away as
"don't bring Jess your problems," and adjusted his behavior accordingly. Jess had no
memory of saying it.

[%b Edmondson1999 %] studied 51 work teams in a hospital and found that psychological
safety---the shared belief that it is safe to take interpersonal risks---was the
strongest predictor of team learning behavior. Teams with high psychological safety
admitted errors, asked questions, and flagged problems early. Teams with low
psychological safety did the same amount of work but missed more problems and learned
less from them. The difference was not the team members' skill or motivation. It was
whether they believed that speaking up would be held against them.

[%b Forsgren2018 %] found the same pattern in software delivery: the highest-performing
engineering teams were distinguished not by their tools or processes but by whether
team members felt safe to admit mistakes and ask for help. Low psychological safety
produced two predictable failure modes---problems discovered late and silent workarounds
that nobody else knew existed. Both are familiar to anyone who has managed a software
project.

Psychological safety is not the same as niceness or the absence of conflict. High-safety
teams disagree often and directly. The difference is that the disagreement is about
ideas and work rather than about people's competence or standing. A team where nobody
ever says "I don't think that's right" is not a psychologically safe team---it's a
team where people have learned that disagreement is dangerous.

### What Managers Do to Destroy It

The most common manager behaviors that destroy psychological safety are not dramatic.
They're small, repeated, often unintentional:

-   Responding to bad news with visible frustration ("why didn't you catch this earlier?")
-   Dismissing questions in public ("that's covered in the documentation")
-   Solving someone's problem for them rather than helping them solve it, which signals
    that you don't trust their judgment
-   Only seeking input from the same two people in every meeting
-   Changing direction without explaining why, which teaches people that their work can
    be cancelled without warning

### What Managers Do to Build It

-   Respond to bad news with curiosity rather than frustration: "tell me more about how this happened"
-   Publicly acknowledge your own mistakes and what you learned from them
-   Ask for input explicitly from people who haven't spoken
-   When someone brings you a problem, ask what they've already tried before offering a solution
-   Close the loop: when someone flags a risk and it turns out to be real, acknowledge that they were right

### Jess's Situation

After the conversation with Ren, Jess started keeping track of how she responded when
people brought her bad news. She was surprised to find that her first instinct was often
"why didn't you catch this earlier?"---not asked with blame intended, but heard that way.
She started replacing that question with "what was the first sign something was wrong?"
The answers were more useful, and the conversation stopped feeling like a debrief and
started feeling like problem-solving.

<div class="callout" markdown="1">

You cannot survey your team and ask them whether they feel psychologically safe. If
psychological safety is low, they won't tell you honestly. The best proxy is behavioral:
how quickly do problems surface? How often do people ask questions in meetings rather
than afterward? How many of your sprint retrospectives produce the same items as last
time? If the answers are "late," "rarely," and "all of them," psychological safety is
the likely culprit.

</div>

<section class="exercise" markdown="1">

### Exercise A: Diagnose Your Team (10 min)

Suggested LLM prompt:

> "I manage a small research software team of [N] people. I'm trying to assess
> whether psychological safety is an issue. Based on the following observable
> behaviors, tell me which are warning signs and which are neutral: [list three to
> five things you've observed recently in your team, e.g., 'problems come to me
> late,' 'the same person dominates code review discussions,' 'nobody has disagreed
> with a technical decision in three months']."

Steps:

1.  (4 min) Run the prompt. Note what the LLM flagged as warning signs and whether
    you agree.

2.  (6 min) Individually, write:
    -   One behavior from your team that might indicate low psychological safety.
    -   One thing you have said or done in the last month that could have made it
        less safe to bring you problems.
    -   One change you will make in how you respond to bad news.

Deliverable: three written sentences.

</section>

<section class="exercise" markdown="1">

### Exercise B: Practice Responding (10 min)

In pairs: one person describes a realistic bad-news scenario (a test suite has been
silently failing for two weeks; a contributor has been sitting on a PR for a month
without mentioning they're blocked). The other person practices responding in a way
that makes it more likely the person will bring problems sooner next time.

Switch roles. Observers: note one phrase the manager used that would make you more
likely to bring problems early, and one that would make you less likely.

Write: "The LLM got [X] wrong because it didn't know [Y]."

Deliverable: one phrase you'll use and one you'll stop using.

</section>

## Debrief (5 min)

-   You cannot build psychological safety with a policy. It is built through hundreds
    of small interactions over months.
-   The fastest way to destroy it is to respond badly to bad news once and then expect
    people to forget.
