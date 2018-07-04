---
layout: page
title: Photography!
---

<div class="galleryWrap">
  {% for photo in site.photos %}
    <div class="pictureBox">
      <div class="innerBox">
        <a href="{{ photo.url }}">
          <img src="{{ photo.image-path }}">
        </a>
          <div class="titleBox">{{ photo.title }}</div>
      </div>
    </div>
  {% endfor %}       
</div>
