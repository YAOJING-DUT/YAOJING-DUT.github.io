---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="about-intro">
  <p class="about-intro__text">Hi there! I am <strong>Jing Yao</strong> 👋. I am a physics and mathematics enthusiast currently working in the field of <em>super-resolution microscopy</em> 🔬. My research focuses on developing advanced imaging methods to explore complex biological structures beyond the diffraction limit, which involves multiple fields, including optics, electronics, algorithms, and mechanics 😊.</p>
</div>

<div class="news-section">
<h2 class="news-section__title">NEWS</h2>
<div class="news-section__content">
<div class="news-item">
  <span class="news-item__date">2026.05</span>
  <span class="news-item__text">Our paper was accepted by <strong>Biomedical Optics Express</strong> (BOE) 🎉</span>
</div>
<!-- Add news items here, e.g.:
<div class="news-item">
  <span class="news-item__date">2024.01</span>
  <span class="news-item__text">Paper accepted in ...</span>
</div>
-->
</div>
</div>

<style>
.about-intro {
  margin: 0 0 2em;
}
.about-intro__text {
  font-size: 1.05em;
  line-height: 1.85;
  color: var(--global-text-color);
  padding: 1.2em 1.5em;
  background: var(--global-accent-light, rgba(79, 70, 229, 0.04));
  border-radius: 12px;
  border-left: 4px solid var(--global-accent-color, #4f46e5);
  box-shadow: 0 2px 12px rgba(79, 70, 229, 0.07);
  animation: fadeInUp 0.6s ease both;
  animation-delay: 0.1s;
}
.about-intro__text strong {
  color: var(--global-accent-color, #4f46e5);
  font-weight: 700;
}
.news-section {
  margin-top: 1em;
}
.news-section__title {
  font-family: 'Times New Roman', serif;
  font-weight: 600;
  font-size: 2.2em;
  letter-spacing: 0.04em;
  background: linear-gradient(135deg, var(--global-accent-color, #4f46e5), var(--global-accent-secondary, #7c3aed));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 0.5em;
}
.news-section__content {
  min-height: 3em;
}
.news-item {
  display: flex;
  gap: 1em;
  align-items: flex-start;
  padding: 0.7em 1em;
  margin-bottom: 0.5em;
  background: var(--global-bg-color);
  border: 1px solid var(--global-border-color);
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(79, 70, 229, 0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.news-item:hover {
  transform: translateX(4px);
  box-shadow: 0 4px 16px rgba(79, 70, 229, 0.1);
}
.news-item__date {
  font-weight: 600;
  color: var(--global-accent-color, #4f46e5);
  white-space: nowrap;
  font-size: 0.9em;
  min-width: 5em;
}
@keyframes fadeInUp {
  from { opacity: 0; transform: translateY(16px); }
  to   { opacity: 1; transform: translateY(0); }
}
</style>
