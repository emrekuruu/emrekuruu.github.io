---
layout: about
title: about
permalink: /
subtitle: PhD Student in Computer Science · Institut Polytechnique de Paris

profile: false

selected_papers: false # rendered manually below so it appears before the timeline
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<style>
  [data-theme="dark"] {
    --global-theme-color: #d06bc8;
    --global-hover-color: #d06bc8;
  }
  .clearfix > h2 {
    margin-top: 4rem;
    margin-bottom: 1.35rem;
  }
  #selected-publications { margin-bottom: 0.35rem; }
  #selected-publications + .publications { margin-top: 0.35rem; }
  .publications .links a[href*="#paper"] { font-size: 0; }
  .publications .links a[href*="#paper"]::after { content: "Paper"; font-size: 0.75rem; }
  .publications .links .btn { border-radius: 6px; }
  .publications .links a[href*="#paper-"],
  .publications .links a[href^="#code-"] { cursor: default; pointer-events: none; }
  #kuru2026retrievalrouter .links::before {
    content: "EMNLP";
    display: inline-flex;
    align-items: center;
    justify-content: center;
    margin-right: 0.25rem;
    min-width: 4.6rem;
    height: 2rem;
    padding: 0 0.7rem;
    border-radius: 6px;
    background: #ccfbf1;
    color: #0f766e;
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    line-height: 1;
    box-sizing: border-box;
    vertical-align: middle;
  }
  #kuru2026retrievalrouter .links .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-width: 4.6rem;
    height: 2rem;
    padding: 0 0.7rem;
    font-size: 0.75rem;
    font-weight: 700;
    line-height: 1;
    box-sizing: border-box;
    vertical-align: middle;
  }
  #kuru2026retrievalrouter .links a[href*="#paper"] { font-size: 0; }
  #kuru2026retrievalrouter .links a[href*="#paper"]::after { font-size: 0.75rem; }
  #kuru2026retrievalrouter .periodical { display: none; }
  .social .contact-icons { font-size: 3.15rem; }
  .contact-icons a[title="Hugging Face"] img {
    width: 4.6rem;
    height: 4.6rem;
    margin-bottom: 0.3rem;
  }
</style>

I am a PhD student in Computer Science at [Institut Polytechnique de Paris](https://www.ip-paris.fr/en), working on **self-evolving AI agents** and **agent memory**. My research asks how long-horizon agents can acquire, organize, retrieve, and improve procedural knowledge from experience.

## Research interests

- Self-evolving agents and procedural memory
- Long-horizon LLM agents
- Information retrieval and multimodal RAG

## Selected publications

{% include selected_papers.liquid %}

## Timeline

<div style="position: relative; margin: 1.5rem 0 2.75rem; padding-left: 3rem">
  <div
    aria-hidden="true"
    style="position: absolute; top: 0.65rem; bottom: -1.25rem; left: 0.72rem; width: 2px; background: linear-gradient(to bottom, var(--global-theme-color), color-mix(in srgb, var(--global-theme-color) 8%, transparent))"
  ></div>

  <article style="position: relative">
    <span
      aria-hidden="true"
      style="position: absolute; top: 0.45rem; left: -2.73rem; width: 1.15rem; height: 1.15rem; border: 4px solid var(--global-bg-color); border-radius: 999px; background: var(--global-theme-color); box-shadow: 0 0 0 1px color-mix(in srgb, var(--global-theme-color) 35%, transparent), 0 0 18px color-mix(in srgb, var(--global-theme-color) 25%, transparent)"
    ></span>

    <div
      style="padding: 1.25rem 1.4rem; border: 1px solid var(--global-divider-color); border-radius: 14px; background: var(--global-card-bg-color); box-shadow: 0 10px 30px rgba(0, 0, 0, 0.04)"
    >
      <div style="display: flex; flex-wrap: wrap; gap: 0.6rem; align-items: center; justify-content: space-between; margin-bottom: 0.8rem">
        <time
          datetime="2026-08-20"
          style="padding: 0.28rem 0.65rem; border-radius: 999px; background: color-mix(in srgb, var(--global-theme-color) 12%, transparent); color: var(--global-theme-color); font-size: 0.75rem; font-weight: 700; letter-spacing: 0.06em"
          >20 AUG 2026</time
        >
        <span
          style="padding: 0.28rem 0.65rem; border-radius: 6px; background: #ccfbf1; color: #0f766e; font-size: 0.75rem; font-weight: 700; letter-spacing: 0.06em; line-height: 1.25"
          >EMNLP</span
        >
      </div>

      <h3 style="margin: 0; font-size: 1.08rem; line-height: 1.45">
        RetrievalRouter: Joint Modality and Architecture Selection for Document Retrieval
      </h3>
    </div>

  </article>
</div>
