# Managing Your Manager

<p class="subtitle" markdown="1">the relationship that controls your freedom to act</p>

## Learning Objectives

-   Translate technical decisions into language non-technical decision-makers can act on.
-   Push back on requests you can't fulfill without losing credibility.
-   Frame resource requests in terms of impact rather than effort.

## Working With the People Above You (10 min)

At every team meeting, Jess's supervisor added items to the simulator's roadmap. Not
requests---additions. By the end of the third meeting, the roadmap had seventeen items
that Jess and Tahia had not agreed to and could not realistically deliver. The
supervisor did not think of himself as creating problems. He was excited about the
project. He had ideas. He assumed that because he was the PI, his ideas were the plan.

Jess had two options. She could say yes to everything and deliver nothing on time while
quietly resenting the situation. Or she could learn to manage the relationship.

Managing your manager does not mean undermining them or working around them. It means
making the relationship productive in both directions. Your manager has authority over
resources and priorities; you have information about what is technically feasible and
how long it actually takes. Neither of you can do the other's job without the other's
information. A manager who adds seventeen items to a roadmap without cost information
is not being unreasonable---they genuinely don't know the costs. Your job is to provide
that information clearly and early.

Three practices that make the relationship work:

*Translate effort into impact*. "That feature would take three weeks" rarely lands.
"If we build that feature, we won't be able to fix the reproducibility problem before
the ESIP conference, which means our three submitted talks will all demo a version
that doesn't run on Windows" lands. Managers make priority decisions by comparing
impacts, not by estimating hours.

*Say no by offering alternatives*. "I can't do that" puts your manager in the position
of having to disagree with you or back down. "I can do that if we defer item 12, which
would push the March release by two weeks" gives them a choice. Most managers will make
the trade-off sensibly when it is presented as a trade-off.

*Give written updates before they ask*. A brief weekly email---three sentences, what's
done, what's next, what's blocked---costs five minutes to write and prevents thirty
minutes of ad hoc check-ins. It also creates a record that protects you when someone
asks why the March release slipped: you told them in February.

### Jess's Situation

Jess started keeping a one-page "capacity document" that listed the team's current
commitments with rough time estimates. Before each supervisor meeting, she emailed it
with one sentence for each proposed new item: "Adding this would require moving
[existing item] to Q3." Her supervisor stopped adding items without asking about
capacity first. The conversation shifted from "here are more things to do" to "here
is the trade-off I'm asking you to make." That was a better conversation for both of them.

<div class="callout" markdown="1">

Most supervisors who overload their teams are not doing it deliberately. They have
more ideas than capacity and they have never seen their team's capacity written down.
Making capacity visible is not complaining; it is giving your manager the information
they need to make good decisions. If you don't give them that information, they'll
make decisions without it.

</div>

<section class="exercise" markdown="1">

### Exercise A: Translate a Technical Decision (10 min)

Think of a technical decision your project has made or needs to make---for example,
refactoring a module, switching a dependency, or adding a test suite.

Suggested LLM prompt:

> "I need to explain a technical decision to a non-technical supervisor. The decision
> is [describe it]. The technical justification is [one or two sentences]. Help me
> write a two-paragraph explanation that describes the decision in terms of risk,
> reliability, and impact rather than technical detail."

Steps:

1.  (4 min) Run the prompt. Read the output. Does it describe the trade-off clearly?
    Does it use any technical terms your supervisor wouldn't know?

2.  (6 min) Rewrite the explanation for your actual supervisor, based on what they
    actually care about. What would make them say yes? What would make them say "let's
    wait until next quarter"?

Deliverable: a two-paragraph explanation of a technical decision for a non-technical
reader.

</section>

<section class="exercise" markdown="1">

### Exercise B: The Alternative Offer (10 min)

In pairs: one person plays a manager who has just asked for something unreasonable
(use a real example from your own work, or use Jess's situation). The other person
practices saying no by offering an alternative.

Rules: you cannot say "that's not possible" or "we don't have time." You must frame
your response as: "I can do [X] if we [trade-off]."

Switch roles. Write: "The LLM got [X] wrong because it didn't know [Y]."

Deliverable: one alternative offer, written out in one sentence.

</section>

## Debrief (5 min)

-   The capacity document is the key tool: it makes trade-offs visible before anyone
    has to argue about them.
-   "I can do that if..." is a more useful phrase than "no" in almost every situation
    where you need to push back up the hierarchy.
