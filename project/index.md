# Managing the Work

<p class="subtitle" markdown="1">knowing who is doing what and what is in their way</p>

## Learning Objectives

-   Set up a lightweight tracking system for a small team.
-   Write a status update that makes blockers visible.

## Knowing Who Is Doing What (10 min)

Jess held her first sprint planning meeting with Tahia and Ren six weeks into the post-doc.
She had a list of fourteen open GitHub issues and a whiteboard.
Two hours later they had agreed on a prioritized set of work for the next three weeks.
The following Monday,
Jess asked each of them what they were working on.
Tahia was working on a refactoring she had decided was necessary,
but which wasn't on the list.
Ren was working on her first item
but had been stuck for two days on a dependency issue he hadn't mentioned
because he hadn't wanted to look like he couldn't handle it.

Project management at Jess's scale is not Gantt charts.
It is knowing who is working on what and what is in their way.
[%b Fournier2017 %] puts it clearly:
the manager's job is to remove obstacles, not to assign tasks.
The planning meeting matters less than the Monday morning check-in
that reveals that someone is stuck.

The three-column status update makes blockers visible
without requiring a long meeting to surface them.
Before the meeting,
everyone writes *and shares* bullet points explaining:

-   *Progress*: what they finished since last time
-   *Plans*: what they will finish before next time
-   *Problems*: what is blocking them (or might)

Progress and Plans are read; the meeting discusses Problems.

<div class="callout" markdown="1">

This format only works if "Problems" is psychologically safe to fill in.
If people think admitting a blocker will be treated as evidence of incompetence,
they'll leave it blank,
and the manager will find out two weeks later.

</div>

Issues work as a to-do list when each one has an assignee, a milestone, and a time estimate.
"Someday/maybe" items get a backlog label,
not a slot in the active milestone.
Issues are closed when the work is done,
not when the pull request is merged.
The issue tracker is the record of what the team decided to do;
the PR history is the record of what they actually built.

<div class="callout" markdown="1">

Issues that have not been triaged are a signal that no one is running the project.
Once a week (at least),
go through all newly-filed issues and assign each a category and a priority
(even if that priority is "not on the roadmap").

</div>

### Jess's Situation

Jess instituted two changes after the sprint planning failure.
First,
she asked everyone to write a three-column status update in a shared document by 9:30 am on Monday.
Second, she labeled Ren's blocker immediately as "needs external help"
and spent thirty minutes on the dependency issue with him before her next meeting.
He had been stuck for two days on something that took thirty minutes to resolve
because she hadn't known to look.

## Cutting

Cutting scope always feels like failure,
but deferring the cut almost always costs more than the cut itself.
If you have a feature that is 80% done at the end of a sprint and it is blocking a release,
the options are to delay the release,
ship with something that is known to be incomplete,
or cut the feature.
None of these feels good,
but deciding to cut two weeks after you should have is always more expensive.

</div>

<section class="exercise" markdown="1">

### Write a Status Update (8 min)

Write one three-column status update for yourself,
then swap with a partner.
Read their Problems column and identify one thing you could do to help.

</section>

<section class="exercise" markdown="1">

### Set Up a Milestone (7 min)

Prompt the LLM with something like this:

> Given these open issues in my project [paste 5-8 real issue titles],
> help me create a four-week milestone.
> Assign each to either the milestone or a backlog.
> For each milestone issue, estimate the effort in hours and identify dependencies.

1.  Note which assignments the LLM got wrong
    because it doesn't know your project's history or your team's actual capacity.

1.  Open your project's issue tracker.
    Create a milestone ending four weeks from today.
    Move or create 3-5 issues into it, each with an assignee and a time estimate.
    Flag any "in progress" issue with no recent activity as "stalled."

</section>
