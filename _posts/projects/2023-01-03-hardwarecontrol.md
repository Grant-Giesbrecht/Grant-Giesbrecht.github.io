---
layout: page-fullwidth
title:  "An Instrument Automation Package written in Python"
teaser: "Research Project"
categories:
    - projects
header:
   title: Hardware Control
   background-color: "#EFC94C;"
   image_fullwidth: "header_homepage_13.jpg"
---

My work at Lawrence Berkeley National Lab was centered around developing a compact
and affordable type of linear accelerator (linac) called a [MEQALAC](http://Grant-Giesbrecht.github.io/projects/meqalac/). Our accelerator
was part of a test stand which relied upon many different types of lab instruments 
to run the linac and collect data. This system originally used NI LabView to synchronize
everything, however this became increasingly impractical to extend as new instruments
and new functionality needed to be incorporated. Our team wasn't satisfied with
any of the instrument automation tools available at the time, so we decided to 
create our own Python package which we could use to simplify our test stand and 
extend to future projects.

The result was the <i>hardware_control</i>. Designed to provide reusable user interfaces
and Python-based instrument drivers, control programs can be written as simply as connecting
the your instrument's driver to a UI. For example, if you had a Keysight 4000 series oscilloscope 
you wished to use for data collection, you'd connect the Keysight 4000 series Python driver
to the generic oscilloscope UI, all provided by <i>Hardware Control</i>.

This project resulted in a completely new software system for our experiment which allowed us to collect data faster and more reliably, while also integrating the data collection process with our data analysis workflow. The project resulted in a [publication](https://joss.theoj.org/papers/10.21105/joss.02688) in the Journal of Open Source Software, an academic journal designed to improve the quality of published software through peer review. It was also a very personally satisfying project to work on. Not only my first opportunity to professionally develop software full time in Python, but I have been able to use it personally at home; to this day, I still use <i>Hardware Control</i> to automate processes on my home lab bench!

If you'd like to give <i>Hardware Control</i> a try, you can get started by checking out its [documentation](https://hardware-control.readthedocs.io/en/latest/index.html), or jump right in by installing it through [pip](https://hardware-control.readthedocs.io/en/latest/installation.html).

<div class="row">
    <div class="medium-8 columns t30">
    <img src="{{ site.urlimg }}gallery-example-7.jpg" alt="">
    </div><!-- /.medium-8.columns -->

    <div class="medium-4 columns t30">
      <img src="{{ site.urlimg }}gallery-example-3.jpg" alt="">
      <img class="t30" src="{{ site.urlimg }}gallery-example-8.jpg" alt="">
    </div><!-- /.medium-4.columns -->

</div><!-- /.row -->
