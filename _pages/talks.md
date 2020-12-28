---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

## Slides

As few of my talks so far have actually been recorded (and so far all on one subject), here's some fun slides from some other presentations I've given:

* [Solving Partial Differential Equations (PDEs) with Quantum Computers](http://ievutec.github.io/files/AWE_presentation.pdf) (_12 March, 2020_)
* [Introduction to Quantum Machine Learning](http://ievutec.github.io/files/IGSQT_pres.pdf) (_19 June, 2020_, presented for [IGSQT](https://igsqt.ac.uk/))
* [Variational Counterdiabatic Driving](http://ievutec.github.io/files/CD_Driving.pdf) (_12 November, 2020_, presented in a joint seminar with the University of Waterloo)


