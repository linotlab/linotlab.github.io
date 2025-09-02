---
layout: about
title: About
permalink: /
subtitle: <a href='https://www.umass.edu/engineering/chemical-engineering'>Department of Chemical Engineering</a>. 112F Goessmann Laboratory, 686 N Pleasant St, Amherst, MA 01002. alinot@umass.edu

# profile:
#   align: right
#   image: prof_pic.jpg
#   image_circular: false # crops the image to make it circular
#   more_info: >
#     <p>555 your office number</p>
#     <p>123 your address street</p>
#     <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/misc/Goessmann.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The group is located in Goessmann Hall.
</div>

<p style="text-align: justify;">
Our group develops numerical tools to model, control, and analyze fluids and chaotic dynamical systems. Studying fluids plays an important role in understanding physics across many scales, such as collective motion in bacteria colonies, the drag caused by turbulence over a plane wing, and the large-scale weather patterns present in the Earth's atmosphere. These are all complex, time-varying systems that are highly sensitive to the initial state of the system -- a hallmark of chaos. We study these systems in computational simulations, which allows us to probe physics that are often difficult, or impossible, to access through experiments alone. 
</p>

<p style="text-align: justify;">
Unfortunately, classical computational methods often remain too expensive for forecasting and controlling highly chaotic flows. Thus, a major thrust of our work is to develop machine learning methods for these tasks. We leverage concepts from chaos theory and dynamical systems theory to develop machine learning methods tailored to our problems of interest. This includes considering concepts such as sensitivity to initial conditions, invariant attractive manifolds, exact coherent states, system symmetries, and more. Despite more than a century of research into turbulent flows, it still presents major challenges we hope to address using machine learning.
</p>
