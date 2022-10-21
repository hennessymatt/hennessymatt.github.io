---
layout: page
title: People
description: Meet the members of the CFM Lab.
permalink: /group/
nav: true
order: 2
---

{% assign sorted_members = site.group_members | sort: 'date' | reverse %}

<!-- PI  -->

<div class="projects">
  <h2 class="category">Principal investigator</h2>
    <div class="row justify-content-sm-center">
      <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/people/matt2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
      </div>
      <div class="col-sm-9 mt-3 mt-md-0">
        <p>
          <b>Matt Hennessy</b> leads the CFM Lab.  His research interests lie at the interface of applied mathematics, materials science, and soft matter.  He has been a Lecturer in <a href="http://www.bristol.ac.uk/engineering/departments/engineering-mathematics/">Engineering Mathematics</a> at the <a href="https://www.bristol.ac.uk/">University of Bristol</a> since 2021.
        </p>
           <!-- Previously, Matt was a: -->
          <!-- <ul>
            <li>Hooke Research Fellow, University of Oxford, UK (2018-2021)</li>
            <li>Marie Curie-Skłodowska Fellow, <a href="http://www.crm.cat">CRM</a>, Spain (2016-2018)</li>
            <li>PDRA, Imperial College London, UK (2014-2014)</li>
          </ul>
          His education is
          <ul>
            <li>2010 - 2014: DPhil in Mathematics, University of Oxford, UK</li>
            <li>2009 - 2010: MSc in Mathematical Modelling and Scientific Computing, University of Oxford, UK</li>
            <li>2004 - 2009: BSc (hons) in Physics and Applied Mathematics, Ontario Tech University, Canada</li>
          </ul>
        </p> -->
        <p>
          Matt obtained a BSc in Physics and Applied Mathematics from <a href="https://ontariotechu.ca/">Ontario Tech University</a>.  He then completed an MSc in Mathematical Modelling and Scientific Computing and a DPhil in Applied Mathematics at the <a href="https://www.maths.ox.ac.uk">University of Oxford</a>.  He then held a post-doc position in the <a href="https://www.imperial.ac.uk/chemical-engineering">Department of Chemical Engineering at Imperial College London</a>, followed by a Marie Curie-Skłodowska Fellowship at the <a href="http://www.crm.cat">Centre de Recerca Matematica</a> in Barcelona, and then returned to Oxford to take up a Hooke Research Fellowship.
        </p>
      </div>
    </div>
</div>

<!-- current members -->

<div class="projects">
  <h2 class="category">Members</h2>
    {% for member in sorted_members %}
    {%- if member.category == "current" -%}
      {% include member_format.html %}
    {%- endif -%}
    {% endfor %}
</div>


<!-- affiliate members -->
<div class="projects">
  <h2 class="category">Collaborators</h2>
    {% for member in sorted_members %}
    {%- if member.category == "associate" -%}
      {% include member_format.html %}
    {%- endif -%}
    {% endfor %}
</div>


<!-- past members -->

<div class="projects">
  <h2 class="category">Past members</h2>
    {% for member in sorted_members %}
    {%- if member.category == "past" -%}
      <p>
        <b>{{member.name}}</b> - {{member.description}}.  
      </p>
    {%- endif -%}
    {% endfor %}
</div>

---
