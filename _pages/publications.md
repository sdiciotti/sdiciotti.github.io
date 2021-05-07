---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

You can find my publications on the following systems.

<a href="{{ site.author.arxiv }}"><i class="ai ai-fw ai-arxiv"></i> arXiv</a>   
<a href="{{ site.author.googlescholar }}"><i class="ai ai-fw ai-google-scholar"></i> Google Scholar</a>     
<a href="{{ site.author.orcid }}"><i class="ai ai-fw ai-orcid"></i> ORCID</a>   
<a href="{{ site.author.researchgate }}"><i class="ai ai-fw ai-researchgate"></i> ResearchGate</a>         

You can download my [own bibtex file](https://sdiciotti.github.io/files/sdiciotti.bib) which serves to generate the list below (which might take a few seconds to appear depending on your connection).

<script src="https://bibbase.org/show?bib=https://sdiciotti.github.io/files/sdiciotti.bib&jsonp=1&nocache=1&theme=default"></script> 

{% include base_path %}

<!-- {% capture written_year %}'None'{% endcapture %}
{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->

