# Project Lifecycle and Succession

<p class="subtitle" markdown="1">planning for endings before they're emergencies</p>

## Learning Objectives

-   Assess your project's bus factor and identify single points of failure.
-   Write a one-page advance directive for your project.
-   Begin a succession plan for your own role.

## Preparing for Endings Before They Happen (10 min)

At Tahia's annual review, she mentioned that she was applying for faculty positions.
She expected to hear back within six months. Jess went home that evening and tried to
answer a simple question: if Tahia left tomorrow, what could the project still do?

The answer was sobering. Tahia was the only person who knew how to package a release.
She held the credentials for the Zenodo account that issued DOIs. She had written
the data pipeline that fed the simulator's climate inputs, and while the code was in
the repository, the configuration files that made it work with the university's HPC
cluster were in a directory on Tahia's laptop. The simulator's automated tests passed
on Tahia's machine and on the CI server. They did not reliably pass on anyone else's.

The bus factor is a rough measure of project fragility: how many people would need to
be unexpectedly unavailable before the project couldn't function? A bus factor of one
means the project is one departure, illness, or accident away from a crisis. Most
research software projects have a bus factor of one for at least one critical function,
and most project leads don't find out until the person has left.

Preparing for a transition does not mean planning for failure. It means making the
project's health independent of any individual's continued participation. The `closure`
workshop covers this in depth; the minimum version for an ongoing project is three things:

*A shared credentials document*: every account, service, and resource the project
depends on, stored in a password manager that at least two people can access. Not just
"we use Zenodo" but "the Zenodo account is managed through the lab's shared 1Password
vault, the recovery key is with the department administrator."

*A release checklist*: the exact steps to cut a release, with enough detail that
someone who has never done it could follow the checklist and succeed. Run through it
with a second person before you need to. The moment you need to use it for real is
not the moment to discover it has errors.

*An advance directive*: a one-page document that answers three questions: what are the
conditions under which this project should be wound down, who has the authority to make
that decision, and what must be preserved before it can be considered closed. Writing
this when the project is healthy is not morbid---it is the same reasoning that makes
you test your backup before you lose data.

### Jess's Situation

Jess spent two afternoons with Tahia documenting the release process and the HPC
configuration. They discovered that two steps in the process required a personal
account rather than a shared project account. They also discovered that one of the
configuration files had been modified six months ago in a way that hadn't been
committed to the repository. The documentation surfaced both problems before they
became emergencies. Tahia ended up staying for another year---but the project was no
longer fragile in the same way.

<div class="callout" markdown="1">

"Document everything" is not a succession plan. People reliably short-change
documentation in favor of doing work, and what they do document usually doesn't address
tomorrow's actual needs. A succession plan is a specific document about a specific
transition: who does what, in what order, and how to verify it worked. It is written
with the person who will use it in mind, not the person who already knows how everything
works.

</div>

<section class="exercise" markdown="1">

### Exercise A: Bus Factor Audit (10 min)

Answer these questions for your project:

1.  Who is the only person who can cut a release? (If you say "me," that is a bus
    factor of one.)
2.  Which credentials exist only on someone's personal account rather than a shared
    project account?
3.  What would your project be unable to do if you were unavailable for three months?
4.  What would be unrecoverable if a key team member left without any notice?

Deliverable: a list of at least three single points of failure.

</section>

<section class="exercise" markdown="1">

### Exercise B: Write Your Advance Directive (10 min)

Write a one-page document covering:

-   The conditions under which this project should be wound down (not just "when
    funding runs out" but specific observable signals: contributor count, response time
    to issues, number of active users).
-   Who has the authority to make that call.
-   What assets must be preserved before shutdown is complete.
-   What obligations must be honoured before the project can be considered closed.

Give the document to a partner. They identify one realistic scenario it doesn't handle.

Write: "The hardest condition to write precisely was [X] because [Y]."

Deliverable: a one-page advance directive with one unhandled scenario noted.

</section>

## Debrief (5 min)

-   The most common single point of failure is release credentials on a personal account.
-   Writing the advance directive is hardest for the person most central to the project,
    because they are the one who has thought least about what happens without them.
