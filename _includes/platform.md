<h2 id="publications" style="margin: 2px 0px -15px;">Research Platform</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.platform.main %}

<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if link.image %} 
    <img src="{{ link.image }}" width="80%" style="display: inline-block;"/>
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 15px;">
      <div class="title">{{ link.title }}</div>
      <div class="contributors">{{link.contributors }}</div>
      <div class="descriptions">{{link.descriptions }}</div>
    </div>
  </div>
  </li>
<!-- <br> -->

{% endfor %}

</ol>
</div>
