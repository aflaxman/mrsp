# Hiring and Firing

<p class="subtitle" markdown="1">the decisions that define your team</p>

## Learning Objectives

-   Describe the most common mistakes in hiring for a research software position.
-   Follow a structured process for letting someone go without making it worse.
-   Know how to protect yourself if you are the one being let go.

## Two Decisions You Can't Take Back (15 min)

Jess needed to fill a six-month contract position to help with data pipeline work
while Tahia was on maternity leave.
She mentioned it to a colleague at lunch,
who said one of his recent graduates would be perfect.
He pointed out that posting the job and doing interviews would take weeks.

Jess took the shortcut.
Three months later,
the contractor had broken the test suite twice,
submitted zero documentation,
and wasn't answering email.
Getting rid of him took six weeks of HR paperwork
and left Jess doing pipeline work herself for a month.

## Hiring

Hiring and firing shape everything else about a team.
Both reward preparation and punish shortcuts.
The basics that frequently get skipped:

-   Talk to Human Resources before doing anything else.
    Rules change, and "I didn't know" is not a defense.
-   Always post positions publicly,
    even if you think you already know who you want.
-   Publish a salary band before applications open.
    Negotiating from a blank slate advantages whoever is least worried about asking for more.
-   Describe the actual job:
    "Must have experience with large-scale distributed data pipelines"
    helps both sides.

[%b Behroozi2020 %] studied hundreds of technical hiring processes
and found that interviewers consistently overrate performance under artificial pressure
and underrate communication skills and documentation habits.
The person who freezes on a whiteboard problem
but writes clear commit messages and asks good questions in code review
is usually more valuable to a research software team than the reverse.

<div class="callout" markdown="1">

A better alternative to whiteboard problems is a work sample:
give candidates a small, realistic task similar to what the job actually involves,
and pay them for their time.
It surfaces relevant skills and signals that you respect people's time.

If that isn't an option,
give candidates a debugging exercise rather than asking them to write code from scratch.
Most people spend more time debugging than writing new code,
so this will let you see how well they do that using their preferred tools.

</div>

## Firing

Sometimes people have good reasons for poor performance.
But sometimes the fit is genuinely wrong,
or the person is simply unreliable, argumentative, lazy, or dishonest.
Keeping them on is bad for morale as well as productivity.
Firing them is the hardest part of managing a team.
The steps below don't make it easier,
but they make it less likely to go badly.

*Talk to HR first.*
Every jurisdiction has rules about termination.
Talk to Human Resources before doing anything else,
including before telling anyone on your team that you're considering it.
If your project is open source and the person is a volunteer contributor,
your governance document should already spell out criteria for membership
and who decides when that privilege is revoked.

*Check with someone outside the project.*
It is hard to think clearly about someone who has frustrated you for months.
Not liking someone is not sufficient reason to let them go,
and the two are easy to confuse.
Before you do anything you might regret,
talk to a colleague or mentor outside the project with no stake in the outcome.
They are more likely to be objective
(and less likely to let something slip back to your team before you are ready to act).

*Create a transition plan.*
The better practice is to ask everyone to document their work all the time,
which keeps roles and responsibilities current
and means you are not caught short in any departure, voluntary or otherwise.
Before the termination conversation,
write out the immediate steps,
like changing passwords and removing them from permission lists.
Going through this list in advance is also a useful reminder of
how much organizational overhead has quietly accumulated around your project.

*No surprises.*
If someone is surprised they are being fired, you have made a mistake.
If the reason is behavior,
they should know what is in the code of conduct,
and you should have given them clear warnings before reaching this point.
If the reason is performance,
you should have told them directly that they were not meeting expectations
and given them a genuine opportunity to improve.
The no-surprises rule also protects you:
you will feel bad if you discover they have been missing deadlines
because of a family illness they were too embarrassed to mention.

*Delivery.*
Write out what you are going to say and keep it short.
Practice it out loud:
not to read from a script,
but because rehearsing forces you to find the words before the moment arrives.
Get straight to the point and do not get drawn into "what if" discussions.
Stick to the practical matters you identified in the transition plan.

*Telling the team.*
Make sure your team hears the news from you before rumors start.
Keep the statement brief and factual and do not discuss the details.
The person you let go has a right to privacy,
and other team members will notice that you talked about someone's private situation
and wonder what you would say about them.

*Keep a record.*
Do all follow-up communication by email so that both sides have accurate records.
If someone insists on a call,
ask to record it or have a neutral third party present.
People do not always act in good faith when they are hurt or angry,
and a record protects everyone.

## Being Fired

Most management guides skip this section.
They probably shouldn't,
because the first time it happens to you,
you will probably have no idea what to do.
If you were fired because money ran out or the project changed direction,
do your best to take it in stride.
If,
on the other hand,
you feel you were fired unfairly,
these rules may help.

<div class="callout" markdown="1">

Do not expect the organization to admit they were wrong.
Their lawyers probably will not allow any statement that acknowledges wrongdoing or liability,
and whatever happened probably wouldn't have
if they were the sort of institution that could readily admit mistakes.

</div>

*You are not a lawyer.*
Do not cite specific laws unless a lawyer tells you to.
Legal language probably does not mean what you think it means,
and whoever fired you almost certainly has legal representation
that will seize on any misstatement you make.

*Keep public statements brief.*
People may care about what happened to you,
but most will not care as much as you do.
A simple, factual account is usually more damning to whoever fired you than an emotional one.

*Correct mistakes publicly.*
If you need to correct something said publicly about your departure,
add a timestamped correction rather than editing what you previously wrote.
Editing looks like rewriting history,
and you should be prepared for the other side to imply that you're being dishonest.

*Be honest about your own failings.*
Speak to all the issues directly rather than glossing over things you would rather not discuss.
Your honesty is your greatest asset in this kind of situation,
and it is hypocritical to criticize the organization for spin if you are doing the same thing.

*Don't sign away your right to speak.*
Do not sign any agreement that prevents you from speaking about moral or legal concerns
without ensuring your concerns are explicitly excluded first.
This advice is easier to follow from a position of financial security.
Someone whose immigration status or family income is threatened may not have a real choice,
which is precisely why people who do have a choice also have an obligation to push back when they can.

*Cry if you need to.*
Or go for long walks,
or pick up something that requires you to focus
on anything other than the situation for a while.
Exhausted people make poor decisions,
and you need to be at your best.

<section class="exercise" markdown="1">

## Exercises

### The Hiring Brief (10 min)

Write the job description for the next hire on your team,
thene check it against these questions:

-   Does it describe the actual work, or the ideal candidate?
-   Does it include a salary range?
-   Does it describe how candidates will be evaluated?

Use an LLM to critique what you wrote:

> I'm hiring a research software engineer for a small academic project.
> Here is my draft job description.
> Identify any language that might discourage qualified candidates from applying
> or that signals poor hiring practices.

</section>

<section class="exercise" markdown="1">

### Transition Plan (8 min)

Write a transition plan for the most critical role on your current team.
The plan should include:

-   What knowledge or access only they currently hold
-   The steps needed to transfer or document that knowledge
-   The immediate actions required on their last day

</section>

## Debrief (5 min)

-   The most common hiring mistake is treating the process as a formality
    once you have already decided who you want.
    The paperwork exists to protect candidates, not to inconvenience managers.
-   The no-surprises rule is the one most managers know and most consistently ignore.
    If someone is surprised they are being let go,
    the performance management process failed before the termination decision.
