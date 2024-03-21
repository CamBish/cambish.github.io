---
layout: page
title: An Interpretable Machine Learning Approach to Sway-Metric Based Fall-Risk Assessment
description: This project investigates the use of interpretable machine learning models to improve fall-risk assessment for seniors using more accessible technologies.
img: assets/img/7.jpg
importance: 3
category: academic
---

#### Overview
This project explores the application of interpretable machine learning (ML) models to analyze sway metrics derived from markerless motion capture data. The goal is to develop an accessible and understandable tool to aid in fall-risk assessment, addressing challenges posed by traditional methods.
#### Key Concepts
- **Sway Metrics:** Quantitative measures of balance and stability derived from motion capture data.
- **Interpretable Machine Learning:** ML models designed to explain their decision-making processes.
- **Fall-Risk Assessment:** The process of identifying individuals at higher risk of injurious falls, particularly relevant for seniors.
#### Methodology
1. **Dataset:** Utilize the KINECAL dataset, containing sway metrics and clinical movement data.
2. **Preprocessing:** Address missing values, normalize data, and consider dimensionality reduction (e.g., PCA).
3. **Model Development:** Employ interpretable ML models (e.g., XGBoost, SVMs, Perceptron) for fall-risk classification.
4. **Evaluation:** Assess performance using metrics like accuracy, F1-score, and ROC AUC, while carefully addressing class imbalance.
#### Results
- **Importance of Data Labelling:** Initial experiments revealed that the dataset's original labelling scheme is not ideal for direct fall-risk prediction.
- **Model Selection:** Simpler models like Perceptron outperformed complex ones, likely due to the limited dataset size and potential overfitting issues.
- **Preprocessing Impacts:** Optimal classifier performance was achieved when normalizing data before concatenation
#### Significance
- **Enhanced Interpretability:** Provides insights into how ML models arrive at fall-risk predictions.
- **Accessibility:** Leverages sway metrics derived from cost-effective markerless motion capture.
- **Future Directions:** Potential for integration with more complex deep learning models for enhanced capabilities.
#### Next Steps
- **Address Dataset Limitations:** Explore methods to mitigate class imbalance and increase the overall sample size.
- **Feature Extraction and Integration:** Use the developed sway-metric analysis as a feature extraction step for more complex deep learning models operating on time-series skeleton data.
- **Clinical Validation:** Collaborate with healthcare professionals to validate the model's performance and potential for real-world application.
#### Repository
The code for this project is open-sourced under a MIT License. You can find the repository [here](https://github.com/CamBish/KINECAL-Fall-Risk-Assessment/tree/main).
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

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
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