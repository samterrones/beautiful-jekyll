---
title: Photography
layout: page
---

A Photo | Another Photo | A Third Photo
:---:|:---:|:---:
![](/img/hello_world.jpeg) | ![](/img/hello_world.jpeg) | ![](/img/hello_world.jpeg)

<ul>
  <li class="container">
    <img class="image" src="/img/hello_world.jpeg"/>
    <span class="caption">my caption</span>
  </li>
  <li class="container">
    <img class="image" src="/img/hello_world.jpeg"/>
    <span class="caption">my caption</span>
  </li>
</ul>

.container {
  float: left;
}

.image {
  display: block
}

.caption {
  display: block;
  width: 100%;
  text-align: center; //assuming centered captions
}
