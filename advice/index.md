# Advice

## Being Fired

I hope you're never fired, or if you are, that the company handles it
professionally.  In case they don't, this advice is based on [my experience
being fired by DataCamp][buzzfeed-datacamp] and on what friends and colleagues
have gone through there and elsewhere Remember: however much you like your job,
it won't love you back [%b Jaffe2021 %].

Insist on a record of all conversations.
:   The biggest mistake you can make is to assume good faith on the part of
    those who fired you.  In most jurisdictions you have a right to record any
    phone calls you are part of, and if that feels too confrontational, insist
    on communicating by email.  If they insist on communicating by phone or
    video call, follow up immediately with an email summary and make sure you
    send a copy to your personal account.

Pause before speaking, posting, or tweeting.
:   If possible, have someone you trust look everything over before you say it
    or send it.  Don't use someone who still works for the company, even if they
    are your closest friend: it puts them in a legally and morally difficult
    position.

Keep your public statements brief.
:   People may care, but most won't care as much as you do.  A simple recitation
    of facts is usually damning enough.

If you want to correct something online, add a timestamped amendment.
:   Don't just take it down or edit it: if you do, you will be accused of
    rewriting history, and muddied waters only help whoever fired you.  Also, be
    prepared for them to dig through everything you've ever said online and
    re-post parts selectively to discredit you.

Speak directly to all the issues rather than omitting or ignoring things you'd rather not discuss.
:   Your honesty is your greatest asset, and it's hypocritical to criticize your
    opponents for spin or selective reporting if you're doing it too,

Don't sign any agreement that might prevent you from speaking about moral or legal concerns.
:   Or if you do, make sure the agreement explicitly excludes your concerns
    before signing it.  And yes, it's very privileged of me to be able to say
    this: someone whose immigration status, essential health benefits, or family
    income is being threatened may not have a choice.  That is why I think
    people who do have a choice also have an obligation to fight.

Don't cite the law unless a lawyer tells you to.
:   The law probably doesn't mean what you think it means, and the company
    almost certainly has lawyers on their side who will seize on any
    misstatement or mistake you make.

Don't try to get them to acknowledge that they were wrong.
:   Their lawyers probably won't let them say anything that would acknowledge
    wrongdoing or liability, and whatever happened probably wouldn't have if
    they were the sort of people who could admit mistakes.

Go for long walks.
:   Or cook some healthy meals, or pick up the guitar you haven't touched in
    years—anything that requires you to focus on something else for a while.
    This isn't just for your mental health: exhausted people make poor
    decisions, and you need to be at the top of your game.

Remember that it's OK to cry.
:   And that other people do care about you.

## Findability

The [FAIR Principles][fair-principles] encourage researchers to make data
findable, accessible interoperable, and reusable [%b Wilkinson2016 %].
The tips below, taken from [%b Lin2020 %], will help you turn those
principles into practice.

Design for a wide range of users.
:   You might think only a few experts know your field well enough to care
    about your data, newcomers also need to use your work to gain
    experience, and other people may access your work in translation or
    via a screen reader.  Establish context, to use clear and concise
    language, and minimize the use of jargon.

Design with the end in mind.
:   Think ahead about the things you would want to be found at the
    completion of the project, including relevant preprints, and then
    decide what should go where. For example:

    -   Finalized laboratory data can be stored in [Dryad][dryad] so that you can
        cite the same data source in multiple publications with a single DOI.
    -   Lab protocols can be maintained in [Protocols.io][protocols] so that
        future collaborators can find them using a DOI while keeping incomplete
        protocol drafts private.
    -   Analysis code can be deposited in [Zenodo][zenodo], which you can cite and
        update as code evolves.
    -   Research manuscripts can be posted to sites like [arXiv][arxiv].
    -   Your ORCID can be linked to each of the DOIs created by these repositories.

