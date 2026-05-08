# The Myth of Meritocracy

<p class="subtitle" markdown="1">why "best person wins" is usually wrong</p>

## Learning Objectives

-   Describe how formal evaluation criteria and informal filters interact in hiring and contribution review.
-   Recognize [%g moral-licensing "moral licensing" %] as a mechanism that makes self-described meritocratic systems less fair over time.
-   Design evaluation processes that close the loop between stated criteria and actual outcomes.

## What Meritocracy Actually Means (15 min)

The word "meritocracy" was coined by the British sociologist Michael Young in a satirical novel in 1958 [%b Young1958 %]. Young's dystopia describes a society that has perfected the measurement of individual talent and ruthlessly sorts people by it, producing a ruling class convinced of its own deservingness and contemptuous of those beneath it. The word was adopted by politicians and executives as a term of praise, and Young spent the rest of his life pointing out the confusion.

When Jess reviewed pull requests from external contributors, she tried to evaluate them purely on technical grounds: does the code work, is it well-tested, does it follow the project's conventions? That sounds like a meritocracy. But Jess was also more patient with contributors she had met at conferences, quicker to merge from people whose names she recognized, and more likely to explain rejection decisions to people who had contributed before. None of these biases were conscious, and none showed up in the written review criteria.

Research on how elite selection actually works consistently finds that formal credentials matter less than what Lauren Rivera calls [%g social-legibility "social legibility" %]---the ability to display tastes, manners, and cultural references that signal membership in the right networks [%b Rivera2015 %]. Rivera's research on hiring at elite firms found that interviewers routinely described candidates as "polished" or "rough around the edges" in ways that correlated with class background rather than competence. The stated meritocratic criteria were real, but they operated within a prior filter that most candidates never saw.

Audit studies make the gap between stated and actual criteria measurable. Researchers send identical resumes to employers, varying only the name at the top, and record callback rates. The results are consistent across countries and decades: resumes with names read as white receive significantly more callbacks than identical resumes with names read as Black or Latino. The same pattern appears when resumes signal class background, gender, or disability.

<div class="callout" markdown="1">

Believing in meritocracy does not make people fairer. Research by Emilio Castilla and Stephen Benard found that organizations that explicitly adopt merit-based pay principles show *larger* gender pay gaps than those that do not. The mechanism appears to be [%g moral-licensing "moral licensing" %]: people who believe the system is already fair feel less need to monitor their own judgments for bias. [%b Sandel2020 %]

</div>

## Closing the Loop (10 min)

The problem is not that formal criteria exist---they are better than nothing. The problem is that most organizations never measure whether their stated criteria actually predict the outcomes they care about. The puzzle interview, popularized by Microsoft and still widespread in tech, selects for people who have prepared for puzzle interviews, which correlates with having the time, networks, and educational backgrounds that make such preparation possible. "Culture fit" as a hiring criterion is even less bounded: it is assessed subjectively and consistently reproduces the demographic composition of existing teams. Neither criterion is calibrated against actual job performance data, because most organizations never close that loop [%b Karabel2006 %].

For an open source project, closing the loop means asking not just "did we follow our review criteria?" but "who actually gets through our review process, and what does that tell us about who our criteria favor?"

### Jess's Situation

Jess noticed that contributors who posted on the mailing list before submitting a pull request had a much higher merge rate than those who submitted cold. The formal review criteria said nothing about prior communication. She added a line to CONTRIBUTING.md recommending that contributors open an issue before starting large changes---not to raise the bar, but to make the informal filter explicit so that people who didn't already know the norm had a chance to meet it.

<section class="exercise" markdown="1">

### Exercise A: Find the Informal Filter (10 min)

Think about a selection process you participate in---reviewing contributions, hiring, accepting applications.

Suggested LLM prompt:

> "I want to identify informal filters in a selection process. The process is [describe it]. The stated criteria are [list them]. What are three things that might make it easier or harder for a candidate to succeed that are not captured in the stated criteria? What group of people would be systematically disadvantaged by each of those informal filters?"

Steps:

1.  (5 min) Run the prompt. Does it identify filters you hadn't named? Does it suggest groups you hadn't considered?

2.  (5 min) For your actual process: pick one informal filter the prompt identified or that you recognize from experience. How could you make it explicit, so that people who don't already know the norm can learn it?

Deliverable: one informal filter and a one-sentence proposal for making it explicit.

</section>

<section class="exercise" markdown="1">

### Exercise B: Calibrate a Criterion (10 min)

Pick one criterion you use to evaluate contributions or candidates. Write down what "meets this criterion" looks like in practice---not in theory, but based on recent decisions you have actually made.

Check: does your description favor people with certain kinds of educational backgrounds, prior connections to the project, or communication styles? If yes, is that what you intended?

Deliverable: one criterion and a one-paragraph description of what it actually selects for.

</section>

## Debrief (5 min)

-   Formal criteria are better than no criteria, but they operate within informal filters that usually go unnamed.
-   Organizations that describe themselves as meritocratic and never measure the gap between stated and actual criteria are not meritocracies. They are systems with extra steps for people who already fit.
-   Closing the loop---checking whether your criteria actually predict the outcomes you care about---is a concrete action, not a gesture.

[%b Young1958 Rivera2015 Sandel2020 Karabel2006 Cottom2017 %]
