---
permalink: /
title: "Homepage"
excerpt: "Natalie Neamtu's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third year PhD student in Computer Science at Carnegie Mellon University
where I am advised by [Bryan Parno](https://www.andrew.cmu.edu/user/bparno/).

My interests lie in formal guarantees for the correctness of software and systems.
My research focuses on formal verification of low-level, unsafe Rust 
using the [Verus](https://github.com/verus-lang/verus) verifier.
My current projects span weak memory concurrency, 
typed and untyped models of Rust ownership,
LLM-based proof generation,
and specification autoformalization.

I graduated in 2021 from Cornell University, where my research on
formal and informal models of distributed consensus protocols was advised
by [Robbert van Renesse](https://www.cs.cornell.edu/home/rvr/). 
After that, I worked on data-centric problems for Bing's knowledge graph,
including using LLMs for high-quality semi-structured data extraction and unstructured data generation.

### News
* *April 2026*: I presented our ongoing work "Supporting Weak Memory in Creusot and Verus" 
at the [Rust Verification Workshop](https://sites.google.com/view/rustverify2026/home?pli=1&authuser=0)
(co-located with ETAPS) in Turin, Italy.
* *May 2025*: I started an internship at the Systems Research Group at Microsoft Research.
* *September 2024*: I quit my job (and, more importantly, started my PhD)!!
* *August 2023:* I was awarded an [NSF CSGrad4US Graduate Fellowship](https://www.nsf.gov/cise/CSGrad4US/).
* *May 2023:* I presented "Trees and Turtles: Modular Abstractions for State Machine Replication" at [PaPoC](https://papoc-workshop.github.io/2023/) (co-organized with EuroSys) in Rome, Italy.
* *May 2021:* I was named a [Merrill Presidential Scholar](https://news.cornell.edu/stories/2021/05/merrill-scholars-thank-educators-who-shaped-cornell-journeys) (and got quoted in Cornell's write-up!). Thanks to Robbert and Mr. Fagan for their support over the years!
* *May 2021:* I was one of two graduating seniors to receive the
 **Alan S. Marx Memorial Prize for Excellence in Undergraduate Teaching**
from Cornell's computer science department. Thanks to Michael and Fred for
their mentorship during my time as their TAs, 
and to all of my teachers who have inspired me to love learning and teaching!

Education
======
* B.A. in Computer Science (summa cum laude) & Mathematics, Cornell University (2018-2021)
* Computer Science & Mathematics, Rutgers University (2017-2018)

Publications & Preprints
======
{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}

Talks
======
{% for post in site.talks reversed %}
  {% include talk.html %}
{% endfor %}

Industry Experience
======
{% for post in site.industry reversed %}
  {% include industry.html %}
{% endfor %}

Teaching
======
{% for post in site.teaching %}
  {% include teaching.html %}
{% endfor %}
