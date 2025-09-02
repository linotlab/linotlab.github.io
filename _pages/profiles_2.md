---
layout: page
permalink: /people/
title: Group
description: 
# members of the lab or group
nav: true
nav_order: 2
---

## Principal Investigator

<div class="post">
  <article>
        <hr>
        <div class="profile float-right">
            {% assign profile_image_path = 'people/Alec_Square.jpg' | prepend: 'assets/img/' %}
            {% assign profile_image_class = 'img-fluid z-depth-1' %}
            {% capture sizes %}(min-width: {{ site.max_width }}) {{ site.max_width | minus: 30 | times: 0.3}}px, (min-width: 576px) 30vw, 95vw"{% endcapture %}
            {% include figure.liquid loading="eager" path=profile_image_path class=profile_image_class sizes=sizes alt="" %}
            <div class="more-info">alinot[at]umass.edu<br>Goessmann Laboratory 112F<br><a href="https://scholar.google.com/citations?user=Mw3YwtAAAAAJ&hl=en">Google Scholar</a></div>
        </div>

        <div class="clearfix">
            {% capture profile_content %}{% include_relative _profiles/about_alec.md %}{% endcapture %}
            {{ profile_content | markdownify }}
        </div>
  </article>
</div>

{% comment %}
## Graduate Students

<div class="post">
  <article>
        <hr>
        <div class="profile float-left">
            {% assign profile_image_path = 'misc/UMassSeal.png' | prepend: 'assets/img/' %}
            {% assign profile_image_class = 'img-fluid z-depth-1' %}
            {% capture sizes %}(min-width: {{ site.max_width }}) {{ site.max_width | minus: 30 | times: 0.3}}px, (min-width: 576px) 30vw, 95vw"{% endcapture %}
            {% include figure.liquid loading="eager" path=profile_image_path class=profile_image_class sizes=sizes alt="" %}
            <div class="more-info">alinot[at]umass.edu<br>Goessmann Laboratory 112F<br><a href="https://scholar.google.com/citations?user=Mw3YwtAAAAAJ&hl=en">Google Scholar</a></div>
        </div>

        <div class="clearfix">
            {% capture profile_content %}{% include_relative _profiles/about_alec.md %}{% endcapture %}
            {{ profile_content | markdownify }}
        </div>
  </article>
</div>
{% endcomment %}
