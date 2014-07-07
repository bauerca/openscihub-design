# Openscihub

Openscihub strives to provide a platform for open and constructive discussion
and review of scientific articles that maximizes engagement from the layperson
to the domain expert.

## Summary

Fundamentally, the platform will manage and display PDFs (articles) and
annotations (reviews), which can be created and submitted by *any* user.
User-defined communities will group users and articles and will serve several
purposes:

- identification of scientific pursuits and domain experts,
- establishment of scientific canons, and
- filtration of article reviews/discussions.

User reviews will be subject to voting and moderation to judge their relevance
and quality and curb abuse.

## Users

Anyone can join openscihub, but not everyone can join every community.

## Communities

Communities are simply groups of openscihub users, and can be initiated by
anyone. Communities will define their own membership prerequisites that
determine the purview of the group. For example, a group of domain experts may
require participation in a relevant conference or some proof of authorship of a
relevant publication, whereas a community interested in discussing general
physics concepts in the context of real articles may not have any prerequisites
for membership.

## Articles

Scientific articles are the focus of openscihub and will be displayed *in full*
so that they can be reviewed with annotations. This will require permission
from the copyright holder and could pose a problem for previously published
articles. Openscihub is probably best classified as a pre-print service.
Partnerships with well-established pre-print archives (ahem,
[arXiv](arxiv.org)) are desired.

It is openscihub's lofty dream to serve *every* scientific article, ready for
open discussion, by being such a successful project that publishers alter their
copyright agreements (we said lofty...).

### URL

Articles will be shown at human-friendly, first-rate urls:

```
https://openscihub.org/<article_alias>
```

where `article_alias` is chosen by the submitter and comprises
the characters `a-z`, `0-9`, and `-`.  Openscihub will *require* the hyphen
character to differentiate between other url endpoints such as
`https://openscihub.org/users`, `https://openscihub.org/communities`, etc.

The alias should identify the article as succinctly as possible, and be
human-readable. This usually means picking terms from the title, and possibly
incorporating author, year, institution, and/or collaboration information. For
example,

```
https://openscihub.org/bethe-small-hole-diffraction
```

might be a good alias for Hans Bethe's seminal paper *Theory of Diffraction by
Small Holes*.

## Canons

Articles can be submitted to and accepted by communities. This is little more
than a declaration of respect that the community has for the article; the
article becomes a piece of the *community canon*.

Community canons will help seedling researchers learn the ropes without the
senseless manual traverse of citation graphs. They will be contributing
breakthroughs in record time, we guarantee it<sup>1</sup>! It's community
mentorship!

<sup>1</sup>*We do not guarantee it.*

## Reviews

A review is a layer of annotations and write-ups on an article. *Any* user (even
non-experts) may write a review of *any* article; however, the target audience of
a review is restricted by the status of the reviewer (more on this in the
[following section](#review-scope)).

Details of the review interface are yet to be determined, but should allow for:

- annotations anywhere on the PDF,
- equation rendering, and/or
- long, standalone write-ups, possibly uploaded PDF.


### Scope

Openscihub should *never* stifle discussion, yet discussions should be useful
for all walks of users. Openscihub addresses this complexity with
*review scope*.

Every reviewer must specify a set of communities as the *intended* audience.
By default, this set comprises the communities of which the reviewer is a
member. The reviewer can trim this set when appropriate (remove communities),
but can only add to it if she joins additional communities. In other words, the
target audience is always a subset of the communities to which the reviewer
belongs.

The purpose of such a system is to help readers filter out those discussions
that would otherwise add to the noise.

For example, consider an article about some novel kind of holey-fiber
telecommunications waveguide. A science writer, Dave, is interested in the
article but is unfamiliar with photonic crystals and therefore composes a
review requesting more background information.  If Dave is a member of only the
two openscihub communities, *public* and *science writers*, a reader from the
*optoelectronics* community, Susan, can ignore Dave's review
(and the resulting discussion of photonic crystals) by "turning off" the
*public* and *science writers* target audiences. Similarly, Dave can ignore any
esoteric discussions between Susan and other *optoelectronics* community
members by turning off the *optoelectronics* target audience.

### Moderation

Reviews will be subject to voting a la the well-established
StackOverflow/Reddit models (single upvote or downvote per review per user) and
moderation by community moderators. Community moderators will have control over
only those reviews written by members of their community. All users are members
of the public community and are therefore subject to super-moderation by the
openscihub anti-abuse task force :|.
