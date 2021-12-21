The goal of the initiative is to enhance research replicability,
transparency, and integrity in the social sciences, not just in economics, across the entire research lifecycle, and from undergraduate education through research support to academic publications.

All of those domains are currently lacking in critical pieces of support.

## Goals

  - > **Researcher support** for
    > achieving intellectual integrity (reproducibility, transparency,
    > statistical validity) when creating, using, and sharing data and
    > research

  - > **Educational support** for undergraduates, graduates, and experienced researchers.

  - > **Research into** replicability,
    > transparency, and integrity **methods and
    > tools** for attaining that primary goal

  - > **Cross-disciplinary and university-wide
    > involvement: Social science disciplines** (Economics,
    > Sociology, Demography, Political Science, etc.) and
    > **Data Sciences** (Information
    > Science, Statistics, Computer Science, Libraries)

# Key feature in the short term: Institutional support

Institutional support is critical. Currently, transaction costs are too high, creating barriers to adoption of reproducible practices.

Fundamentally, reproducibility requires a cross-disciplinary skill set. Whether such skill sets are brought to bear by individual researchers or by researcher teams may depend on disciplinary habits and skill sets. Much of the cross-disciplinary skills can be simplified through novel infrastructure and techniques.

When I define this as an institutional task, I view "institutions" very broadly:

- **universities** provide educational support for undergraduates and graduate students, and provide training support for new and established researchers.
- **research institutions**, which include universities, but also non-academic or governmental research institutions producing academic research, such as non-profits, statistical agencies, international agencies, or central banks, provide infrastructure, technical and human support at various stages of the research lifecycle, including setting up research projects as reproducible by default, providing internal and external data and code repositories, and as providers of computational infrastructure and software. 
- **providers of confidential or restricted data** have a special role, since they often cannot delegate such roles to researchers' home institutions, and must have access protocols in place that can slow down if not impede reproducibility attempts.

# Webinar series: institutional approaches

The webinar series would be a series of panels, moderated by Lars Vilhuber. It heavily relies on observations of behaviors, problems, attitudes seen in the 600+ articles reviewed by the LDI Replication Lab for the AEA.

## Introductory presentation

Lars Vilhuber

"An overview of needs, concerns, and challenges in providing reproducibility across the research lifecycle"

## Disciplinary support: why is reproducibility not uniformly required across disciplines?

Moderator: BITSS (Ted Miguel)

- Kim Weeden or Philip Cohen (Sociology)
- Esther Duflo or Hilary Hoynes (Economics)
- (Criminology)
- (Statistics)
- (Political Science)

## Institutional support: Verifying reproducibility at journals

Why journals may have a role in verifying reproducibility 

Moderator: TBD

Participants

- self (AEA - yes) (or Esther Duflo)
- (one of the other Econ Data Editors) (yes)
- (Statistics) (sometimes)
- Ben Greiner (Management) (yes)
- Kim Weeden (Sociology) (no)

## Institutional support: Verifying reproducibility at research institutions

Is there a role for institutions to verify reproducibility 

Moderator: Self

Participants:

- (Yale) - has a service part of CURE
- (CSCU, Cornell) - statistical consulting service during the lifecycle but not at the end
- (Federal Reserve system - Board has interest/concerns)
- Lucia Foster/Ron Jarmin (Census Bureau) challenges in setting up such a system
- cascad.tech (institution providing reproducibility services)

## Institutional support: Publishing replication packages at research institutions

Why can or should institutions publish replication packages? Should that be as 

Moderator: Self

Participants:

- Florio Arguillas (Cornell University, Data and Code Reproducibility Archive)
- (NBER) - which sometimes posts packages
- (Federal Reserve system - KS Fed posts replication packages)
- (Urban Institute) transparency by non-profit research institutions

## Teaching reproducibility: Undergraduate version

Can teaching reproducibility be a part of undergraduate education/curriculum?

Moderator: TBD

Participants:

- TIER Project
- Fed St. Louis / EconLowDown/ Page One
- Self (training for reproducibility checks)

## Teaching reproducibility: Graduate version

Whether and How to integrate reproducibility into Social Science? 

[NOTE: possible COI - we have an NRT proposal on this. Might want to schedule this AFTER the NRT panels are done]

Moderator: Self

Participants:
- Ken Bollen (UNC, Psychology/Sociology) 
- Julian Greif (Economics)
- Ariel Ortiz-Bobea (Cornell, Ag-Econ)
- (Statistics)

## Beyond Data Management Plans: Should funders require reproducibility?

Should funders require reproducible archives, and how would that work?

Moderator: self

- NSF (?)
- Sloan (Daniel Goroff)
- Arnold (Stuart Buck)
- 3ie (?)

## Computational support for reproducibility

Best practices in 3 slides

- Stata
- R
- Matlab
- Julia/Python
- how to verify reproducibility (hint: not by running on your own computer)

## Computational support for reproducibility - the cutting edge

How to go from reproducible research to robust reproducible research that is archived.

- Github is not an archive
- Containers or virtual machines: what are they and how to use them?
- Going from internal reproducibility to external reproducibility

## Why require reproducibility? The Twitter version

Participants:
- Jennifer Doleac (skeptic)
- Grant McDermott (pro)
- Lars Vilhuber (pro)
- (other?) (skeptic)

Special: live on twitter/services

## Additional support services

Moderator: Self

- Reproducibility and ethics approval - a conversation with IRBs
- Everything social scientists should know about licences and copyrights (Victoria Stodden?)
- Everything data providers should know about licenses, copyrights, data citations


# **Additional Actions**

The following are some of the additional possible/feasible projects that support the themes outlined in the webinar series, and the topics outlined later in this document.

