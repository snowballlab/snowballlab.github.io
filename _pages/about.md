---
layout: about
title: Home
permalink: /
subtitle:
hide_page_title: true
bottom_logo: /assets/img/purdue_logo.png
bottom_logo_alt: Purdue logo
bottom_logo_max_width: 220px

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  .home-intro {
    display: grid;
    grid-template-columns: minmax(220px, 360px) minmax(0, 1fr);
    gap: 1.5rem;
    align-items: center;
    margin: 0.5rem 0 2rem;
  }

  .home-intro-logo {
    width: 100%;
    max-width: 340px;
    height: auto;
    display: block;
  }

  .home-intro-copy h2 {
    margin: 0 0 0.75rem;
    font-size: 1.8rem;
  }
  .home-intro-copy p {
    margin: 0;
    font-size: 1rem;
    line-height: 1.65;
  }

  .theme-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 1rem;
    margin: 1.5rem 0 2rem;
  }

  .theme-card {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 1.5rem 1.1rem 1.2rem;
    border-radius: 16px;
    border: 1px solid rgba(0, 0, 0, 0.1);
    background: linear-gradient(180deg, #ffffff 0%, #f8fbff 100%);
  }

  .theme-icon {
    width: 108px;
    height: 108px;
    margin: 0 auto 0.9rem;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2.5rem;
    color: #2a6f97;
  }

  .theme-illustration {
    width: 108px;
    height: 108px;
    display: block;
    object-fit: contain;
  }

  .theme-title {
    margin: 0;
    font-weight: 700;
    font-size: 1.12rem;
    line-height: 1.3;
    min-height: 2.9rem;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .theme-text {
    margin: 0.65rem 0 0;
    font-size: 0.95rem;
    line-height: 1.55;
  }

  .teaser-row {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    margin: 0.75rem 0 2rem;
  }

  .teaser-row img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 14px;
    display: block;
  }

  @media (max-width: 768px) {
    .home-intro {
      grid-template-columns: 1fr;
      text-align: center;
    }

    .home-intro-logo {
      margin: 0 auto;
    }

    .teaser-row {
      grid-template-columns: 1fr;
    }

    .teaser-row img {
      height: auto;
    }
  }
</style>

<div class="home-intro">
  <div>
    <img class="home-intro-logo" src="/assets/img/Snowball_lab_logo_new.png" alt="Snowball Lab logo">
  </div>
  <div class="home-intro-copy">
    <p>
      Snowball Lab is part of the Department of Computer Science at Purdue
      University. We create novel sensing technologies, signal processing and
      machine learning methods, low-power systems, and embedded intelligence to
      address important real-world problems. Our work spans applications in
      wearable computing, health, and human-computer interaction. We are
      particularly interested in building systems that are practical for
      everyday life, scalable beyond research prototypes, and robust for
      long-term deployment in real-world settings.
    </p>
  </div>
</div>

## Research Themes

<div class="theme-grid">
  <div class="theme-card">
    <div class="theme-icon">
      <img class="theme-illustration" src="/assets/img/earring_icon_.png" alt="Wearable computing icon">
    </div>
    <p class="theme-title">Wearable Computing</p>
    <p class="theme-text">
      Transforming everyday accessories into intelligent wearable systems that
      enable new applications that were previously challenging or impossible.
    </p>
  </div>
  <div class="theme-card">
    <div class="theme-icon">
      <img class="theme-illustration" src="/assets/img/mobile_health_icon.png" alt="Mobile health icon">
    </div>
    <p class="theme-title">Mobile Health</p>
    <p class="theme-text">
      Enabling passive, accessible health monitoring in daily life that can
      capture transient health conditions to support onset detection and early
      intervention.
    </p>
  </div>
  <div class="theme-card">
    <div class="theme-icon">
      <img class="theme-illustration" src="/assets/img/low-power_inteligence_icon.png" alt="Low-power intelligence icon">
    </div>
    <p class="theme-title">Low-Power Intelligence</p>
    <p class="theme-text">
      Pushing the boundaries of low-power systems and embedded machine learning
      to enable ubiquitous intelligence while remaining unobtrusive.
    </p>
  </div>
</div>

<div class="teaser-row">
  <img src="/assets/img/ppg_earring_teaser_fig.png" alt="PPG earring teaser figure">
  <img src="/assets/img/necklace_teaser_fig.png" alt="Necklace teaser figure">
  <img src="/assets/img/ThermalEarring_004.jpg" alt="Thermal earring teaser figure">
  <img src="/assets/img/Thermal_earring_intro.png" alt="Thermal earring intro figure">
</div>

Learn more about the team on the [Members](/people/) page and see our work on the
[Research](/research/) page.
