---
layout: page
permalink: /join_us/
title: Join us
nav: true
order: 5
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
 <a href="http://www.bristol.ac.uk/study/postgraduate/2021/eng/phd-eng-maths">Information about
  admission requirements can be found on the University of Bristol's website</a>.
</p>  

<h2 class="category">Engineering Maths students at Bristol</h2>
Each year there are opportunities to join the CFM Lab through the project-based units offered to third-year BEng students (EMAT30009), fourth-year MEng students (EMATM5000), and MSc students (EMATM0038).  Project proposals can be developed
with students and are usually submitted in the summer before TB1.  Please email Matt if you would like
to develop a project together.

<h2 class="category">Summer projects for undergraduate students</h2>

<p> The CFM Lab strongly advocates undergraduate research.  Summer projects
involve working on a current research problem under the supervision of a member
of our lab.  Bristol's Faculty of Engineering provides funding for summer projects.
These projects are usually announced in January.
</p>

<h2 class="category">Post-doctoral researchers</h2>
The CFM Lab does not currently have funding for post-doctoral researchers.  Please check again as vacancies will be posted here.  Below are some links for external funding for post-doctoral researchers:

<ul>
<li><a href="https://ec.europa.eu/research/mariecurieactions/actions/postdoctoral-fellowships">Marie Skłodowska-Curie Individual Fellowships</a> - for researchers currently based outside of the UK.</li>
<li><a href="https://royalcommission1851.org/fellowships/research-fellowships">Royal Commission 1851 Fellowships</a> - for reseachers with less than 3 years of post-doc experience.</li>
<li><a href="https://royalsociety.org/grants-schemes-awards/grants/university-research/">Royal Society University Research Fellowships</a> - for researchers based anywhere.</li>
<li><a href="https://www.ukri.org/councils/epsrc/career-and-skills-development/fellowships/">EPSRC fellowships</a> - for researchers based anywhere.</li>
</ul>
</div>
