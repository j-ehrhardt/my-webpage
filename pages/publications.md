---
layout: page
title: Publications
order: 1
permalink: "/publications/"
image: assets/images/header-publications.png
description: "Click here to get to a list of my peer-reviewed publications and publications that I co-authored."

---

Here is a list of my peer-reviewed publications, including publications I co-authored. By clicking on the publication title, you will be redirected to the abstract and further information. 

{% for post in site.posts %}

<div class="col-md-12">
  {% include postbox.html %}
</div>
{% endfor %}
