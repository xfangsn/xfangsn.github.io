<h1 id="publications"></h1>

<h2 style="margin: 60px 0px -15px;">Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?user=GJtATkAAAAAJ" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp>
</h2>
<!--<temp style="font-size:15px;">[</temp><a href="" target="_blank" style="font-size:15px;">DBLP</a><temp style="font-size:15px;">]</temp> -->

<div class="publications-wrapper">

{% if site.data.publications.conference %}
<div class="pub-category">
  <h3 class="pub-category-title"><i class="fa-solid fa-users-rectangle"></i> Conference</h3>
  <div class="publications">
    {% for link in site.data.publications.conference %}
      {% include publication_card.html link=link %}
    {% endfor %}
  </div>
</div>
{% endif %}

{% if site.data.publications.workshop %}
<div class="pub-category">
  <h3 class="pub-category-title"><i class="fa-solid fa-chalkboard-user"></i> Workshop</h3>
  <div class="publications">
    {% for link in site.data.publications.workshop %}
      {% include publication_card.html link=link %}
    {% endfor %}
  </div>
</div>
{% endif %}

{% if site.data.publications.journal %}
<div class="pub-category">
  <h3 class="pub-category-title"><i class="fa-solid fa-book-open"></i> Journal</h3>
  <div class="publications">
    {% for link in site.data.publications.journal %}
      {% include publication_card.html link=link %}
    {% endfor %}
  </div>
</div>
{% endif %}

{% if site.data.publications.preprint %}
<div class="pub-category">
  <h3 class="pub-category-title"><i class="fa-solid fa-file-lines"></i> Preprints</h3>
  <div class="publications">
    {% for link in site.data.publications.preprint %}
      {% include publication_card.html link=link %}
    {% endfor %}
  </div>
</div>
{% endif %}

</div>
