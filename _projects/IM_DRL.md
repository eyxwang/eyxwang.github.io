---
layout: page
title: Inventory Management + DRL
description: Deep Reinforcement Learning for Inventory Management under Uncertain Environment @PolyU, Hong Kong
img: assets/img/project_preview/im_drl.jpg
category: In Progress
importance: 2
related_publications:
header-background-img:
---

<div style="text-align: justify;">
Inventory management is a challenging problem that involves making a sequence of optimal decisions under uncertainty. Traditional methods often rely on heuristics or simplifying assumptions that may not capture the complexity and dynamics of real-world scenarios. Motivated by developing an automatic decision-making policy without over-reliance on developing special heuristics tailored to specific conditions, we investigate a framework in which Deep reinforcement learning (DRL) is applied to automatically search, feedback, and update, obtain the optimal policy for inventory management problems. DRL is a powerful technique that can learn from trial and error to handle high-dimensional, nonlinear, and stochastic problems. First of all, to enhance the decision-making effectiveness to obtain long-term returns under stochastic demand environments, we explore how an agent can learn efficiently from historical information to infer the replenishment policy. Second, we will discuss how an effective deep learning model is designed to optimize the inventory policy that can discover the latent pattern in a stochastic demand environment and respond in advance. Finally, we are extending our proposed model to more complex inventory management problems of censored demand, random supply, etc.
</div>
<br>
<div class="row">
    <div class="col-sm-1 mt-md-0"></div>
    <div class="col-sm-10 mt-md-0" style="text-align: center;">
        <div style="width: 90%; margin: auto;">
            {% include figure.liquid loading="eager" path="assets/img/project_preview/im_problem.jpg" title="im_problem" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="col-sm-1 mt-md-0"></div>
</div>

**Process:**
- A technical report was submitted to PolyU and we are conducting the next experiments.
- We presented our initial exploration of simple inventory problems with lost sales and random uncensored demand in [the 2nd ORSHK Young Researchers Workshop](https://www.hksts.org/Workshop2023.pdf) on 9 Dec 2023, <*[SLIDES](../../assets/pdf/projects_pdf/ORSHK2023_yxwang.pdf)*>.

**References:**

- Boute, R. N., Gijsbrechts, J., Van Jaarsveld, W., & Vanvuchelen, N. (2022). Deep reinforcement learning for inventory control: A roadmap. *European Journal of Operational Research*, 298(2), 401-412.
- Chen, B., Jiang, J., Zhang, J., & Zhou, Z. (2024). Learning to order for inventory systems with lost sales and uncertain supplies. *Management Science*.
- Bu, J., Gong, X., & Yao, D. (2020). Constant-order policies for lost-sales inventory models with random supply functions: Asymptotics and heuristic. *Operations Research*, 68(4), 1063-1073.
- Snyder, L. V., & Shen, Z. J. M. (2019). *Fundamentals of supply chain theory*. John Wiley & Sons.

