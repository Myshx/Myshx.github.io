---
layout: page
title: Design Space Exploration for High-Efficiency Building
description: The project focuses on designing an exploration for retrofitting 792 Donald Lee Hollowell Parkway NW, Atlanta, Georgia, USA. The project is located in Climate Zone 3, with an area of 1,680 sqf. The aim is to design exploration for building renovation to understand the tradeoff between occupancy (density), comfort and energy use intensity while balancing operational energy, reducing the overall carbon emission, and maintaining daylight performance (UDI/ASE). Additionally, explore rainwater harvesting potential.
img: assets/img/A.jpg
importance: 1
category: work
related_publications: true
cv_pdf: BSDP1.pdf
---

## Project Information

**Location:** 792 Donald Lee Hollowell Parkway NW, Atlanta, Georgia, USA  
**Climate Zone:** 3  
**Building Area:** 1,680 sq ft

The project focuses on designing an exploration for retrofitting 792 Donald Lee Hollowell Parkway NW, Atlanta, Georgia, USA. The project is located in Climate Zone 3, with an area of 1,680 sqf. The aim is to design exploration for building renovation to understand the tradeoff between occupancy (density), comfort and energy use intensity while balancing operational energy, reducing the overall carbon emission, and maintaining daylight performance (UDI/ASE). Additionally, explore rainwater harvesting potential.

---

Every project has a beautiful feature showcase page.
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
        {% include figure.liquid loading="eager" path="assets/img/design-exploration.gif" title="Design exploration 3D model" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/design-exploration-2.gif" title="Building analysis with occupancy" class="img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/design-exploration-3.gif" title="Daylight performance analysis" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    Design space exploration showing 3D building models with envelope analysis, occupancy density studies, and daylight performance optimization.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded" %}
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
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded" %}
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
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded" %}
  </div>
</div>
```

{% endraw %}
