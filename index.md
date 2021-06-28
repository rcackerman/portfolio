---
layout: page
full_logo: true
title: 
subtitle: 
description: A minimal yet feature-rich Jekyll theme made for personal websites and blogs.
sitemap:
  priority: 1.0
---

<div class="row justify-content-md-center">
  <div class="col-md-10 intro">
    <p id="describe-text">Hi, I'm Rebecca. I research, design, and build things at the intersection of policy and technology. Here are some of my projects:</p>
  </div>
</div>

<div class="card-columns">
  {% for project in site.data.projects %}
    {% include post/project_card.html %}
  {% endfor %}
</div>
