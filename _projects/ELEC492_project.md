---
layout: page
title: Implementing a Hybrid DES-RL System to Improve Machine Learning Interpretability
description: A research project applying Discrete-Event Systems and Reinforcement Learning to a multi-agent autonomous search-and-rescue problem.
img: assets/img/12.jpg
importance: 1
category: academic
related_publications: true
---

#### Overview
This project explores the integration of Discrete Event Systems (DES) with Reinforcement Learning (RL) to enhance the interpretability of machine learning models. Traditional RL methods can be powerful, but often result in models that lack transparency, known as the "black box" problem. Meanwhile, DES provides a high-level, visual formalism for control and navigation, but lacks flexibility and the ability to learn from data and experiences.
By combining the formal logic and structure of DES, with the adaptive capabilities of RL, we create a framework to understand _how_ complex RL methods arrive at their decisions.

#### Key Concepts
- **Discrete Event Systems (DES):** Provide a mathematical framework for modelling and controlling event-driven systems. They offer a well-defined structure for representing complex system behaviour.
- **Reinforcement Learning (RL):** A subfield of machine learning where agents learn through experience and interaction with an environment to maximize rewards.
- **Mutual Learning:** Enables cooperative learning among multiple agents, allowing for more efficient exploration and decision-making, especially in partially observable environments.

#### Methodology
1. **Hybrid DES-RL Model:** Develop a model that combines the strengths of DES (interpretability) and RL (learning capabilities). This model might involve:
    - Representing the RL environment and agent actions as a DES automaton
    - Incorporating reward mechanisms into the DES framework
    - Using DES concepts like controllability and observability to guide RL decision-making
2. **Mutual Learning:** Implement a mutual learning approach to enable cooperative learning among multiple RL agents with limited information sharing. This could improve exploration efficiency and model performance in complex environments.

#### Significance
- **Improved Interpretability:** The hybrid model offers insights into the underlying decision-making process of RL agents, enhancing understanding and trust in their outputs.
- **Mutual Learning Efficiency:** Mutual learning fosters collaboration between agents, leading to better exploration strategies and more robust RL solutions.
- **Potential Applications:** This work has applications in fields where explainable AI is critical, such as:
    - Autonomous vehicles
    - Healthcare decision-making
    - Financial systems

#### Next Steps
- Experiment with different DES-RL model architectures.
- Evaluate the proposed system in a complex multiagent search problem.
- Conduct rigorous testing and validation to ensure model interpretability and performance.


<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %} -->