# Managing the Work

<p class="subtitle" markdown="1">knowing who is doing what and what is in their way</p>

## Learning Objectives

-   Set up a lightweight tracking system for a small team.
-   Write a status update that makes blockers visible.

## Knowing Who Is Doing What (10 min)

Jess held her first sprint planning meeting with Tahia and Ren six weeks into the
post-doc. She had a list of fourteen open GitHub issues and a whiteboard. Two hours
later they had agreed on a prioritized set of work for the next three weeks. The
following Monday, Jess asked each of them what they were working on. Tahia was working
on something that wasn't on the list---a refactor she'd decided was necessary. Ren was
working on the first item on the list but had been stuck for two days on a dependency
issue he hadn't mentioned because he hadn't wanted to look like he couldn't handle it.

Project management at Jess's scale is not Gantt charts. It is knowing who is working
on what and what is in their way. [%b Fournier2017 %] puts it clearly: the manager's
job is to remove obstacles, not to assign tasks. The planning meeting matters less
than the Monday morning check-in that reveals Ren has been stuck for two days.

The three-column status update makes blockers visible without requiring a long meeting
to surface them. Everyone writes before the meeting:

-   *Progress*: what I finished since last time.
-   *Plans*: what I'll finish before next time.
-   *Problems*: what is blocking me or might block me.

Progress and Plans are read; the meeting discusses Problems. The format only works if
"Problems" is psychologically safe to fill in. If people think admitting a blocker
will be treated as evidence of incompetence, they'll leave it blank, and the manager
will find out two weeks later.

Issues work as a to-do list when each one has an assignee, a milestone, and a
time estimate. "Someday/maybe" items get a backlog label, not a slot in the active
milestone. Issues are closed when the work is done, not when the pull request is
merged. The issue tracker is the record of what the team decided to do; the PR history
is the record of what they actually built.

The one decision you cannot defer is when to cut scope. A feature that is 80% done
and blocking a release is worse than not having started it. Deciding to cut is always
uncomfortable. Deciding it two weeks after you should have is always more expensive.

<div class="callout" markdown="1">

Issues open for months with no assignee are not a backlog; they are a graveyard. A
graveyard signals to newcomers that the project doesn't take its own priorities
seriously, and signals to contributors that their reports may never be addressed.
Once a quarter, close every issue that has been open for more than six months with no
activity and add a comment: "Closing due to inactivity. Reopen if this is still
relevant." The people who still care will reopen them.

</div>

### Jess's Situation

After the sprint planning failure, Jess instituted two changes. First, she asked
everyone to write a three-column status update in a shared document by 9am on Monday.
Second, she labeled Ren's blocker immediately as "needs external help" and spent
thirty minutes on the dependency issue with him before her next meeting. He'd been
stuck for two days on something that took thirty minutes to resolve once Jess looked
at it. She hadn't known to look because he hadn't told her.

<div class="callout" markdown="1">

Cutting scope always feels like failure. Deferring the cut always costs more than
the cut itself. If you have a feature that is 80% done at the end of a sprint and
it is blocking a release, the options are: delay the release, ship with a known
incomplete feature, or cut the feature. None of these feels good. The one that felt
least bad usually looks better in retrospect than the one that felt most tolerable.

</div>

<section class="exercise" markdown="1">

### Exercise A: Write a Status Update (8 min)

Write one three-column status update for yourself as if it is the end of today.

-   Progress: two to four things you have finished since last week.
-   Plans: two to four things you will finish before next week.
-   Problems: one to three things that are blocking you or might block you.

Then swap with a partner. Read their Problems column and identify one thing you could
do to help. Tell them.

Deliverable: a written status update with Problems filled in honestly.

</section>

<section class="exercise" markdown="1">

### Exercise B: Set Up a Milestone (7 min)

Suggested LLM prompt:

> "Given these open issues in my project: [paste 5-8 real issue titles], help me
> create a four-week milestone. Assign each to either the milestone or a backlog.
> For each milestone issue, estimate the effort in hours and identify dependencies."

Steps:

1.  (3 min) Run the prompt. Note which assignments the LLM got wrong because it
    doesn't know your project's history or your team's actual capacity.

2.  (4 min) Open your project's issue tracker. Create a milestone ending four weeks
    from today. Move or create 3-5 issues into it, each with an assignee and a time
    estimate. Flag any "in progress" issue with no recent activity as "stalled."

Write: "The LLM got [X] wrong because it didn't know [Y]."

Deliverable: a milestone with at least 3 issues.

</section>

## Debrief (during transition)

-   The Problems column is where the meeting's value lives.
-   The status update is not a performance review. If people treat it as one, they
    will never put real blockers in the Problems column.
