---
title: "Loh Lab - Team"
layout: gridlay
excerpt: "Team"
sitemap: false
permalink: /team/
---

## Group Members

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<br/>


## Openings

We will have open positions in 2027 for postdocs and students with very strong computational or statistical background and previous research experience in genetics or genomics. Potential research areas include analyses of somatic mutations as part of the [SMaHT Network](https://smaht.org) and analyses of emerging data modalities in biobank data sets. Please send your CV and a brief statement of your research interests to poruloh@broadinstitute.org if interested.

(Please note that we do not have positions available for summer interns or for students who have not already been admitted to a Boston-area PhD program; due to email volume, these queries will not receive responses.)


## Past Members

* [Nolan Kamitaki](https://nkamitaki.github.io) (HMS BIG PhD student, 2022-2026) &#8594; Postdoc with [Steve McCarroll](https://mccarrolllab.org), HMS
* [Simone Rubinacci](https://compstatgenlab.github.io) (Postdoc, 2023-2024) &#8594; Group Leader, FIMM
* [Margaux Hujoel](https://mhujoel.github.io) (Postdoc, 2020-2025) &#8594; Assistant Professor, UCLA
* [Ronen Mukamel](https://www.linkedin.com/in/ronen-mukamel-b9926659) (Instructor, 2019-2024) &#8594; Staff Bioinformatics Scientist, Illumina
* [Alison Barton](https://www.linkedin.com/in/alison-barton) (HMS BIG PhD student, 2018-2022) &#8594; Postdoc with [David Reich](https://reich.hms.harvard.edu), HMS
* [Max Sherman](https://www.linkedin.com/in/maxwellsh) (MIT EECS PhD student, 2018-2022) &#8594; Co-Founder & CTO, Serinus Biosciences


## Lab photos

Lab hike at Mount Monadnock, Oct 2023
<div style="text-align: center;">
  <img src="/images/lab_hike_2023-10-03_web.jpg" width="80%"/>
</div>

Lab photo, Sep 2021
<div style="text-align: center;">
  <img src="/images/lab_photo_2021-09-10_web.jpg" width="80%"/>
</div>
