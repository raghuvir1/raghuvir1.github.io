---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hello! I'm  **{{ site.author.name }}**,<br>
a graduate student from the University of Illinois, Urbana-Champaign pursuing a Master's of Science in Information Management (Data Science).

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