Use textual structure.
:   A key part of searching the web is scanning the text returned by
    search engines to see if it contains target information.  Textual
    structure helps that process: formatted headers (rather than just
    enlarged text), bulleted or numbered lists, and highlighted terms all
    make both the information and its structure easier to understand.
    Other examples include:

    -   GitHub allows users to add tags to issues and commit messages which
        can then be searched across projects.
    -   Using specific Google Docs heading levels creates a table of
        contents in real time, visible when the file is open.
    -   CSV files do not have a standard way to store metadata, but authors
        commonly create a README or MANIFEST file that describes the
        structure and content of the files in a collection.

Add metadata.
:   All modern operating systems allow you to add information to the
    properties of a file or directory. Databases, word processors, and
    website construction programs also have built-in metadata
    capabilities, though application-specific metadata can quickly become
    inconsistent. Creating a list of terms and writing a small program to
    check that only terms from that list goes a long way toward preventing
    this.

Use search and browsing.
:   People search *and* browse when they're trying to find information, so
    design for both. As people browse, they build a mental map of the
    content they could possibly find, then search based on that map.  You
    should therefore make information accessible both ways and make it
    easy to move from searching to browsing and back again. Tags and other
    metadata help with searching, while structural clues tell users about
    the content contained in the information they are looking at.

Mimic real world directions.
:   Research shows that people scan but don't read: they click on the
    first close thing they see and give up very, very quickly.  Markers
    and directions should therefore be as consistent as highway signs with
    regards to appearance, style, and type of information.
    File paths and breadcrumb trails on websites give users a sense of
    where information is and suggest new paths they can take. For example,
    the URLs of a website might all include the name of a section of the
    site, such as <code>/papers/</code> or <code>/blog/</code>,
    while DOIs and ORCIDs serve as beacons that people can always get back to.

Use meaningful names.
:   Filenames and URLs are the one kind of metadata you can't avoid
    creating, so always choose ones that are human-readable and that
    convey information about what they name, both when navigated to *and*
    when returned in search results. For example, it's easy to call a
    paper <code>nature2021.pdf</code>, but since other people will publish papers
    there that year, a longer name like <code>wilson-managing-rse-plos-2021.pdf</code>
    will convey more information at a glance and retain that information
    after the paper has been downloaded and put in a folder with dozens of
    others.

Use unusual names.
:   The more generic a term is, the harder it is to search
    for. A quick test is to search for the name before adopting it: if
    dozens of unrelated results come up, you may want to pick a different
    name.

Use tags.
:   After meaningful names, tags are the easiest and most effective
    metadata you can create. Most tools support tagging, and most search
    tools use them to narrow the scope of queries.  This means that you
    can now file a single thing in multiple "locations", which was not
    possible in the pre-digital era. Multiple tags also assist users from
    varied backgrounds because the terms can be customized to be inclusive
    of a diverse set of users.

Use other people's tags.
:   Where possible, used established subject terms taken from article
    databases, data repositories, and library catalogs that you and your
    users might already be familiar with, such as the National Cancer
    Institute Thesaurus and the Medical Subject Headings.

Understand the difference between format and subject.
:   Format describes what your content *is*, while subject describes what
    it is *about*: for example, this *is* a web page, but it is *about*
    making information findable. You can rely on filename suffixes to
    distinguish computational notebooks from PDF files, tabular data sets,
    or slide decks, but file formats can change (e.g., slides can be printed as a PDF).
    Naming and metadata conventions therefore tend to be more robust as well as more
    informative than relying on file types.

Do not abbrvt.
:   Acronyms and abbreviations make communication between those who know
    them more efficient at the price of making them less accessible to
    newcomers. Spell out acronyms and abbreviations that you take for
    granted (or hyperlink to their definitions), but remember that
    acronyms are often repurposed by different professions or disciplines,
    so write them all out the first time they appear or point to a
    glossary.

## Partnership

People say, "If you want to go fast, go alone; if you want to go far,
go together," but in my experience, this is wrong: going alone is good for a fast
start, but after that, both speed and distance come from having partners.
Researchers and practitioners can each do great things on their own, but both
are better able to solve problems that really matter if they work together.
The rules listed below may help mitigate the frustration you encounter as you try to do this.

