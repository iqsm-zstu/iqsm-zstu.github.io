---
layout: archive
title: People
permalink: /members/
author_profile: true
id: "people"
---

## Faculty

<div class="flex-container people image-container">
{% for person in site.data.faculty %}
  {% include person_image image=person.image caption=person.name link=person.website title=person.name %}
{% endfor %}
</div>
