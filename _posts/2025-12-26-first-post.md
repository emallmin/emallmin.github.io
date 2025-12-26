---
layout: post
title: "First review: Lagavulin 16"
review_id: lagavulin16
---

{% assign whisky = site.data.reviews[page.review_id] %}

<h2>{{ whisky.name }}</h2>

<ul>
  <li>Age: {{ whisky.age }}</li>
  <li>Region: {{ whisky.region }}</li>
  <li>Grade: {{ whisky.grade }}</li>
</ul>

<h3>Tasting notes</h3>
<ul>
{% for note in whisky.tasting_notes %}
  <li>{{ note }}</li>
{% endfor %}
</ul>
