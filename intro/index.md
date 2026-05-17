# Introduction

This workshop introduces the ideas and tools you need
to manage a team of up to a dozen people working together to build research software.

## Learner [%g persona "Persona" %]

Jess, 31, completed a PhD in ecology three years ago and now works for a national lab.
The data cleanup and simulation software she wrote in grad school
is being used by two dozen research groups around the world,
several of which have started contributing fixes and extensions of varying quality.
Jess has just been given a post-doc and a junior programmer,
and needs to decide which pull requests are safe to merge,
what everyone should work on next,
and how to handle people who spend more time arguing in group chat than writing code.
This workshop will show her what a healthy mid-sized project looks like
and how to manage both staff and external contributors.

## What Was Wrong with Version 1

The first run had two problems:

-   Content was abstract. Each lesson surveyed six to eight topics at
    high altitude without giving learners anything concrete to think
    about or do. The Jess narrative described what a fictional person
    did, but didn't ask learners to connect it to their own work.
-   Exercises couldn't be done in time, or had no clear
    deliverable. "Where are you now?"  with seven open questions takes
    an hour to discuss properly or five minutes to wave at.  "Draw a
    concept map for the thing you're working on" is fine if you've
    been taught how to draw concept maps; without that, learners
    stall.

## The Design of Version 2

1.  Every session ends with something learners can take home and use
    right away.
1.  Every exercise is time-boxed.
1.  Jess is a worked example for every exercise, not just backdrop.
1.  Learners will use LLMs during exercises.

That last point needs some justification.
Research software engineers already use LLMs as coding assistants;
the workshop should model what good practice looks like
rather than pretending the tools don't exist.
Each exercise is designed accordingly:

1.  Exercises that produce generic documents provide a suggested prompt.
    Learners generate a first draft with LLM help,
    then critique it for their specific project.
1.  Exercises requiring judgment about real people,
    real trade-offs,
    or specific project history cannot be offloaded.
1.  Some role-play exercises use the LLM as the other party.
    This lets learners practice at their own pace and repeat if they want.
1.  The debrief for each session discuss common LLM errors.
