---
layout: default
title: About
permalink: /about/
---

<div class="about-page">

  <div class="about-container">
    <div class="about-header">
      <h1 class="gradient-text">About Prestige Empire</h1>
      <p class="about-subtitle">Your Definitive Guide to Luxury Living</p>
    </div>

    <div class="about-content">
      <section class="about-section">
        <h2>Our Vision</h2>
        <p>Prestige Empire is devoted to those who appreciate the finer things in life. We curate the most exclusive content 
        on luxury timepieces, high-end automobiles, designer fashion, and exceptional experiences that define 
        a premium lifestyle.</p>
      </section>

      <section class="about-section">
        <h2>What We Cover</h2>
        <div class="features-grid">
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <circle cx="12" cy="12" r="10"></circle>
              <circle cx="12" cy="12" r="1"></circle>
              <polyline points="12 6 12 12"></polyline>
            </svg>
            <h3>Luxury Timepieces</h3>
            <p>In-depth coverage of prestigious watch brands, collections, and horological masterpieces</p>
          </div>
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <rect x="4" y="10" width="16" height="8" rx="2"></rect>
              <path d="M6 7v3"></path>
              <path d="M18 7v3"></path>
              <circle cx="8" cy="18" r="2"></circle>
              <circle cx="16" cy="18" r="2"></circle>
            </svg>
            <h3>Exclusive Automobiles</h3>
            <p>Reviews and features on the world's most distinguished vehicles and automotive innovations</p>
          </div>
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M20.38 3.46L16 2a4 4 0 01-8 0L3.62 3.46a2 2 0 00-1.34 2.23l.58 3.47a1 1 0 00.99.84H6v10c0 1.1.9 2 2 2h8a2 2 0 002-2V10h2.15a1 1 0 00.99-.84l.58-3.47a2 2 0 00-1.34-2.23z"></path>
            </svg>
            <h3>Designer Fashion</h3>
            <p>The latest collections from prestigious fashion houses and style insights for the discerning</p>
          </div>
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0118 0z"></path>
              <circle cx="12" cy="10" r="3"></circle>
            </svg>
            <h3>Elite Destinations</h3>
            <p>Curated guides to the most exquisite travel experiences and accommodations around the world</p>
          </div>
        </div>
      </section>

      <section class="about-section">
        <h2>The Prestige Difference</h2>
        <ul class="benefits-list">
          <li>✓ Exclusive content from luxury experts</li>
          <li>✓ Unparalleled coverage of premium brands</li>
          <li>✓ Elegantly designed reading experience</li>
          <li>✓ Insider access to the world of luxury</li>
        </ul>
      </section>

      <section class="about-section contact-section">
        <h2>Connect With Us</h2>
        <p>For collaborations, partnerships, or inquiries, please contact us at:</p>
        <a href="mailto:{{ site.email }}" class="contact-button">{{ site.email }}</a>
      </section>
    </div>
  </div>
</div>

<style>
.about-page {
  background: var(--bg-primary);
}

.about-header {
  text-align: center;
  margin-bottom: 4rem;
}

.about-subtitle {
  font-size: 1.25rem;
  color: var(--text-secondary);
  margin-top: 1rem;
}

.about-section {
  margin-bottom: 4rem;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.feature-card {
  background: var(--card-bg);
  padding: 2rem;
  border-radius: 0.5rem;
  border: 1px solid var(--border-color);
  text-align: center;
  transition: all 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: var(--shadow-lg);
}

.feature-card svg {
  color: var(--accent-color);
  margin-bottom: 1rem;
  width: 40px;
  height: 40px;
}

.benefits-list {
  list-style: none;
  padding: 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin-top: 2rem;
}

.benefits-list li {
  padding: 1rem;
  background: var(--card-bg);
  border-radius: 0.5rem;
  border: 1px solid var(--border-color);
}

.contact-section {
  text-align: center;
}

.contact-button {
  display: inline-block;
  padding: 1rem 2rem;
  background: var(--accent-color);
  color: white;
  border-radius: 0.5rem;
  margin-top: 1rem;
  transition: all 0.3s ease;
}

.contact-button:hover {
  background: var(--accent-hover);
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .features-grid {
    grid-template-columns: 1fr;
  }
  
  .benefits-list {
    grid-template-columns: 1fr;
  }
}
</style>
