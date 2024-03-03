layout: true
name: fullheader
background-image: url(../apachecon/img/neonbrand-258972-unsplash-sm.jpg)
background-size: cover

---
layout: true
name: contributions
background-image: url(../apachecon/img/rawpixel-600782-unsplash-sm.jpg)
background-size: cover

---
layout: true
name: thanks
background-image: url(../client/img/stuart-guest-smith-150560-169.jpg)
background-size: cover

---
layout: true
name: fosdem
background-image: url(img/KaraSowles-FOSDEM2024-Slide6.png)
background-size: cover

---
layout: true
name: logorb
class: left
background-image: url(img/23_FOSSBack_Logo_standard_colour_300px.png)
background-repeat: no-repeat
background-position: bottom .8rem right 5rem
background-size: 10%

---
template: fullheader
# Who Funds FOSS Foundations?
## Modeling Open Source Foundation Sponsorships

.left-column-equal[
### [@ShaneCurcuru](https://twitter.com/shanecurcuru)
### [FOSSSustainability.com/FOSSBack](https://fosssustainability.com/fossback)
]

---
template: logorb
# Resources

## [FOSSSustainability.com/FOSSBack](https://fosssustainability.com/fossback)

???
Please follow along at fosssustainability.com/fossback for links to slides
and all the data and code associated with this project!

---
template: logorb
# Topics

- Aspects of Sustainability
- Modeling Foundation Sponsorships
- Financial Data of Key Foundations

???
Topics for today...
**SPACEBAR**

--

- *Finding better questions to ask*

???
I hope to leave everyone with enough information and ideas, so that you can start asking better questions when you're working on sustainability.

---
template: logorb
# Aspects of Sustainability

.left-column-equal[
**Who**

- Users
- Contributors
- Maintainers
- PMC / TSC
]
.right-column-equal[
**What**
- Software Companies
- Non-Software Companies
- Educational Institutions
- Governments
- Standards Bodies
]

???
Listening to people talk about sustainability, I'm often struck by how siloed the conversations are.  Each participant is coming in with their own needs and their own vocabulary, and it's often hard to find efficient ways to translate one aspect's needs to the vocabulary or taxonomy some other aspect needs.

---
template: logorb
# Aspects of Sustainability

.left-column-equal[
**Who**

- Users
- Contributors
- Maintainers
- PMC / TSC
]
.right-column-equal[
**What**
- Software Companies
- Non-Software Companies
- Educational Institutions
- Governments
- Standards Bodies
]

???
TODO: story showing example of two groups talking past each other.

---
template: logorb
# Aspects of Sustainability

> TODO: Wrapup sustainability sidebar.

???

---
template: logorb
# TODO: Introduce c3/c6

> TODO: IRS 990 and c3/c6 distinctions

???

---
template: fosdem

???
TODO: Define where/how to show Kara's slide

