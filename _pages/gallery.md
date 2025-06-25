---
layout: splash
title: Full Photo Gallery
permalink: /gallery/
---

## Full Photo Gallery

<div class="gallery-grid">
  {% for image in site.static_files %}
    {% if image.path contains 'assets/photos' %}
    <img src="{{ image.path | relative_url }}" alt="Gallery image" />
    {% endif %}
  {% endfor %}
</div>

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
  gap: 20px;
  max-width: 1100px;
  margin: 40px auto;
}
.gallery-grid img {
  width: 100%;
  height: 280px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 6px 20px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
  cursor: pointer;
  background: white;
}
.gallery-grid img:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 35px rgba(0,0,0,0.2);
}
</style>
