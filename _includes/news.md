<h1 id="news"></h1>

<h2 style="margin: 60px 0px 10px;">News</h2>

<ul>

<!-- current news -->
{% for news in site.data.news.current %}
<li>
<strong>[{{ news.date }}]</strong> {{ news.content }}
</li>
{% endfor %}

<!-- old news -->
<!-- 
<li> <a href="javascript:toggle_vis('newsmore')">Show more</a> </li>
<div id="newsmore" style="display:none">
{% for news in site.data.news.old %} 
<li><strong>[{{ news.date }}]</strong> {{ news.content }}</li>
{% endfor %}
</div>
-->

<li>
  <a href="#" class="toggle-link" data-target="newsmore">Show more</a>
</li>

<div id="newsmore" style="display:none;">
{% for news in site.data.news.old %} 
<li><strong>[{{ news.date }}]</strong> {{ news.content }}</li>
{% endfor %}
</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
  document.querySelectorAll(".toggle-link").forEach(function(link) {
    link.addEventListener("click", function(e) {
      e.preventDefault();
      var targetId = this.getAttribute("data-target");
      var target = document.getElementById(targetId);
      if (target.style.display === "none" || target.style.display === "") {
        target.style.display = "block";
        this.textContent = "Show less";
      } else {
        target.style.display = "none";
        this.textContent = "Show more";
      }
    });
  });
});
</script>

</ul>




