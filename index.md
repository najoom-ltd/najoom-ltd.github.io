---
layout: default
title: Najoom | Coming Soon
---

<style>
  .hero-shell {
    max-width: 960px;
    margin: 2rem auto;
    padding: 2.6rem 2.2rem;
    border-radius: 28px;
    background:
      radial-gradient(circle at top left, rgba(255,255,255,0.8) 0%, rgba(255,255,255,0.2) 30%, transparent 45%),
      linear-gradient(135deg, #f8efe8 0%, #efe0d2 45%, #e8d4c2 100%);
    box-shadow: 0 20px 60px rgba(88, 58, 37, 0.16);
    border: 1px solid rgba(112, 76, 54, 0.15);
    position: relative;
    overflow: hidden;
  }

  .hero-shell::before {
    content: "";
    position: absolute;
    inset: 0;
    background:
      linear-gradient(115deg, rgba(255,255,255,0.18), transparent 35%, rgba(255,255,255,0.12) 65%, transparent),
      radial-gradient(circle at 20% 20%, rgba(255,255,255,0.55), transparent 22%),
      radial-gradient(circle at 80% 80%, rgba(255,255,255,0.35), transparent 28%);
    pointer-events: none;
  }

  .hero-content {
    position: relative;
    z-index: 1;
    text-align: center;
  }

  .hero-pill {
    display: inline-block;
    padding: 0.45rem 0.8rem;
    margin-bottom: 1rem;
    border-radius: 999px;
    background: rgba(118, 81, 58, 0.12);
    color: #6f4e3b;
    font-size: 0.85rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    font-weight: 600;
  }

  .hero-brand {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 0 0.6rem;
  }

  .hero-brand img {
    max-width: 280px;
    width: 100%;
    height: auto;
    filter: drop-shadow(0 8px 16px rgba(77, 52, 40, 0.15));
  }

  .hero-tagline {
    margin: 0 auto 1rem;
    max-width: 720px;
    font-size: 1.1rem;
    line-height: 1.7;
    color: #6f4e3b;
  }

  .hero-copy {
    margin: 0 auto 1.4rem;
    max-width: 720px;
    font-size: 1rem;
    line-height: 1.8;
    color: #74513e;
  }

  .hero-footnote {
    margin-top: 0.6rem;
    color: #7a5a4a;
    font-size: 0.98rem;
  }
</style>

<div class="hero-shell">
  <div class="hero-content">
    <div class="hero-pill">Travel abayas • Coming soon</div>
    <div class="hero-brand">
      <img src="Name_Logo_transparent.png" alt="Najoom logo without background">
    </div>
    <p class="hero-tagline">Refined essentials for graceful travel and effortless everyday elegance.</p>
    <p class="hero-copy">We’re preparing a beautifully curated collection of travel abayas designed to feel polished, comfortable, and timeless.</p>
    <p class="hero-footnote">Stay tuned — our new collection is almost here.</p>
  </div>
</div>
