---
layout: gallery
title: Selected Works
permalink: /selected-works/
---

<div class="gallery">
  {% for artwork in site.artwork %}
    <a href="{{ artwork.url }}" class="gallery-item">
      <img src="{{ artwork.image }}" alt="{{ artwork.title }}">
      <div class="artwork-title">{{ artwork.title }}</div>
    </a>
  {% endfor %}
</div>

<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    padding: 2rem;
  }

  .gallery-item {
    position: relative;
    display: block;
    text-decoration: none;
    color: inherit;
    transition: transform 0.2s;
  }

  .gallery-item:hover {
    transform: translateY(-5px);
  }

  .gallery-item img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    display: block;
  }

  .artwork-title {
    margin-top: 0.5rem;
    font-size: 1.1rem;
    text-align: center;
  }
</style>