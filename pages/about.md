---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:, Telematics Engineering student about to finish the Degree.

I have been able to complete my learning with self-study and occasional freelance work. I have also participated in student representation and volunteering, which have given me soft skills and great versatility.

<!--
<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>
-->

<div class="row">
{% include about/tag-skills.liquid title="Soft skills" source=site.data.tagskills-soft %}
</div>

<div class="row">
{% include about/tag-skills.liquid title="Communications" source=site.data.tagskills-comms %}
{% include about/tag-skills.liquid title="Platforms" source=site.data.tagskills-platforms %}
</div>

# My timeline

<div class="row">
{% include about/timeline.html %}
</div>