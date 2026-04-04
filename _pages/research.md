---
layout: page
permalink: /research/
title: Research
description:
nav: true
nav_order: 3
---

<style>
  .publications h2.bibliography {
    display: none;
  }

  .publications .abbr abbr {
    display: none;
  }

  .publications .abbr {
    padding-top: 0;
  }

  .publications .abbr .badge {
    display: none !important;
  }

  .publications .venue {
    margin: 0.3rem 0 0.4rem;
    font-size: 0.98rem;
  }

  @media (min-width: 768px) {
    .publications .row > .abbr.col-sm-2 {
      flex: 0 0 30%;
      max-width: 30%;
    }

    .publications .row > .col-sm-8 {
      flex: 0 0 70%;
      max-width: 70%;
    }
  }

  .publications .preview {
    width: 100%;
    max-width: 260px;
  }
</style>

<div class="publications">

{% bibliography %}

<h2>Patents</h2>

{% bibliography --file patents %}

</div>
