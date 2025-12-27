---
layout: default
lang: en
title: Tom Tourwé
---

<div class="layout-container">
  <aside class="sidebar">
    <h1>Tom Tourwé</h1>
    <nav class="sidebar-nav">
      <a href="#about" onclick="showSection('about')">About</a>
      <a href="#challenges" onclick="showSection('challenges')">Challenges</a>
    </nav>
  </aside>

  <main class="main-content">

<div class="hero-section">
  <h2>Welcome to my professional portfolio</h2>
  <p>Software engineer, problem solver, and technology enthusiast</p>
</div>

<div id="about" class="section hidden">
  <div class="markdown-content">
    {% include about.md %}
  </div>
</div>

<div id="challenges" class="section hidden">
  <div class="markdown-content">
    {% include challenges.md %}
  </div>
</div>

  </main>
</div>

<div class="language-links">
  <p>Available in: <a href="/en/">English</a> | <a href="/nl/">Nederlands</a></p>
</div>

<script>
function showSection(sectionId) {
  // Hide all sections
  const sections = document.querySelectorAll('.section');
  sections.forEach(section => {
    section.classList.add('hidden');
  });

  // Show the selected section
  const targetSection = document.getElementById(sectionId);
  if (targetSection) {
    targetSection.classList.remove('hidden');
  }

  // Update URL hash
  window.location.hash = sectionId;
}

// Show section based on URL hash on page load
document.addEventListener('DOMContentLoaded', function() {
  const hash = window.location.hash.substring(1);
  if (hash === 'about' || hash === 'challenges') {
    showSection(hash);
  }
});
</script>
