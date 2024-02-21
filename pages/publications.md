---
layout: page
title: Publications
permalink: "/publications/"
image: assets/images/header-publications.png
description: "Click here to get to a list of my publications and publications that I co-authored."

---

Here is a list of my publications, including publications I co-authored. By clicking on the publication tile, you will be redirected to the abstract and further informations. 


{% for post in site.posts %}
<div class="col-md-12">
  {% include postbox.html %}
</div>
{% endfor %}
