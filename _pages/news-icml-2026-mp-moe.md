---
layout: archive
permalink: /news/icml-2026-mp-moe/
title: "Notes from ICML 2026 in Seoul"
author_profile: true
---

<style>
.news-photo-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
  margin: 1.1rem auto;
  max-width: 820px;
  align-items: start;
}
.news-photo-card {
  margin: 0;
  overflow: hidden;
  border: 7px solid #fff;
  border-radius: 8px;
  background: #fff;
  box-shadow: 0 10px 26px rgba(37, 31, 28, 0.12);
  transition: transform 180ms ease, box-shadow 180ms ease;
}
.news-photo-card--wide {
  grid-column: 1 / -1;
}
.news-photo-card:nth-child(odd) {
  transform: rotate(-0.6deg);
}
.news-photo-card:nth-child(even) {
  transform: rotate(0.7deg);
}
.news-photo-card:hover {
  transform: translateY(-3px) rotate(0deg);
  box-shadow: 0 14px 32px rgba(37, 31, 28, 0.16);
}
.news-photo-card img {
  display: block;
  width: 100%;
  height: auto;
  border-radius: 4px;
}
.news-photo-card figcaption {
  margin-top: 0.55rem;
  padding-left: 0.55rem;
  border-left: 3px solid #d94b3d;
  color: #6a574f;
  font-size: 0.76rem;
  line-height: 1.4;
  letter-spacing: 0;
}
@media (max-width: 720px) {
  .news-photo-grid {
    grid-template-columns: 1fr;
    max-width: 100%;
    gap: 0.85rem;
  }
  .news-photo-card {
    border-width: 5px;
    transform: none !important;
  }
}
</style>

In July 2026, Xinlai Kang and Dunyao Xue traveled to Seoul and presented the team's latest MP-MoE work during the ICML 2026 poster session.

From the venue check-in to the poster session, they discussed expert selection, complementarity modeling, and practical efficiency in MoE systems with researchers from different directions. The conversations also brought back useful observations for the group's follow-up work.

<div class="news-photo-grid">
  <figure class="news-photo-card news-photo-card--wide">
    <img loading="lazy" src="https://cheng-bdal.github.io/images/news/icml-2026-mp-moe-entrance.jpg" alt="Xinlai Kang and Dunyao Xue at the ICML 2026 venue in Seoul" width="1600" height="1200">
    <figcaption>Checking in at the ICML 2026 venue in Seoul</figcaption>
  </figure>
  <figure class="news-photo-card">
    <img loading="lazy" src="https://cheng-bdal.github.io/images/news/icml-2026-mp-moe-poster-presenters.jpg" alt="Xinlai Kang and Dunyao Xue in front of the MP-MoE poster" width="1600" height="1200">
    <figcaption>In front of the MP-MoE poster</figcaption>
  </figure>
  <figure class="news-photo-card">
    <img loading="lazy" src="https://cheng-bdal.github.io/images/news/icml-2026-mp-moe-poster-discussion.jpg" alt="Xinlai Kang discussing the MP-MoE poster with ICML attendees" width="1600" height="1200">
    <figcaption>Discussing the method details on site</figcaption>
  </figure>
  <figure class="news-photo-card">
    <img loading="lazy" src="https://cheng-bdal.github.io/images/news/icml-2026-mp-moe-poster-crowd.jpg" alt="Attendees gathered around the MP-MoE poster at ICML 2026" width="1600" height="1200">
    <figcaption>Exchange during the poster session</figcaption>
  </figure>
</div>
