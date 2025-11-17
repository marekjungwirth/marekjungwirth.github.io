---
layout: page
title: Home
permalink: /
---

<style>
.home-container {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin: 2rem 0;
  gap: 2rem;
  max-width: 100%;
}

.intro-section {
  flex: 1;
  min-width: 0;
}

.ascii-art-section {
  flex: 0 0 300px;
  max-width: 300px;
}

.ascii-image {
  max-width: 100%;
  height: auto;
  border: 1px solid currentColor;
  padding: 0.5rem;
  display: block;
}

.quote-section {
  margin-top: 4rem;
  text-align: center;
  clear: both;
}

.quote-text {
  font-style: italic;
}

@media (max-width: 768px) {
  .home-container {
    flex-direction: column;
  }
  .ascii-art-section {
    max-width: 100%;
  }
}
</style>

<div class="home-container">
  <div class="intro-section">
    <p class="intro-text">
      Hello traveller!<br>
      Choose any path above.
    </p>
  </div>
  
  <div class="ascii-art-section">
    <img src="{{ '/assets/muj-cool-obrazek.png' | relative_url }}" alt="ASCII art postava" class="ascii-image">
  </div>
</div>

<div class="quote-section">
  <p class="quote-text">
    Není to náhodou pocestný? Je to pocestný!
  </p>
</div>