## Reproducibility and Equity

I often hear concerns that the requirement for reproducibility is for the well-established researchers, and prevents less-well-funded researchers or universities, or junior researchers, from publishing, or from publishing on-time. My intuition and my experience tells me that this is far from the truth, but that there is a kernel of truth in it. The following two sub-projects would test/alleviate such concerns explicitly.

### (Branded) training for reproducibility summer program for undergraduates from minority-serving institutions

Scaling up existing training initiatives (Project TIER, LDI Replication Lab training) to provide cross-university training, targeting minority-serving institutions (HBCUs and HHEs). Might be combined with Sloan initiatives supporting Carpentries training in economics (https://datacarpentry.org/lessons/#economics-curriculum) and/or Project TIER training. Focus is not only on imparting reproducible practices, but on skills that allow to recognize and verify reproducibility in other work. Students can apply, need a letter of recommendation from one of their faculty attesting to minimal qualifications (know how to run statistical software). Pre-requisites can be met by non-university accreditation (e.g., Carpentries).

Bonus: the training might be followed up with an "internship" at a journal or a university-based verification lab, conducting reproducibility check. Some of these may qualify for self-directed research or credit-internships.

Role of NSF: Provide branding, and university-independent funding (students would apply for stipend directly?)

### Variant with confidential data

Various institutions have access to restricted-access data (confidential, proprietary). Interns are often placed at such institutions (Fed system, Census Bureau, BLS). We would leverage and/or expand such existing placements, provide training, and the hosting institution would be able to conduct "reproducibility spot-checks" on some of their internal work prior to submission to journals. The workshops *and* verifications would be run by existing reproducibility checking experts (data editors including self, Odum institute at UNC, Rsquared at Cornell, cascad.tech). There are benefits to the students (internships and reproducibility expertise), and to the hosting institutions.

Role of NSF: Funding to expand the program, time and travel for trainers. Might flow through existing funding for such activities. 

# **Activities/Domains**

This section provides an overview of various topics. Lots of overlap with the above.

## Replicability Standards

While many reproducibility suggestions exist, too many researchers
follow none. Clarifying the standards to follow and articulating
feasibly-implemented standards by example and in software will improve
acceptance and adherence. Who is setting standards?
Possibly  by collaborating with journals and scholarly associations, drive
adoption by researchers.

  - **Research** into and development of open and transparent
    replicability standards in the social sciences, in collaboration and
    coordination with the various entities on campus and off-campus.
    (For example: how to avoid overly redundant storage of data across
    multiple studies; effective synthetic data)

  - **Develop** (discipline-wide) “certification” standards and convey
    compliance with those standards (for researchers, articles/ papers,
    and research)

## Standing up Reproducibility Services, Confidential Data

Pre-submission verification of reproducibility reduces the load on
journals, enhances the reputation of the University or Network, and provides early
feedback to researchers. When access to data is restricted for privacy
reasons, verification of reproducibility is not possible
post-publication, making embedded pre-publication services critically
important. The initiative will

  - **Provide** reproducibility (verification) services for
    **confidential data** in the Federal
    Statistical Research Data Center (FSRDC). Researchers nationwide
    will be users. This
    is already being discussed with the Census Bureau, and could be extended at a later stage to
    other restricted-access enclaves: University-based ones (Cornell Restricted Access Data Center
    \[CRADC\]), NORC Data Enclave), German and Canadian RDC, etc. There is potential for grant
    funding/cost recovery across a national network.

  - **Provide** specialized verification services for
    **proprietary data** (Wharton Research Data Services, Kilts Center, etc.)

### ***Reproducibility Training***

We believe that reproducibility should be an integral part of the
standard workflow that students and researchers follow. This requires
that they receive training, and be able to convey that they have
received such training.

  - Training of undergraduate and graduate
    **RAs**: Model curriculum for research labs

  - Training of undergraduate and graduate
    **students**: NRT and similar practices [already NRT proposal!]

## Scientific Publication and Reproducibility

Data and code linkage to published outputs is currently weak and
heterogeneous. Scientists adhering to proper standards need to see the
output of such efforts, and be visibly rewarded. However flawed
bibliometrics might be, reproducibility can be measured through
citations, linkages, and visualizations.

  - Visibility of reproducible research: research into standards,
    methods, and their effectiveness

  - Articulation of data curation standards to journals, preprint
    repositories (RePEc, arXiv, other \*Xivs) and vice-versa: how to
    move the linkage of data and research output into the preprint or
    grey literature (early efforts: Kansas City Federal Reserve Bank,
    National Bureau of Economic Research)

  - Research into inference robustness in published statistics,
    effectiveness of various incentive mechanisms (data sharing, badges,
    open-access)

## Sustainability and Cost/Benefits of Reproducibility 

  - Community of practice amongst Data Editor of journals (starting to
    emerge in Econ under Vilhuber's leadership, interest from other
    domains)

  - Research into cost to journals or universities, willingness to pay by universities or researchers

  - Research into delay to publication speed, reduction in scientific efficacy

  - Developing a robust cross-journal/multi-disciplinary set of curated "best practices" 
    - build off of social-science-data-editors.github.io website
    - curation is important - quite a few websites propose "dumping grounds" without good quality metrics (popular != reproducible or FAIR)

## Infrastructure

  - Support for third-party data communities: NIH often supports central archives, these are less commonly used or demanded in economics or social sciences
    - ICPSR, Dataverse exist, provide some aspects
    - Poor integration with third-party websites (Dataverse, Zenodo have deposit API)
  - Development of robust APIs to data repositories
    - Dataverse has *emerging* API (not robust), Zenodo has data query API
    - ICPSR, others do not
    - Questions of licensing, etc.