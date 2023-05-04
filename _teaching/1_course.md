---
layout: page
title: Correspondence between cities and kings
description: BA-1/2 Source Reading Course
pdf: korrespondenz_semesterplan.pdf
importance: 1
category: Heidelberg
---

<a href="{{ page.pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fas fa-file-pdf">Semesterplan/Syllabus</i></a>

In the Summer Semester 2022 I taught a source reading course (<i>Quellenübung</i>) at the Seminar für Alte Geschichte und Epigraphik, Heidelberg. 

## Description

> Die Korrespondenz zwischen hellenistischen Königen und griechischen Städten stellt ein fruchtbares Quellenkorpus dar, das Historiker:innen ermöglicht, den Informationsfluss, die politische Verhandlungen und die städtische Institutionen in dieser chaotischen Zeit zu verstehen. Die königlichen Briefe weisen einen selbstbewussten und performativen Stil auf und bieten Raum für textliche und materielle Interaktionen. Sie werden zum einen an den Königshöfen geschrieben, archiviert und überliefert, zum anderen im öffentlichen Raum der griechischen Städte gelesen und zur Schau gestellt als Repräsentation der königlichen Macht und der Verbindung zwischen Städen und Königen. Im Rahmen dieser Übung sollen die Quellen entweder in deutscher oder englischer Übersetzung vorgestellt werden. Wir werden an dem archäologisch-materiellen Kontext der Korrespondenz arbeiten.

## Reflection

History is a science of contexts.
As a reading course for first year BA students, reading epigraphic sources can be particularly difficult, as they lack the information of context.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your course before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your course, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
