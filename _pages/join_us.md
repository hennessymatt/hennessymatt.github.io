---
layout: page
permalink: /join_us/
title: Join us
nav: true
nav_order: 5
---

There are several opportunities to join the CFM Lab.  If any of the
opportunities below are of interest to you, then please email Matt at
 <a href = "mailto:matthew.hennessy@bristol.ac.uk">matthew.hennessy@bristol.ac.uk</a>
 to discuss further.


<div class="projects">

<h2 class="category">PhD opportunities</h2>
<p>
We are looking for enthusiastic students to work on PhD projects.
Applicants should have a keen interest in fluid and solid mechanics, numerical
simulations, and using mathematical techniques to solve real-world problems.
There may be opportunities to carry out experimental work as well.
</p>
<p>
We currently have PhD projects relating to (click link for a description):
<div class="projects">
{%- assign sorted_projects = site.phd_projects | sort: "importance" %}
<ul>
{% for project in sorted_projects %}
<li><a href="{{ project.url | relative_url }}">{{ project.title }}</a></li>
{% endfor %}
</ul>
</div>
<!-- <ul>
<li>The solid mechanics of drying colloidal fluids</li>
<li>Mathematical modelling of hydrogel-based drug-delivery systems</li>
<li>Instabilities and pattern formation in hydrogels and electro-active gels</li>
</ul> -->

Competitive funding is available for these PhD projects.
 <a href="https://www.bristol.ac.uk/study/postgraduate/research/engineering-mathematics/">Information about
  admission requirements can be found on the University of Bristol's website</a>.
</p>  
</div>


<div class="projects">
<h2 class="category">Post-doc opportunities</h2>
</div>
The CFM Lab does not currently have funding for post-doctoral researchers.  Please check again as vacancies will be posted here.  Below are some links for external funding for post-doctoral researchers:
* [Marie Skłodowska-Curie Individual Fellowships](https://ec.europa.eu/research/mariecurieactions/actions/postdoctoral-fellowships) - for researchers currently based outside of the UK
* [Royal Commission 1851 Fellowships](https://royalcommission1851.org/fellowships/research-fellowships) - for reseachers with less than 3 years of post-doc experience
* [Royal Society University Research Fellowships](https://royalsociety.org/grants-schemes-awards/grants/university-research/) - for researchers based anywhere
* [EPSRC fellowships](https://www.ukri.org/councils/epsrc/career-and-skills-development/fellowships/) - for researchers based anywhere