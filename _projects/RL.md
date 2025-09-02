---
layout: page
title: Control of Chaos
description: Reinforcement learning, model predictive control, and more.
img: /assets/img/research/RLSq.png
importance: 1
category: current
related_publications: true
---

<p style="text-align: justify;">
Active, closed-loop flow control is a category of flow control methods that involves energy input (active) and a method of changing the actuation based on measurements of the system (closed-loop). This style of flow control is appealing because it can offer greater control authority over passive and open-loop methods. Modern experimental tools provide methods for observing the state of the system and for rapidly reacting to changes in the state (e.g., Micro-Electro-Mechanical Systems). However, a major challenge lies in determining the optimal actuation policy. As such, we work on developing computational methods for discovering active flow-control strategies.
</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/research/MFU_Control.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example of turbulent flow control. The top panel shows drag (red) and the wall normal velocity of the left jet (black). The right jet actuations in the opposite direction. The lower panels show snapshots of the flow with isosurfaces of the streamwise velocity. This highlights the location of low-speed streaks. Here, the RL agent finds a method to laminarize the flow by generating two low-speed streaks. This temporarily increases drag, but disrupts the natural streak spacing, which leads to laminarization.
</div>

<p style="text-align: justify;">
Two methods for finding control algorithms are reinforcement learning (RL) and model predictive control (MPC). We use methods like these to discover close-loop control algorithms in high-resolution simulations -- the results of which could be applied to physical systems. Those in controls often refer to these simulations as surrogate models. In RL, a neural network agent repeatedly interacts with this surrogate model to find a policy that maximizes a reward. In MPC, a set of actions are chosen, then the surrogate model is evolved forward and an adjoint model is evolved backwards to compute the gradient of a reward with respect to this set of actions. This gradient is then used to select a new set of actions. 
</p>

<p style="text-align: justify;">
Applying these types of approaches for tasks such as drag reduction remains a major challenge due to the high computational cost of forecasting, the ambiguity in selecting flow actuators, and the high sensitivity of fluid systems. Thus, a major thrust of our research involves developing fast algorithms for discovering active flow-control strategies. For example, we have found that we can couple low-dimensional models with RL and MPC to minimize drag in turbulent channels using fluid jets {% cite NODERLCouette %}. 
</p>