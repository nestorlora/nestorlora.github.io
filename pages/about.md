---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:, a Telematics Engineer living in Málaga (Spain).

I love public transportation and the technologies behind the Internet. I'm constantly learning more about them and exploring how they can be leveraged to make an even greater positive impact on society.

## Soft skills
I have been able to complete my learning with self-study and occasional freelance work. I have also participated in student representation and volunteering, which have given me soft skills and great versatility.

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