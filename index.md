---
layout: null
title: Najoom | Coming Soon
---
<style>
  html,
  body {
    min-height: 100%;
    margin: 0;
    padding: 0;
    background: linear-gradient(180deg, #f8efe8 0%, #ead9c6 36%, #d8c1a9 100%);
    color: #4d3428;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  }

  body {
    background-image:
      radial-gradient(circle at top left, rgba(255,255,255,0.35), transparent 18%),
      radial-gradient(circle at 20% 18%, rgba(255,255,255,0.5), transparent 22%),
      linear-gradient(180deg, rgba(255,255,255,0.18), transparent 50%);
    background-repeat: no-repeat;
    background-attachment: fixed;
  }

  * {
    box-sizing: border-box;
  }

  .hero-shell {
    max-width: 980px;
    height: 100vh;
    margin: 0 auto;
    padding: 2.5rem 2.4rem;
    border-radius: 32px;
    background:
      radial-gradient(circle at top left, rgba(255,255,255,0.9) 0%, rgba(255,255,255,0.45) 30%, transparent 55%),
      linear-gradient(180deg, rgba(255,255,255,0.95) 0%, rgba(245, 226, 213, 0.88) 42%, rgba(238, 212, 186, 0.88) 100%);
    box-shadow: 0 35px 90px rgba(95, 62, 40, 0.16);
    border: 1px solid rgba(125, 86, 58, 0.12);
    position: relative;
    overflow: hidden;
  }

  .hero-shell::before {
    content: "";
    position: absolute;
    inset: 0;
    background:
      linear-gradient(120deg, rgba(255,255,255,0.2), transparent 36%, rgba(255,255,255,0.15) 64%, transparent),
      radial-gradient(circle at 25% 15%, rgba(255,255,255,0.4), transparent 18%),
      radial-gradient(circle at 80% 80%, rgba(255,255,255,0.2), transparent 25%);
    pointer-events: none;
  }

  .hero-content {
    position: relative;
    z-index: 1;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100%;
    gap: 2rem;
  }

  .hero-brand {
    display: flex;
    justify-content: center;
    margin: 0 auto;
    max-width: 320px;
  }

  .hero-details {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    gap: 1.3rem;
    width: 100%;
    max-width: 720px;
    margin: 0 auto;
    min-height: 34vh;
    padding-bottom: 0.5rem;
  }

  .hero-pill {
    display: inline-block;
    width: auto;
    max-width: none;
    padding: 0.45rem 0.9rem;
    border-radius: 999px;
    background: rgba(126, 88, 60, 0.12);
    color: #6f4e3b;
    font-size: 0.85rem;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    font-weight: 600;
  }

  .hero-brand img {
    width: 100%;
    height: auto;
    background: transparent;
    filter: drop-shadow(0 10px 24px rgba(78, 54, 35, 0.18));
  }

  .hero-tagline {
    margin: 0 auto 1rem;
    max-width: 680px;
    font-size: clamp(1rem, 1.2vw, 1.15rem);
    line-height: 1.75;
    color: #6f4e3b;
  }

  .hero-copy {
    margin: 0 auto 1.6rem;
    max-width: 720px;
    font-size: 1rem;
    line-height: 1.85;
    color: #725641;
  }

  .hero-footnote {
    margin-top: 0.6rem;
    color: #7a5a4a;
    font-size: 0.98rem;
  }
</style>

<div class="hero-shell">
  <div class="hero-content">
    <div class="hero-brand">
      <img src="Name_Logo_transparent.png" alt="Najoom logo without background">
    </div>
    <div class="hero-details">
        <div class="hero-pill">Travel abayas • Coming soon</div>
      <p class="hero-tagline">Refined essentials for graceful travel and effortless everyday elegance.</p>
      <p class="hero-copy">We’re preparing a beautifully curated collection of travel abayas designed to make travel easier while feeling polished, comfortable, and timeless.</p>
      <p class="hero-footnote">Stay tuned — our new collection is almost here.</p>
    </div>
  </div>
</div>