This is an excellent holistic overview of how funding typically gets to open source contributors, foundations, and more.  From [Kara Sowles' excellent talk at FOSDEM](https://fosdem.org/2024/schedule/event/fosdem-2024-2751-the-state-of-funding-free-open-source-software/) this year.

---
template: logorb
# TODO: bridge slide

> TODO: define the story behind the different kinds of data here

???

---
template: logorb
# Sponsorship Program Modeling

## TODO: sponsorship model

- Intro and model
- Data captured so far
- Observations

???

---
template: logorb
# FOSS Financials

## TODO: story of finances as told by 990s

- Intro and model
- Data captured so far
- Graphs
- Observations

???

---
template: logorb
# TODO: bridge slides

> TODO: define the story beind the different kinds of data here

???

---
template: logorb
# Who pays for FOSS Foundations?

What does that actually mean?

- What is **open source**?
- **How do you pay** for it?
- What **things or activities** are paid for?
- How do **Foundations** get funded?

???
Talking with 5 people about "FOSS Funding" gives you 10 different topics to cover, so let's define what we're covering here today.

First off, some brief definitions:

The important question: what are the **different ways to contribute** to open source - code, services, activities, events, sponsorships

Then we'll talk money - how key FOSS Foundations get funded

I expect many of you will end up with more questions to ask after this talk - there are many other areas of "funding" to cover out there, and I'm hoping this overview will make you think a little more about how open source works at scale, especially with larger projects or the many foundations that provide a home to so many important projects out there.

---
template: contributions
# Most major open source is from companies

???
Here's my belief: most of the major open source projects used today are now primarily built and maintained by companies directly paying their employees to contribute.  Let's see what data from some major projects show.

---
template: logorb
# Linux kernel development

The Linux Kernel Report tracks which companies are sponsoring kernel development.

???
The Linux Kernel Report does a thorough analysis of both who's contributing all the code, as well as who they're working for or being paid by.

**SPACEBAR**

--

- In 2020, at least **83%** of code was *paid corporate work*

--

- 2018 it was 85%
- 2016 it was 80%
- 2015 it was 80%
- 2013 it was 80%
- 2012 it was 75%
- 2010 it was 70%

???
The great majority of work done in the Linux kernel is done directly by corporations (having their employees make the fixes), and this number is only going up over time.

---
template: logorb
# Apache software committers

Survey: how Apache committers contribute to their projects.

- ~**50%** replied it was as an *Employee (as their job)*
- ~40% replied as an *Individual (outside regular job)*
- ~10% were *Retired, students, other*

.code[https://s.apache.org/2016dsurvey]

???
Let's look at the ASF - which has hundreds of Apache project communities.  In 2016 we ran a survey.

The ASF ran a similar survey this year, which also shows a high percentage of work on our projects is directly paid.

---
template: logorb
# Drupal commits and sponsors

Drupal regularly updates their contribution reports - in 2021:

- **68%** of code was *Wholly sponsored work*
- 16% was *Work that's a mix or not credited*
- 16% was *Purely volunteer work*

.code[https://dri.es/who-sponsors-drupal-development-2021]

???
Drupals' credit system uses commit logs to show not just who wrote the code, but if the contributor was sponsored or paid to do make that commit by a company or other entity.  That counts either software vendor employees, or consultants or integrators working for end users.

The ratio of sponsored to not sponsored is increasing over time, and my bet is a similar ratio is in most of the widely-used software products in business today.  See details of the program: https://www.drupal.org/drupalorg/contribution-credit

---
template: logorb
# Services Foundations provide

Foundations provide:

- Governance
- Mentoring
- Legal shield
- Fundraising
- Hosting, build pipelines, clouds
- Respectability / brand management
- Events
- Community education / management
- Marketing / ecosystem development

???
We still rely on many volunteers to help, but when it comes to reviewing contracts or doing the accounting on donations, we need hired help.  Accounting volunteers are rare to find in the coding world, and few coders want to carry a beeper for 24x7 support when the server goes down.  All these services we need money for.

All of these services are hard to provide at scale with volunteers - so Foundations are needed to provide the fiscal organization to pay someone to provide them.

---
template: fullheader
# Comparative Review: Foundation Services & Funding

???
Non-profit foundations attract some donations - from individuals or small businesses who want to say thanks for the software we provide.  But the bulk of funding for most software non-profits comes from corporate grants or recurring sponsors.

How do these foundations get their money?  Primarily recurring corporate sponsorships.

Let's review some key FOSS Foundations, and how they're funded.

---
template: logorb
# Software Freedom Conservancy

.left-column-equal[
**Project Overview**
- 42 projects
- Independent governance
- Independent branding
- Focus on software freedom
]
.right-column-equal[
**Scalable Services**
- Legal
- IP stewardship
- Fiscal fundraising host
- GPL compliance
]

.bottomnote[Conservancy is a **501C3** Public Charity]

???
Conservancy offers basic fiscal sponsorship services, along with some legal and IP support.  Additional services may be available resources permitting when projects make requests.

---
template: logorb
# Conservancy - Sponsors

Conservancy's current major sponsors are:

.left-column-equal[
- Amateur Radio Digital Communications
- Code Weavers
- Google
- iFixit
- Indeed
]
.right-column-equal[
- JMP
- Mozilla
- Mark Wielaard
- David Turner
- Danielle Sucher
]

.bottomnote[Conservancy is a **501C3** Public Charity]

???
Conservancy lists their major sponsors, along with a number of smaller, individual sponsors.  Conservancy doesn't list sponsorship amounts, but my bet is that the above sponsors provide the bulk of Conservancy's annual income.

---
template: logorb
# Conservancy - Funding

.left-column-equal[
<img src="img/conservancy-income-2023.png" style="width: 95%" />
]
.right-column-equal[
<img src="img/conservancy-assets-2023.png" style="width: 95%" />
]

???
On the left, we see Conservancy's annual gross income for the past few years, primarily from donations.  Conservancy's income is on a steady upward trend, surpassing $4M in 2021, the last year that official IRS 990 forms are available for.

On the right, we can see Conservancy's Net Assets - cash in the bank or investments for their continuing operations, which also has a solid upwards trend surpassing $6M in 2021.

---
template: logorb
# Apache Software Foundation

.left-column-equal[
**Project Overview**
- 200+ projects
- Apache Way governance
- Apache *Project* branding
- Focus on community over code
]
.right-column-equal[
**Scalable Services**
- Legal
- IP stewardship
- Infrastructure
- Conferences
- Community mentoring
- Lifecycle support
]

.bottomnote[ASF is a **501C3** Public Charity]

???
The ASF hosts well over 200 Apache project communities.  While each project is managed independently, the board provides oversight to ensure they are following the Apache Way.  The ASF also provides hosting and infra, and especially community mentorship, as well as lifecycle support in the Apache Incubator and Apache Attic.

---
template: logorb
# Apache - Sponsors

Apache's Platinum sponsors are:

.left-column-equal[
- Amazon Web Services
- Apple
- Microsoft
- Huawei
- Pineapple Fund
]
.right-column-equal[
- yahoo!
- Facebook
- Google
- VMWare
]

.bottomnote[ASF is a **501C3** Public Charity]

???
Those are just the platinum sponsors, but they represent about $800K in annual donations, or about half the financial income for the entire ASF.  These sponsors get a thank you and a listing on our webpage, but otherwise have no influence over how the ASF or Apache projects are run.

Thank you to all the ASF sponsors, Gold, Silver, Bronze, and in-kind sponsors too as well as all our ApacheCon event sponsors!

---
template: logorb
# Apache - In-Kind Sponsors

Apache's Targeted *(In-Kind/Services)* Platinum sponsors are:

.left-column-equal[
- GitHub
- DLAPiper
- leaseweb
- Microsoft
- yahoo!
- Sonatype
- CloudBees
]
.right-column-equal[
- OSU Open Source Lab
- JetBrains
- fastly
- JFrog
- AWS
- Gradle
]

.bottomnote[ASF is a **501C3** Public Charity]

???
There are more ways to organizationally support Apache than just donating cash.  Each of these organizations is a Targeted Platinum sponsor, meaning they donate the equivalent of a Platinum sponsorship of hosting services, bandwidth, cloud credits, and CI pipelines or testing resources to Apache projects.

Importantly, these are all services that Apache projects directly need and are actually using.

---
template: logorb
# Apache - Funding

.left-column-equal[
<img src="img/apache-income-2023.png" style="width: 95%" />
]
.right-column-equal[
<img src="img/apache-assets-2023.png" style="width: 95%" />
]

???
Here we can see the ASF's income and assets - an average of about $1million annual income, with the singular blip of the Pineapple fund one-time donation in 2017.  More projects and more services that Conservancy, but slightly smaller funding numbers.

Note that all numbers here are taken directly from the 990 tax forms that all US charities file with the IRS.

---
template: logorb
# NumFocus

.left-column-equal[
**Project Overview**
- 60 hosted projects
- 60+ affiliated projects
- Independent brands & governance
- Focus on science & Python
]
.right-column-equal[
**Scalable Services**
- Legal
- IP stewardship
- Conferences
- Community mentoring
- Fiscal fundraising host
]

.bottomnote[NumFocus is a **501C3** Public Charity]

???
NumFocus is another typical FOSS project host, with a wide variety of scientific projects.  Hosted projects are offerred a full variety of services, and some affilated projects choose just some of the services they need.

---
template: logorb
# NumFocus - Sponsors

NumFocus' Principal Corporate Sponsors are:

.left-column-equal[
- Bloomberg
- IBM
- posit
- AWS
]
.right-column-equal[
- Anaconda
- bodo.ai
- T.Rowe Price
- Google
]

.bottomnote[NumFocus is a **501C3** Public Charity]

???
NumFocus has a similar set of corporate or major sponsors much like other foundations here, and also has support from some scientific grantmaking and similar organizations.

---
template: logorb
# NumFocus - Funding

.left-column-equal[
<img src="img/numfocus-income-2023.png" style="width: 95%" />
]
.right-column-equal[
<img src="img/numfocus-assets-2023.png" style="width: 95%" />
]

???
NumFocus shows a roughly similar funding picture as the previous foundations.  There are likely differences in the ways NumFocus is funded given their strong focus on scientific and research projects - meaning both different types of corporations interested, as well as much more of an opportunity for grants.

---
template: logorb
# Linux Foundation

.left-column-equal[
**Project Overview**
- LOTS of foundations
- Industry/Community mixed governance
- Independent branding
- Multiple project scales
]
.right-column-equal[
**Scalable Services**
- Legal / IP stewardship
- Infrastructure
- Development process support
- Community management
- Ecosystem development
- Marketing
- Conferences
]

.bottomnote[Linux Foundation is a **501C6** Business League]

???
The Linux Foundation has a large number projects, several of them giant factors in today's software world.  They also operate with an agency model, where Linux Foundation employees provide a wide variety of services to projects - some employees are directly assigned to specific projects.

---
template: logorb
# Linux Foundation - Sponsors

That's a complicated question.

Many Linux Foundation projects have their **own funding models**.

???

---
template: logorb
# Linux Foundation - Sponsors

The Platinum Corporate Members of the Linux Foundation:

.left-column-equal[
- Ericsson
- Fujitsu
- Hitachi
- Huawei
- Intel
- Meta
- Microsoft
]
.right-column-equal[
- NEC
- Oracle
- Qualcomm
- Red Hat
- Samsung
- Tencent
- VMWare
]

???
Each platinum member/sponsor of the Linux Foundation as a whole reportedly pays about 500K annually, and provides representatives both on the board of the foundation as well as in various technical bodies of collaborative projects.

This list represents **over 7M of annual income** for the Linux Foundation.

---
template: logorb
# CNCF - Sponsors

The eighteen Platinum member sponsors of the CNCF are:

.left-column-equal[
- Alibaba Cloud
- AWS
- Apple
- ARM Holdings
- Cisco
- Fujitsu
- Google Cloud
- Huawei
- IBM Cloud
]
.right-column-equal[
- Intel
- JD.Com
- Microsoft Azure
- Net App
- Oracle
- Paloalto Networks
- RedHat
- SAP
- VMWare
]

???

The Cloud Native Computing Foundation is a subsidiary of the Linux Foundation, and just for the CNCF, they have this list of platinum sponsors, each of which are donating in the range of 250K or more annually to the CNCF.

These are just sponsoring the CNCF, and likely represents at least **4M in annual income**, if not more, for the CNCF and Linux Foundation.

---
template: logorb
# Hyperledger Foundation - Sponsors

The Premiere Members of Hyperledger are:

- Accenture
- DTCC
- Fujitsu
- Hitachi
- IBM

???
Each of these premier members for Hyperledger likely provides at least 250K annual donation, as well as employees working on the project.

---
template: logorb
# Who Sponsors The Linux Foundation?

... and the 200+ Collaborative Projects at the LF?

**Answer:** A lot of companies, many repeatedly.

???
There are probably a dozen **major** collaborative projects, each with their own sponsors (and products), and another hundred plus or so smaller projects - still interesting, but with fewer or little direct funding.

In particular, you'll note there are many software vendors - and non-software companies! - who are sponsoring multiple projects at the LF with cash as well as contributions.

---
template: logorb
# Linux Foundation - Funding

.left-column-equal[
<img src="img/linux-income-2023.png" style="width: 95%" />
]

.right-column-equal[
<img src="img/linux-assets-2023.png" style="width: 95%" />
]

???
Here we can see the LF's income and assets.  Huh.  Those are pretty big numbers - these charts are an order of magnitude higher than the earlier charts.  In 2021, LF made $140 million in income, and listed net assets of $89 million.

Anyone surprised at these numbers?  Remember: these figures are from 2018, the most year IRS 990 forms are available for.  As a Business League, the LF doesn't otherwise provide public budget figures, so we don't know what their 2019 income was, or what the blip in their net assets over 2017 was.

---
template: thanks
name: closingslide
class: inverse-header
# Foundations Data

FOSS Foundations metadata and models

.code[https://fossfoundation.info/]

Do your own US funding research

.code[https://projects.propublica.org/nonprofits/]

Open Source Sustainability research

.code[https://fosssustainability.com/]

---
name: last-page
template: thanks

## Thank You &amp; Questions!

## [@ShaneCurcuru](https://twitter.com/shanecurcuru)
.code[https://shaneslides.com]

<a rel="license" class="code" href="https://www.apache.org/licenses/LICENSE-2.0.html">Apache v2.0</a>

---
template: logorb
# Other topics to investigate

- RedisLabs and the Commons Clause
  - Source-Available or Cloud Licenses
- Open Source Sustainability
  - [Aspects of sustainability](https://fosssustainability.com/aspects/)
  - [FOSS Sustainability Zotero library](https://www.zotero.org/groups/5030713/foss-sustainability/library)
  - [Defining FOSS Project Health](https://fosssustainability.com/health)
- [Reviewing funding models](https://fossfunding.com/#how-are-individual-projects-or-maintainers-funded)
  - Patreon and crowdfunding
  - Bountysource pays for specific work
  - Tidelift, Liberapay, Open Collective and subscriptions
  - Building your own business model

???
There's a lot more to talk about out there - I look forward to your ideas!

---
template: logorb
# Open Source is a ________________

- Sustainable contribution model.
- Model for broad innovation.
- **NOT** a Business model.

## What does "Open Source Sustainability" mean to you?

???
Yes, this is a trick question.
https://medium.com/@stephenrwalli/there-is-still-no-open-source-business-model-8748738faa43