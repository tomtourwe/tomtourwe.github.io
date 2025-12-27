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
  <h2>About Me</h2>
  <div class="about-content">
    <p>I'm a passionate software engineer with expertise in building scalable solutions and solving complex technical challenges. I believe in clean code, continuous learning, and delivering value through technology.</p>

    <h3>Skills & Expertise</h3>
    <ul>
      <li>Software Development & Architecture</li>
      <li>Problem Solving & Algorithm Design</li>
      <li>Team Leadership & Mentoring</li>
      <li>Technology Strategy & Innovation</li>
    </ul>

    <h3>Experience</h3>
    <p>With years of experience in the software industry, I've worked on diverse projects ranging from web applications to distributed systems, always focusing on delivering robust and maintainable solutions.</p>
  </div>
</div>

<div id="challenges" class="section hidden">
  <h2>Challenges & Projects</h2>
  <div class="challenges-content">
    <p>Here you'll find a collection of interesting technical challenges, coding problems, and projects I've worked on. Each challenge demonstrates different aspects of software engineering and problem-solving.</p>

    <div class="challenge-grid">
      <div class="challenge-card">
        <h3>Algorithm Challenges</h3>
        <p>Complex algorithmic problems and their efficient solutions</p>
      </div>

      <div class="challenge-card">
        <h3>System Design</h3>
        <p>Architectural challenges and scalable system designs</p>
      </div>

      <div class="challenge-card">
        <h3>Code Optimization</h3>
        <p>Performance improvements and optimization techniques</p>
      </div>
    </div>
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
