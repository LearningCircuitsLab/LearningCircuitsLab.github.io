---
layout: homelay
excerpt: "The Learning Circuits Laboratory at the IDIBAPS is studying the neural circuits mediating learning in mice."
sitemap: false
permalink: /
---
<div class="col-sm-12" style="text-align: center !important;">
<img class="float-left biglogo mx-auto d-block" src="{{ site.url }}{{ site.baseurl }}/images/mouse_brain_logo.png">
<div class="bigtitle titlebox">
Learning Circuits Laboratory
</div>
</div>

<div class="col-sm-12">
  <p>
  We are a research group at <a href="https://braincircuitsbehavior.org/">the Brain Circuits and Behavior Lab</a>
  in the <a href="https://www.clinicbarcelona.org/en/idibaps">Instituto de Investigaciones Biomédicas August Pi i Sunyer</a>.
  <br>
  We are interested in understanding the brain circuits that mediate learned behaviors in mice. Our main approaches and goals are:
    <ul>
      <li>Use of behavioral paradigms based on audition and smell, and mathematical modelling to explain the learning and behavior of the animals.</li>
      <li>Trans-synaptic viral approaches to reconstruct long-range circuits between the telencephalon and the midbrain.</li>
      <li>Transcriptomic approaches to characterize the cell types in different brain areas.</li>
      <li>Electrophysiology and optogenetics to probe the activity and function of specific neurons.</li>
      <li>We aim to integrate and combine the above tools to achieve a description of circuits that incorporates the identity of neurons, their connectivity, how their activity gives rises to specific behaviors, and how this changes during learning.</li>
      <li>Our interest extends beyond the mouse, and one of our goals is to compare our findings across species. With distant animals to understand the evolution of these circuits, and with humans to understand how these circuits are affected in distinct neuropathologies.</li>
    </ul>
  </p>
</div>

<div class="col-12" markdown="1" style="margin: auto; width: 75%;">
<div class="carousel slide" data-ride="carousel">
  <div class="carousel-inner" role="listbox" style="max-width:600px; max-height:400px;">
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
