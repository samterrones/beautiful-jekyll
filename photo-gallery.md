---
layout: page
title: Photography!
---

<div class="galleryWrap">
  {% for photo in site.photos %}
    <div class="pictureBox">
      <div class="innerBox">
          <img src="{{ photo.path }}">
          <div class="titleBox">{{ photo.title }}</div>
      </div>
    </div>
  {% endfor %}       
</div>
