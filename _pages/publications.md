---
layout: page
permalink: /publications/
title: Publications
description: Browse publications by year or search by title, author, and topic.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<p>
  <a href="https://scholar.google.com/citations?user={{ site.scholar_userid }}">
    View my Google Scholar profile <span aria-hidden="true">↗</span>
  </a>
</p>

<!-- <div class="publication-tools" aria-label="Publication filters">
  <label for="publication-search"><strong>Search publications</strong></label>
  <div class="publication-search-row">
    <input
      id="publication-search"
      type="search"
      placeholder="Search by title, author, or topic"
      autocomplete="off"
      aria-describedby="publication-results"
    >
    <button id="publication-search-clear" class="btn" type="button" hidden>Clear</button>
  </div>
  <div class="publication-year-nav" aria-label="Jump to publication year"></div>
  <p id="publication-results" class="publication-results" aria-live="polite"></p>
</div>


<div class="topic-legend" id="topic-filter" role="toolbar" aria-label="Filter publications by topic">
  <span class="topic-legend__hint">Click a topic to filter:</span>
  <button type="button" class="topic-btn is-active" data-topic="all">ALL</button>
  <button type="button" class="topic-btn" data-topic="matrixpolys"><span class="topic-ico">📕</span> Matrix Polynomials &amp; Nonlinear Eigenvalue Problems</button>
  <button type="button" class="topic-btn" data-topic="krylovNLA"><span class="topic-ico">📙</span> Krylov Methods in NLA</button>
  <button type="button" class="topic-btn" data-topic="logistics"><span class="topic-ico">📘</span> Supply Chain Management</button>
  <button type="button" class="topic-btn" data-topic="MLandHPC"><span class="topic-ico">📗</span> Machine Learning &amp; Parallel Algorithms</button>
  <button type="button" class="topic-btn" data-topic="other"><span class="topic-ico">📔</span> Other</button>
</div>

<style>
  .topic-legend {
    display: flex;
    flex-wrap: wrap;
    column-gap: 0.6rem;
    row-gap: 0.4rem;
    align-items: center;
  }

  .topic-legend__hint {
    flex-basis: 100%;
    font-weight: 400;
    font-size: 1.6rem;
    margin-bottom: 0.3rem;
  }
</style> -->


<!-- <div class="under-construction">
  🚧 This page is still under construction 🚧
</div>

<style>
  .under-construction {
    text-align: center;
    font-size: 2rem;
    font-weight: bold;
    color: blue;
    margin: 2rem 0;
    /* animation: blink 1s infinite; */
  }

  /* @keyframes blink {
    0%, 50% {
      opacity: 1;
    }
    51%, 100% {
      opacity: 0;
    } */
</style> -->



<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>

<script defer src="{{ '/assets/js/publications.js' | relative_url }}"></script>