---
layout: page
title: Photography
---

<div class="galleryWrap">
  {% for photo in site.photos %}
    <div class="pictureBox">
      <div class="innerBox">
        <a href="{{ photo.url }}">
          <img src="{{ photo.path }}">
          <div class="titleBox">{{ photo.title }}</div>
        </a>
      </div>
    </div>
  {% endfor %}       
</div>
