---
layout: homelay
excerpt: "The Learning Circuits Laboratory at the IDIBAPS is studying the neural circuits mediating learning in mice."
sitemap: false
permalink: /
---
<div class="col-sm-12">
<img class="float-left biglogo" src="{{ site.url }}{{ site.baseurl }}/images/mouse_brain_logo.png">
<div class="bigtitle titlebox">
Learning Circuits Laboratory
</div>
</div>

<div class="col-sm-12">
  <p>
  We are a research group at <a href="https://braincircuitsbehavior.org/">the Brain Circuits and Behavior Lab</a>
  in the <a href="https://www.clinicbarcelona.org/en/idibaps">Instituto de Investigaciones Biomédicas August Pi i Sunyer</a>.
  </b>
  We are interested in the brain circuits that mediate learned behaviors.
  </p>
</div>

<div class="col-12" markdown="1">
<div class="carousel slide" data-ride="carousel">
  <div class="carousel-inner" role="listbox" style="max-width:600px; max-height:400px !important;">
    {% for image in site.data.gallery %}
    {% if forloop.index == 1 %}
    <div class="carousel-item active">
    {% else %}
    <div class="carousel-item">
    {% endif %}
      <img class="d-block w-100" src="{{ site.url }}{{ site.baseurl }}/images/carousel/{{ image.name }}" alt="{{ image.alt }}">
    </div>
    {% endfor %}
  </div>
</div>

# More stuff here

<p></p>
</div>
