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
        {% include figure.html path="assets/img/people/matt.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
      </div>
      <div class="col-sm-9 mt-3 mt-md-0">
        <p>
          <b>Matt Hennessy</b> leads the CFM Lab.  His research interests lie at the interface of applied mathematics, materials science, and soft matter.  He is currently a Lecturer in <a href="http://www.bristol.ac.uk/engineering/departments/engineering-mathematics/">Engineering Mathematics</a> at the <a href="https://www.bristol.ac.uk/">University of Bristol</a>.
        </p>
        <p>
          Matt obtained his DPhil in Applied Mathematics from the <a href="https://www.maths.ox.ac.uk">University of Oxford</a>, where he studied evaporation-driven instabilities in polymer films in the context of organic solar cell fabrication.  He then held a post-doc position in the <a href="https://www.imperial.ac.uk/chemical-engineering">Department of Chemical Engineering at Imperial College London</a>, followed by a Marie Curie-Skłodowska Fellowship at the <a href="http://www.crm.cat">Centre de Recerca Matematica</a> in Barcelona, and then returned to Oxford to take up a Hooke Research Fellowship.
        </p>
      </div>
    </div>
</div>

<!-- current members -->

<div class="projects">
  <h2 class="category">Current members</h2>
    {% for member in sorted_members %}
    {%- if member.category == "current" -%}
      {% include member_format.html %}
    {%- endif -%}
    {% endfor %}
</div>


<!-- affiliate members -->
<div class="projects">
  <h2 class="category">Associate members</h2>
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
