---
layout: page
title: Public Transit + DRL
description: Real-time Online Task Assignment for Tram Motorman with Deep Reinforcement Learning @PolyU, Hong Kong
img: assets/img/project_preview/tram_drl.jpg
category: In Progress
importance: 1
related_publications:
header-background-img:
---

<div style="text-align: justify;">
In modern cities, some public transit systems, e.g. trams and buses, face some uncertainties in their operation, such as disruption and bunching. This leads to inefficient service to the public and seriously affects the working hours and welfare of motormen. Thus, how to develop a flexible, robust, and efficient real-time online task assignment scheme according to such complex system dynamics for motormen become the core of this project.
</div>
<br>
<div class="row">
    <div class="col-sm-3 mt-md-0"></div>
    <div class="col-sm-6 mt-md-0" style="text-align: center;">
        <div style="width: 50%; margin: auto;">
            {% include figure.liquid loading="eager" path="assets/img/project_preview/tram_drl_buses_bunching_HK.jpg" title="Buses bunching" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="col-sm-3 mt-md-0"></div>
</div>
<div class="caption">
    An example of buses bunching in Hong Kong. (Source: 4TU.ResearchData)
</div>

**Objectives:**

- Create a simulator that will allow to test the performance of operational strategies and easily extend to other public transit systems.
- Develop a Deep Reinforcement Learning (DRL) based agent to generate tasks to motormen.
- Explore a learning-based approach to alleviate or circumvent the high computational complexity of traditional optimization techniques.

**Preview:**

- With a developed DRL-based agent, the experiments show that the agent can have all the motormen take meal breaks and sign off while maintaining a low under-coverage rate on one operational day.
<div class="row">
    <div class="col-sm-2 mt-md-0"></div>
    <div class="col-sm-8 mt-md-0" style="text-align: center;">
        <div style="margin: auto;">
            {% include figure.liquid loading="eager" path="assets/img/project_preview/tram_drl_exps.jpg" title="exps" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="col-sm-2 mt-md-0"></div>
</div>

**Reference:**

- David SW Lai and Janny MY Leung. Real-time rescheduling and disruption management for public transit. _Transportmetrica B: Transport Dynamics_, 6(1):17–33, 2018.
