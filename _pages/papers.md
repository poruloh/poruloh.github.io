---
title: "Loh Lab - Papers"
layout: gridlay
excerpt: "Papers"
sitemap: false
permalink: /papers/
---

## Selected Preprints

<ul>
{% for publi in site.data.publist %}
{% if publi.type == 2 %}
<li>
{{ publi.authors }}. <a href="{{ publi.url }}">{{ publi.title }}</a>. <i>{{ publi.journal }}</i> ({{ publi.year }}).
</li>
{% endif %}
{% endfor %}
</ul>

## Selected Publications

<ul>
{% for publi in site.data.publist %}
{% if publi.type == 1 %}
<li>
{{ publi.authors }}. <a href="{{ publi.url }}">{{ publi.title }}</a>. <i>{{ publi.journal }}</i> ({{ publi.year }}).
</li>
{% endif %}
{% endfor %}
</ul>

For a full list of publications, see [Google Scholar](https://scholar.google.com/citations?user=yZbch0cAAAAJ) or [NIH/NCBI My Bibliography](https://www.ncbi.nlm.nih.gov/myncbi/14CfxHHXiq5Q7/bibliography/public).

PDFs of publications through 2023 are available from our [old lab website](https://statgen.bwh.harvard.edu/papers/highlights).
