---
layout: page
title: Stability analysis
description: Finding growth mechanisms in unsteady flows.
img: /assets/img/research/StabilitySq.png
importance: 3
category: current
related_publications: true
---

<p style="text-align: justify;">
Most fluid systems are characterized by a steady fixed point solution, which is laminar flow, and a chaotic attractor, which is turbulent flow. In Newtonian flows, upon increasing the Reynolds number a transition from a stable laminar solution to a stable turbulent solution is experimentally observed. Interestingly, in pipe flow this transition happens despite the fact that the laminar solution is linearly stable for all Reynolds numbers. This apparent contradiction is due to the fact that linear stability indicates asymptotic behavior, but not how perturbations evolve over short-times. In fact, when eigenvectors are nonorthogonal then large levels of growth can occur. This nonmodal growth is what causes finite perturbations in pipe flows to grow and eventually trigger turbulence. Understanding this transition is important as it allows us to develop methods to delay (e.g., mitigate drag) or accelerating (e.g., mixing) this transition.
</p>

<p style="text-align: justify;">
For many stationary systems like constant flowrate pipe flow, we know much about the flow stability. Unfortunately, these stability properties can change dramatically for unsteady flows, and these flows are far less studied. Some example include, start-up/shut-down of pipe flow, gust-airfoil encounters, and an accelerating/decelerating vehicle. Our group is interested in studying these unsteady flows, and using insights from these studies for control. Below is an example of a study where we derived analytical solutions for channel flows with arbitrary wall motion and showed how deceleration causes dramatically higher perturbation growth than in an accelerating flow {% cite Stability %}.  
</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/research/UnsteadyStab.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    a) example of a channel flow with arbitrary wall motion. b) analytical solutions for accelerating and decelerating wall motion. c) maximum energy amplification for perturbations to the flows in b).
</div>
