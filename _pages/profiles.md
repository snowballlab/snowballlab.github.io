---
layout: page
permalink: /people/
title: Members
description: members of the Snowball Lab
nav: true
nav_order: 2
hide_title: true
---

<style>
  .people-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
    margin-top: 0.75rem;
  }

  /* keeps a partly-filled row left-aligned instead of stretching to fill */
  .people-grid.grid-fill {
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  }

  .person-card {
    border-radius: 12px;
    padding: 1rem;
    background: #fff;
  }

  .pi-card {
    display: grid;
    grid-template-columns: minmax(180px, 220px) minmax(0, 1fr);
    gap: 1.5rem;
    align-items: center;
  }

  .pi-section {
    margin-bottom: 1.5rem;
  }

  .pi-copy .person-name {
    margin-top: 0;
  }

  .person-name {
    margin: 0.75rem 0 0;
    font-weight: 700;
  }

  .person-name a {
    color: inherit;
  }

  .person-role {
    margin: 0.3rem 0 0;
    font-size: 0.95rem;
    opacity: 0.85;
  }

  .person-email {
    margin: 0.35rem 0 0;
    font-size: 0.95rem;
  }

  .person-photo {
    width: 100%;
    max-width: 180px;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 999px;
    display: block;
    margin: 0 auto;
  }

  /* wraps the photo when the member has a link; keeps the bare-<img> layout */
  .person-photo-link {
    display: block;
  }

  .person-desc {
    margin: 0.65rem 0 0;
    line-height: 1.45;
    font-size: 0.95rem;
  }

  .student-card {
    text-align: center;
  }

  @media (max-width: 768px) {
    .pi-card {
      grid-template-columns: 1fr;
      text-align: center;
    }
  }
</style>

## Principal Investigator

<div class="people-grid pi-section">
  <div class="person-card pi-card">
    <a class="person-photo-link" href="https://xueqiuyue.com/" target="_blank" rel="noopener noreferrer" tabindex="-1" aria-hidden="true"><img class="person-photo" src="/assets/img/Shirley_Xue.jpg" alt="Qiuyue (Shirley) Xue"></a>
    <div class="pi-copy">
      <p class="person-name"><a href="https://xueqiuyue.com/" target="_blank" rel="noopener noreferrer">Qiuyue (Shirley) Xue</a></p>
      <p class="person-email">qiuyue at purdue dot edu</p>
      <p class="person-desc">Assistant professor<br />
        Department of Computer Science, Purdue University</p>
    </div>
  </div>
</div>

## PhD Students

<div class="people-grid grid-fill">
  <div class="person-card student-card">
    <a class="person-photo-link" href="https://zelo-415.github.io/" target="_blank" rel="noopener noreferrer" tabindex="-1" aria-hidden="true"><img class="person-photo" src="/assets/img/profile_pic/Leyi_Zou.jpg" alt="Leyi Zou"></a>
    <p class="person-name"><a href="https://zelo-415.github.io/" target="_blank" rel="noopener noreferrer">Leyi Zou</a></p>
    <p class="person-role">CS PhD Student</p>
  </div>
</div>

## Undergrad and MS

<div class="people-grid">
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/jiayi_shao.jpg" alt="Jiayi Shao">
    <p class="person-name">Jiayi (Maggie) Shao</p>
    <p class="person-role">UW ECE MS</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Aarav_wadhwani.jpeg" alt="Aarav Wadhwani">
    <p class="person-name">Aarav Wadhwani</p>
    <p class="person-role">UW ECE undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Feng_ye.png" alt="Feng Ye">
    <p class="person-name">Feng Ye</p>
    <p class="person-role">Engineering undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Aylen_kim.jpg" alt="Aylen Kim">
    <p class="person-name">Aylen Kim</p>
    <p class="person-role">Biomedical undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Jang-Hoon-Lee.jpg" alt="Jang Hoon Lee">
    <p class="person-name">Jang Hoon Lee</p>
    <p class="person-role">CS undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Jiaying_ye.jpg" alt="Jiaying Ye">
    <p class="person-name">Jiaying Ye</p>
    <p class="person-role">UW DS undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/yaroslave_stetsko.JPG" alt="Yaroslave Stetsko">
    <p class="person-name">Yaroslav Stetsko</p>
    <p class="person-role">CS undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Soleil_Pham.jpeg" alt="Soleil Pham">
    <p class="person-name">Soleil Pham</p>
    <p class="person-role">CS undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/AntaraDurbha.jpg" alt="Antara Durbha">
    <p class="person-name">Antara Durbha</p>
    <p class="person-role">CS undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Qiyu_Ji.jpg" alt="Qiyu Ji">
    <p class="person-name">Qiyu Ji</p>
    <p class="person-role">CS undergrad</p>
  </div>
  <div class="person-card student-card">
    <img class="person-photo" src="/assets/img/profile_pic/Rishabh_Goenka.png" alt="Rishabh Goenka">
    <p class="person-name">Rishabh Goenka</p>
    <p class="person-role">UW ECE undergrad</p>
  </div>
</div>
