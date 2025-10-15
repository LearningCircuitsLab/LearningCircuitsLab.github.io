---
layout: homelay
excerpt: "The Learning Circuits Laboratory at the IDIBAPS is studying the neural circuits mediating learning in mice."
sitemap: false
permalink: /
---
<div class="col-sm-12" style="display: flex; justify-content: center; align-items: center;">
<img class="float-left biglogo" src="{{ site.url }}{{ site.baseurl }}/images/mouse_brain_logo.png">
<div class="bigtitle titlebox; !important;">
Learning Circuits Laboratory
</div>
</div>

<div class="col-sm-12">
  <p>
  We are a research group at <a href="https://braincircuitsbehavior.org/">the Brain Circuits and Behavior Lab</a>
  in the <a href="https://www.clinicbarcelona.org/en/idibaps">Instituto de Investigaciones Biomédicas August Pi i Sunyer</a>.
  <br>
  We are interested in understanding the <strong>brain circuits that mediate learned behaviors</strong> in mice. Our main approaches and goals are:
    <ul>
      <li>Use of behavioral paradigms based on audition and smell, and <strong>mathematical modelling</strong> to explain the learning and behavior of the animals.</li>
      <li>Trans-synaptic viral approaches to reconstruct <strong>long-range circuits</strong> between the telencephalon and the midbrain.</li>
      <li>Transcriptomic approaches to characterize the <strong>cell types</strong> in different brain areas.</li>
      <li>Electrophysiology and optogenetics to probe the activity and <strong>function</strong> of specific neurons.</li>
      <li>We aim to <strong>integrate</strong> and combine the above tools to achieve a description of circuits that incorporates the identity of neurons, their connectivity, how their activity gives rises to specific behaviors, and how this changes during learning.</li>
      <li>Our interest extends beyond the mouse, and one of our goals is to compare our findings across species. With distant animals to understand the <strong>evolution</strong> of these circuits, and with humans to understand how these circuits are affected in distinct <strong>neuropathologies</strong>.</li>
    </ul>
  </p>
</div>

<div class="col-12" markdown="1" style="display: flex; justify-content: center; align-items: center;">
  <div class="carousel slide" data-ride="carousel" style="max-width:600px; max-height:400px; !important;">
    <div class="carousel-inner" role="listbox" style="max-width:600px; max-height:400px; !important;">
      {% for image in site.data.gallery %}
      {% assign ext = image.name | split: '.' | last %}
      {% if ext == 'jpg' or ext == 'png' or ext == 'gif' %}
      {% if forloop.index == 1 %}
      <div class="carousel-item active">
      {% else %}
      <div class="carousel-item">
      {% endif %}
        <img class="d-block w-100" src="{{ site.url }}{{ site.baseurl }}/images/carousel/{{ image.name }}" alt="{{ image.alt }}">
      </div>
      {% endif %}
      {% endfor %}
    </div>
  </div>
</div>


<p></p>
<br>
<br>

<strong>Our research is supported by:</strong>
<br>
<img class="float-left" src="{{ site.url }}{{ site.baseurl }}/images/AEI_logo.png" style="max-width:250px; max-height:200px; margin-right:20px; margin-top:10px;">