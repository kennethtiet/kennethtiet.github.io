---
layout: page
permalink: /pencollection/
title: pen collection
nav: true
nav_order: 3
---

<!-- pages/projects.md -->
<div class="projects">
  <!-- parker -->
  <a id="category" href=".#parker">
    <h2 class="category">parker</h2>
  </a>
    {% assign folder_path = "assets/img/collection/parker" %}
    {% assign files = site.static_files %}
    <div class="row">
        {% for file in files %}
        <!-- Check if the file is in the specified folder -->
        {% assign lower_path = file.path | downcase %}
        {% if lower_path contains folder_path and file.path contains '.jpg' %}
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path=file.path title=file.name class="img-fluid rounded z-depth-1" %}
        </div>
        {% endif %}
        {% endfor %}
    </div>

    <!-- sheaffer -->

  <a id="category" href=".#sheaffer">
    <h2 class="category">sheaffer</h2>
  </a>
    {% assign folder_path = "assets/img/collection/sheaffer" %}
    {% assign files = site.static_files %}
    <div class="row">
        {% for file in files %}
        {% assign lower_path = file.path | downcase %}

        {% if lower_path contains folder_path and file.path contains '.jpg' %}
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path=file.path title=file.name class="img-fluid rounded z-depth-1" %}
        </div>
        {% endif %}
        {% endfor %}
    </div>

    <!-- wahl eversharp -->

  <a id="category" href=".#wahleversharp">
    <h2 class="category">wahl eversharp</h2>
  </a>
    {% assign folder_path = "assets/img/collection/wahleversharp" %}
    {% assign files = site.static_files %}
    <div class="row">
        {% for file in files %}
        {% assign lower_path = file.path | downcase %}

        {% if lower_path contains folder_path and file.path contains '.jpg' %}
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path=file.path title=file.name class="img-fluid rounded z-depth-1" %}
        </div>
        {% endif %}
        {% endfor %}
    </div>

    <!-- esterbrook -->

  <a id="category" href=".#esterbrook">
    <h2 class="category">esterbrook</h2>
  </a>
    {% assign folder_path = "assets/img/collection/esterbrook" %}
    {% assign files = site.static_files %}
    <div class="row">
        {% for file in files %}
        {% assign lower_path = file.path | downcase %}

        {% if lower_path contains folder_path and file.path contains '.jpg' %}
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path=file.path title=file.name class="img-fluid rounded z-depth-1" %}
        </div>
        {% endif %}
        {% endfor %}
    </div>

    <!-- waterman -->

  <a id="category" href=".#waterman">
    <h2 class="category">waterman</h2>
  </a>
    {% assign folder_path = "assets/img/collection/waterman" %}
    {% assign files = site.static_files %}
    <div class="row">
        {% for file in files %}
        {% assign lower_path = file.path | downcase %}

        {% if lower_path contains folder_path and file.path contains '.jpg' %}
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path=file.path title=file.name class="img-fluid rounded z-depth-1" %}
        </div>
        {% endif %}
        {% endfor %}
    </div>

    <!-- writingsamples -->

  <a id="category" href=".#writingsamples">
    <h2 class="category">writing samples</h2>
  </a>
    {% assign folder_path = "assets/img/collection/writingsamples" %}
    {% assign files = site.static_files %}
    <div class="row">
        {% for file in files %}
        {% assign lower_path = file.path | downcase %}

        {% if lower_path contains folder_path and file.path contains '.jpg' %}
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path=file.path title=file.name class="img-fluid rounded z-depth-1" %}
        </div>
        {% endif %}
        {% endfor %}
    </div>

</div>
