---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi :wave: I am **{{ site.author.name }}**, a Telematics Engineer living in Málaga (Spain).

I love public transportation and the technologies behind the Internet. I'm constantly learning more about them and exploring how they can be contribute to society.

Curiosity is my driving force and my desire to improve things motivates me. I'm an advocate of free (as in freedom) and pro-democratic technology. I enjoy participating in volunteer work and I have also served as a student representative advocating for a public and high-quality university.

## Traits
<div class="row">
{% include about/tag-skills.liquid source=site.data.tagskills-soft %}
</div>

<div class="row">
{% include about/skills.html title="Programming" source=site.data.programming-skills %}
{% include about/tag-skills.liquid title="Communications" source=site.data.tagskills-comms %}
{% include about/tag-skills.liquid title="Frameworks & Tools" source=site.data.tagskills-platforms %}
</div>

# My timeline

<div class="row">
{% include about/timeline.liquid %}
</div>