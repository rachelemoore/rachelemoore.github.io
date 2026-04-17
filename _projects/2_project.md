---
layout: page
title: Understanding the biology of axon initiation _in vivo_
description: a project with a background image and giscus comments
img: assets/img/3.jpg
importance: 1
category: work
related_publications: true
---

Neurons connect to their targets, such as muscles or other neurons, via long thin processes called axons. During embryonic develompent, newborn neurons extend a specific number of axons from specific positions on the cell body. This is essential for the subsequent formation of connectivity, enabling a functioning nervous system. However, we don't understand how axon initiation is controlled and how this mechanism is maintained in nerve regeneration. Adult mammalian neurons are unable to grow new axons after they are damaged by injury or disease, even when the cell body remains healthy.

Our current understanding of axon initiation is mostly based on experiments where neurons are cultured in a dish. This is very different to their normal environment in the nervous system, and it's hard to know which findings are relevant. There are some methods of investigating axon initiation in the neurons' normal environment, but it is generally very difficult to observe. Further, in all of our current models (neurons in a dish or in an embryo), neurons extend other types of processes first, with one of those later turning into an axon. This makes it difficult to figure out exactly when the axon is "born".

To address these problems, I have established the zebrafish embryonic spinal cord as a model. Zebrafish embryos are transparent so it is very easy to see living neurons developing within their normal environment. Neurons in the zebrafish spinal cord extend axons directly from the cell body, so I can see exactly when axon initiation occurs. They extend either one or (rarely) three axons at a very stereotyped position on the cell body. This allows me to describe how axon number and axon positioning are controlled in time and space and identify precisely what is driving this process. 

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

{% endraw %}