### If you are a researcher in academia…

Remember that companies work in weeks, not seasons.
:   Academic semesters are rooted in the seasons of an agricultural era, but
    practitioners in industry have to work at a more accelerated pace. In the time
    it takes you to write a grant, a company might develop and release two new
    versions of their product in order to keep up with their competition. Discuss
    timescales with your industrial research partners early on, and be realistic
    about how slowly things will proceed.

Be open.
:   While Jimmy Wales (the founder of Wikipedia) may not actually have said,
    "Open information drives out closed," the principle holds: with so much
    information freely available on the Internet, any paywall or login barrier put
    between you and your hoped-for audience will send a large number of people
    elsewhere.
    <br>
    More importantly, these barriers send a clear signal that you do not care if
    practitioners read your work or not: as one colleague observed rather sourly,
    it's the equivalent of inviting people to your house for dinner and then
    expecting them to pay for the drinks.

Value action over insight.
:   The goal for practitioners is not to understand the world, but to change it. "We
    know X" is much less useful to them than "we can do Y". When presenting your
    findings, you should therefore focus on how someone might act on it.
    One way to do this is to add slides titled, "What Difference Does It Make?" at
    strategic points in your presentations. If you can't think of what to write
    next, you may want to rethink what you're focused on.

Don't hesitate to sacrifice detail for clarity.
:   Understanding doesn't have to be complete in order to be actionable. For
    example, atoms aren't actually little colored balls connected by springs, but
    that's still a useful model in organic chemistry. You may need to hedge
    conclusions with qualifiers in order to get your work past Reviewer #3, but
    those "maybes" and "howevers" can often be omitted if they don't change what
    practitioners should try next.

Apologize in advance for the state of academic publishing.
:   Modern academic publishing isn't actually a conspiracy by a handful of large
    companies to line their pockets with government money that could and should be
    used to lift researchers out of penury, but it is functionally indistinguishable
    from a system that was. The best way to prepare your industry partners for its
    Kafkaesque production pipelines and interminable delays is to have them watch
    Gilliam's *Brazil*.

### If you are a practitioner in industry…

