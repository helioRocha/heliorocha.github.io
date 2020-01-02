---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

[//]: # ( Hi I am **{{ site.author.name }}** :wave:,<br>)
[//]: # ({% include about/timeline.html title="Other Achievements" source=site.data.other-timeline %})

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html title="Academic" source=site.data.academic-timeline %}
</div>
