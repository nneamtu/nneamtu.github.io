---
permalink: /
title: "Homepage"
excerpt: "Natalie Neamtu's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first year PhD student in CSE at the University of Washington.
My research interests lie in formal methods and verification for systems.
I am excited about developing new techniques, and applications thereof,
for reasoning about and proving the correctness of systems that bring
formal reasoning closer to widespread use in software development practice.

I graduated in 2021 from Cornell University, where my research on
formal and informal models of distributed consensus protocols was advised
by [Robbert van Renesse](https://www.cs.cornell.edu/home/rvr/). 
After that, I worked on data-centric problems for Bing's knowledge graph,
most recently using LLMs for semi-structured data extraction and unstructured data generation.

### News
* *January 2025*: I am visiting the [Secure Foundations Lab](https://www.andrew.cmu.edu/user/bparno/research.html) 
at Carnegie Mellon University for the spring semester. 
I am working on modular verification of large distributed and concurrent systems in Verus.
* *September 2024*: I quit my job (and, more importantly, started my PhD)!!
* *July 2024*: My team's feature, generative search, was featured on [Bing's blog](https://blogs.bing.com/search/July-2024/generativesearch).
* *August 2023:* I was awarded an [NSF CSGrad4US Graduate Fellowship](https://www.nsf.gov/cise/CSGrad4US/).
* *May 2023:* I presented "Trees and Turtles: Modular Abstractions for State Machine Replication" at [PaPoC 2023](https://papoc-workshop.github.io/2023/) (co-organized with EuroSys) in Rome, Italy.
* *March 2023:* My team's feature, AI-generated short videos for Knowledge Cards, was featured on [Bing's blog](https://blogs.bing.com/search/march_2023/Bing-Preview-Release-Notes-AI-powered-Knowledge-Cards-and-Stories).
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

Publications
======
{% for post in site.publications reversed %}
  {% include publication.html %}
{% endfor %}

Industry Experience
======
{% for post in site.industry reversed %}
  {% include industry.html %}
{% endfor %}

Past Projects
======
{% for post in site.projects reversed %}
  {% include teaching.html %}
{% endfor %}

Teaching
======
{% for post in site.teaching %}
  {% include teaching.html %}
{% endfor %}
