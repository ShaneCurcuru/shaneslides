---
title: The OFA Symposium was amazing!
excerpt: "OFA Symposium at Digital Data Design Institute, Harvard"
description: "Amazing conference of research and practice together."
dates: 13-14 November 2024
location: Boston, MA
conference: Open Forum Academy Symposium
eventurl: https://symposium.openforumeurope.org/
layout: trip
---

I was fortunate to be invited to the Open Forum Academy Symposium, a curated event bringing together researchers and practitioners who work on open source software.  It was a chance to see a number of new research papers exploring open source code, communities, funding, impacts, and more.  Even better, it became a true collaboration with practitioners, working together to improve the impact of research, and collaborating on key tools and metrics.

## My Day 1 Themes: Funding and Open Source; Economics

The first day I spent in the economics track: papers around how FOSS work is funded, how to measure impacts, and ideas and proposals for fairer and more efficient ways to support open source work economically.  Seeing the work that went into research papers here was humbling, even though I've done a little bit of work on this myself on the [FOSS Funding](https://fossfunding.com/) and [FOSS Sustainability](https://fosssustainability.com/) sites.  The panel discussions and fireside chats were also enlightening; I could see attendees of all types having "ah-ha!" moments throughout the day.

## My Day 2 Theme: Open Source Ecosystems

The key topics for me this day were around serious research about community structure, governance, and funding, as relating to outcomes and methods.  There are definitely real research answers that have practical value to many FOSS communities here; the question is finding ways to translate the academic papers into practical advice, suited for each community.

I was also asked to join a panel of other prestigious academics and FOSS luminaries.  Again, the questions we got and discussions we led show that there are plenty of wins for both academics and developers alike, if we can better coordinate our two worlds.

## Lessons And Notes

There were several major themes through the event that struck me.

- Researchers take the easy way out, and end up using data that takes zero or very low effort.  Paper after paper carefully described how they selected appropriate populations of GitHub repositories to study such-and-such...  And I raise my hand and ask: Did you consider how many open source projects aren't on GitHub?  This is understandable given academic institution reward structures, but is definitely skewing results.  See this [Ecosyste.ms repo service issue](https://github.com/ecosyste-ms/repos/issues/716) for one small step to improve this.
- Researchers *want* to get feedback from communities!  The first and simplest issue is: they don't know where to ask for permissions, or what kind of communication standards different communities use.  The result seems to be that some research isn't focused on as impactful questions as it could be.  One first step here is simply having discoverable "Research Information Portals" at any FOSS Foundations or the like.  See the [ASF's Research Portal](https://apache.org/research/).
- Practitioners don't read research papers.  While peer-reviewed research has reasons for the length and complexity of paper formats, where is the *"good enough"* guide for developers and FOSS community members on "How To Get The Gist Of Academic Papers"?  It would be lovely if papers could have a "practical conclusions" section, that explained in laymen's terms what use the data might be to a community that was studied; but that's a big ask.  How can we build some guides for reading research papers to make sense for the developers they are studying?
- Networking.  As in any industry, there are obvious ways for networking within academic institutions, funding or grantmaking institutions, and in various open source or technical ecosystems.  But how do we bridge the gap for the respected researchers who want to reach out to people who manage open source communities at scale?  How can Foundation or major FOSS project leaders gain entry into the hallowed ivory halls, to get pointers to the researchers who are using our open source data?
- Mapping and attestations.  Several deep research questions, especially around the loosely-governed FOSS ecosystem, came down to: how do we map this commit to one person?  How can we associate a person or project with various entities, like FOSS Foundations, corporate players, or governmental IT departments?  What automatable ways to do mapping are sufficiently accurate to be useful?

## Thank Yous and Connections

Thanks to the event organizers; it was well run and very useful for all attendees that I saw.  Thanks also to the local host from Harvard, Asst. Professor Frank Nagle, for providing the space, as well as some welcoming talks that really helped connect some wicked big themes to the local area.

## Key Connections

### Attestations and organizational mapping

There are several different people/groups interested in creating ways at the individual level, and organizational level, to implicitly or explicitly map code / repos, to projects, to organizations, and more.  A few rough links on this topic that I'd love to help collaborate on this:

- Julia Ferraioli (and others!) [work around open source community research](https://www.juliaferraioli.com/pub/). 
- [Ecosyste.ms tools and roadmaps](https://github.com/ecosyste-ms/roadmap), especially [issue #19](https://github.com/ecosyste-ms/roadmap/issues/19).
- [FOSS Foundations metadata directory](https://fossfoundation.info/), extending the [Foundation schema](https://github.com/Punderthings/fossfoundation/blob/main/_data/foundations-schema.json).
- [RFC 8615 Well-known resource identifiers](https://datatracker.ietf.org/doc/html/rfc8615) as a way for organizations to provide attestation hints.  Various RFCs or listed well-known URIs that have potentially similar mapping fields that could be used (either directly or as inspiration):
  - [RFC 7072](https://www.rfc-editor.org/rfc/rfc7072.html) A Reputation Query Protocol
  - [RFC 7033](https://www.rfc-editor.org/rfc/rfc7033.html) WebFinger
  - [.well-known/openorg](https://opd.data.ac.uk/) Organization Profile Documents
  - [.well-known/trust.txt](https://journallist.net/) "a system of helping the digital robots of the world know about groups that have formed to express some trust in each other"
  - Deductions made from various security/key/PKI/OpenID related well-known ids (where some organizational reference is implicit somewhere)
- [NumFOCUS Open Source Science project](https://numfocus.org/open-source-science-initiative-ossci) and the [MOSS Map](https://github.com/numfocus/MOSS).
- Various ideas that could riff on existing [CHAOSS metrics](https://chaoss.community/) structures.
- Several other OFA attendees who were coming up with ideas!

Apologies for any obvious omissions; happy to add other people working on ways to do attestations and mapping in FOSS community or development spaces.
