---
title: "Moses Stewart"
layout: homelay
classes: wide
sitemap: false
permalink: /
---

### About Me

<br>

I am a second-year graduate student at Harvard University living in Cambridge, Massachusetts. I currently work as a research assistant for [Rahul Singh](https://www.economics.harvard.edu/people/rahul-singh).  I graduated Harvard University in Fall of 2025, with a concentration in Honors Statistics.

From 2022-2024, I spent two years working closely with [Jesse Shapiro](https://scholar.harvard.edu/shapiro/home) and [Isaiah Andrews](https://economics.mit.edu/people/faculty/isaiah-andrews) as a research assistent.

**Research interests:** My undergraduate research focused on causal inference under misspecified models in Economics. Currently my research is centered around nonparametric causal inference and identification. I hope to continue this theme in the near future.

**Contact me:** mosesstewart \[at\] g \[dot\] harvard \[dot\] edu

<br/>

### Work Experiences

<div class='jumbotron'>
{% for member in site.data.work %}
<ul>
    <li>
      {{ member.role }} at <b>{{ member.company }}</b> ({{ member.yearStart }} - {{ member.yearEnd }})
    </li>
</ul>
{% endfor %}
</div>

<br/>

### Working Papers

<div class="jumbotron">
{% bibliography --query @inproceedings %}
</div>


<br/>

