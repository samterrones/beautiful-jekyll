---
layout: page
title: Photography
images:
  - image_path: /img/hello_world.jpeg
    title: Apple Pie
  - image_path: /img/hello_world.jpeg
    title: Birthday Cake
  - image_path: /img/hello_world.jpeg
    title: Black Forest
  - image_path: /img/hello_world.jpeg
    title: Brownie
  - image_path: /img/hello_world.jpeg
    title: Cheese Cake
  - image_path: /img/hello_world.jpeg
    title: Chocolate Cake
  - image_path: /img/hello_world.jpeg
    title: Fruit Cake
  - image_path: /img/hello_world.jpeg
    title: Lamington
  - image_path: /img/hello_world.jpeg
    title: Lemon Cake
---

<div class="galleryWrap">
  {% for image in page.images %}
    <div class="pictureBox">
      <div class="innerBox">
        <img src="{{ image.image_path }}">
        <div class="titleBox">{{ image.title }}</div>
      </div>
    </div>
  {% endfor %}       
</div>
