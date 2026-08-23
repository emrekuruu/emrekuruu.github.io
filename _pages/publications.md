---
layout: page
permalink: /publications/
title: publications
description: Research publications in AI agents, information retrieval, multimodal RAG, and multi-agent systems.
nav: true
nav_order: 2
---

<style>
  .publications .links { display: none; }
  .publications #kuru2026retrievalrouter .links { display: block; }
  .publications .links .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-width: 4.6rem;
    height: 2rem;
    padding: 0 0.7rem;
    border-radius: 6px;
    font-size: 0.75rem;
    font-weight: 700;
    line-height: 1;
    box-sizing: border-box;
    vertical-align: middle;
  }
  .publications .links a[href*="#paper"] { font-size: 0; }
  .publications .links a[href*="#paper"]::after { content: "Paper"; font-size: 0.75rem; }
  .publications .links a[href*="#paper-"],
  .publications .links a[href^="#code-"] { cursor: default; pointer-events: none; }
</style>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
