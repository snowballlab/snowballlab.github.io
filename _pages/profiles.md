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
    <img class="person-photo" src="/assets/img/Shirley_Xue.jpg" alt="Qiuyue (Shirley) Xue">
    <div class="pi-copy">
      <p class="person-name"><a href="https://xueqiuyue.com/" target="_blank" rel="noopener noreferrer">Qiuyue (Shirley) Xue</a></p>
      <p class="person-email">qiuyue at purdue dot edu</p>
      <p class="person-desc">
        Qiuyue (Shirley) Xue is an Assistant Professor in the Department of
        Computer Science at Purdue University. She earned her Ph.D. in Computer
        Science and Engineering from the University of Washington, an M.S. in
        Computer Science from Georgia Institute of Technology, and dual B.S.
        degrees in Computer Science and Electrical Engineering from Peking
        University. Her research focuses on ubiquitous computing,
        human-computer interaction, wearable computing, mobile health, novel
        sensing, and low-power embedded systems.
      </p>
    </div>
  </div>
</div>

## Students

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
    <img class="person-photo" src="/assets/img/profile_pic/Richard_Li.jpg" alt="Richard Li">
    <p class="person-name">Richard Li</p>
    <p class="person-role">CE undergrad</p>
  </div>
</div>
