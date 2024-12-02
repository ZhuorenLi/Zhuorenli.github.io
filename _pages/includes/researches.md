

# 📝 Research Experiences 
<!-- ## 🎙 Speech Synthesis -->

<!-- pages/research.md -->
<div class="projects" style="margin-top:50px;margin-bottom:20px">


<!-- Display projects without categories -->

{% assign sorted_projects = site.researches | sort: "importance" %}

  <!-- Generate cards for each project -->


  <div class="projects_list">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  </div>