Remember that universities work in seasons, not weeks.
:   The timescale mismatch described in Rule #1 is due in part to the fact that
    academic researchers are almost always multi-tasking, and that many of those
    tasks are things they've never been trained to do. As students, they juggle
    several courses at once (which effectively means that they answer to several
    bosses who don't communicate with each other). Later, they are responsible for
    teaching, writing grant proposals, and administrative duties.
    <br>
    Collectively, this mean that their "work week" is only a few hours long, and
    that they will often appear to move at a snail's pace. Be as sympathetic as you
    can: they are even less happy with the situation than you are.

Remember that academic success is measured in publications, not sales.
:   University presidents routinely make about the economic value of research, but
    the only things that truly matter for academic advancement are publication,
    publication, and publication. Researchers are not given grants or tenure for
    doing things that are "merely useful", even if doing so requires a deep
    understanding of subtle complexities and months of hard work. For all the jokes
    practitioners make about the ivory tower, academic life is hard, uncertain, and
    poorly paid. People stay in it for the love of new knowledge; respecting their
    priorities is essential to building a productive relationship. (That said,
    practical problems often do unlock the door to genuinely new research topics by
    pushing researchers out of their comfort zone.)

Do the background reading.
:   H.L. Mencken once wrote that, "There is always a well-known solution to every
    human problem—neat, plausible, and wrong." Your problem is almost certainly
    one of those, and is almost certainly more complex than you first realize. While
    researchers should sacrifice detail for clarity,
    practitioners should make an effort to grasp at least some of that detail so that
    you don't waste time reinventing wheels and so that your research partner can
    think, work, and talk at full speed.

Don't overstate what has been learned.
:   The "maybes" and "howevers" that researchers are so fond of do sometimes
    matter; if your research partner has found that regular doses of a new drug
    seems to slow tumor growth in lab rats, do not embarrass them by claiming
    that they have discovered a cure for cancer.

### If you are either…

Apologize in advance for the state of your data.
:   The final rule applies equally to both researchers and practitioners. Files'
    names and locations, the meanings of column headers in tables, how those tables
    relate to one another, how missing values are represented and handles:
    everything that has made sense to you for years will suddenly seem a little
    foolish when you have to explain it to someone else. Apologize in advance, and
    then forgive yourself, because no matter how bad your data is, theirs may well
    be worse.

## Persuasion

Persuading people to do things is almost as essential to teamwork as running a
good meeting. These simple rules have served me well.

Don't.
:   If you have to talk someone into something, odds are that they don't really
    want to do it.  Respect that: it's almost always better in the long run to
    leave some particular thing undone than to use guilt or any underhanded
    psychological tricks that will only engender resentment.

Be kind.
:   I don't know if there actually is a book called *Secret Tricks of the Ninja
    Sales Masters*, but if there is, it probably tells readers that creating a
    sense of obligation or guilt increases the odds of a sale.  That may work,
    but it only works once and it's a skeezy thing to do even then.  If, on the
    other hand, you are genuinely kind and help other people because it's what
    good people do, you just might inspire them to be good people too.

Appeal to the greater good.
:   If you open by talking about what's in it for them, you are signalling that
    they should think of their interaction with you as a commercial exchange of
    value to be bargained over.  Instead, start by explaining how whatever you
    want them to help with is going to make the world a better place, and *mean
    it*.  (If what you're proposing isn't going to make the world a better
    place, propose something better.)

Start small.
:   Most people are understandably reluctant to dive into things head-first, so
    give them a chance to test the waters and to get to know you and everyone
    else involved in whatever it is you want help with.  Don't be surprised or
    disappointed if that's where things end: everyone is busy or tired or has
    projects of their own, or maybe just has a different mental model of how
    collaboration is supposed to work.  Remember the [%g 90-9-1 "90-9-1 rule" %] and set your
    expectations accordingly.

Don't build a project: build a community.
:   There is a softball team here in Toronto that never actually plays games:
    their practices are just an excuse for members to enjoy each other's
    company.  You probably don't want to go quite that far, but sharing a cup of
    tea with someone or celebrating the birth of their first grandchild can get
    you things that no reasonable amount of money can.

Establish a point of connection.
:   "I was speaking to X" or "we met at Y" gives them context, which in turn
    makes them more comfortable.  This must be specific: spammers and
    cold-callers have trained us all to ignore anything that starts, "I recently
    came across your website…"

Be specific about what you are asking for.
:   People need to know this so that they can figure out whether the time and
    skills they have are a match for what you need.  Being realistic up front is
    also a sign of respect: if you tell people you need a hand moving a few
    boxes when you're actually packing up an entire house, they're probably not
    going to come back.

Establish your credibility.
:   Mention your backers, your size, how long your group has been around, or
    something that you've accomplished in the past so that they'll believe
    you're worth taking seriously.

Create a slight sense of urgency.
:   "We're hoping to launch this in the spring" is more likely to get a positive
    response than "We'd eventually like to launch this."  However, the word
    "slight" is also important: if your request is urgent, most people will
    assume you're disorganized or that something has gone wrong, and may then
    err on the side of prudence.

Take a hint.
:   If the first person you ask for help says "no", ask someone else.  If the
    fifth or the tenth person says "no", ask yourself if what you're trying to
    do makes sense and is worth doing.

[arxiv]: https://arxiv.org/
[buzzfeed-datacamp]: https://www.buzzfeednews.com/article/daveyalba/datacamp-sexual-harassment-metoo-tech-startup
[dryad]: https://datadryad.org/
[fair-principles]: https://www.go-fair.org/fair-principles/
[protocols]: https://www.protocols.io/
[zenodo]: https://zenodo.org/
