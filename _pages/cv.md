---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-timeline {
    display: grid;
    gap: 0.75rem;
    margin-bottom: 1.4rem;
  }
  .cv-entry {
    display: grid;
    grid-template-columns: minmax(7rem, 10rem) 1fr;
    gap: 0.9rem;
    padding: 0.8rem 0.9rem;
    border: 1px solid #e6e0dc;
    border-left: 3px solid #8b1e2d;
    border-radius: 6px;
    background: #fbfaf8;
  }
  .cv-date {
    align-self: start;
    width: fit-content;
    padding: 0.12rem 0.48rem;
    border: 1px solid #d8c8bf;
    border-radius: 999px;
    background: #fff;
    color: #8b1e2d;
    font-size: 0.82rem;
    font-weight: 700;
    line-height: 1.4;
  }
  .cv-entry h3 {
    margin: 0 0 0.25rem;
    font-size: 1rem;
  }
  .cv-entry p {
    margin: 0.15rem 0;
  }
  .cv-service {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.75rem;
  }
  .cv-service-item {
    min-width: 0;
    padding: 0.85rem 0.9rem;
    border: 1px solid #e6e0dc;
    border-left: 3px solid #8b1e2d;
    border-radius: 6px;
    background: #fbfaf8;
  }
  .cv-service-item h3 {
    margin: 0 0 0.35rem;
    font-size: 1rem;
  }
  .cv-service-item p {
    margin: 0.2rem 0 0.45rem;
  }
  .cv-service-item a {
    display: inline-block;
    margin-left: 0.2rem;
    padding: 0.08rem 0.42rem;
    border: 1px solid #d8c8bf;
    border-radius: 999px;
    background: #fff;
    color: #8b1e2d;
    font-size: 0.78rem;
    font-weight: 600;
    line-height: 1.35;
    text-decoration: none;
  }
  .cv-service-item a:hover {
    background: #f7e6e6;
    text-decoration: none;
  }
  .cv-image-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.45rem;
    margin-top: 0.5rem;
  }
  .cv-image-grid img,
  .cv-image-wide {
    width: 100%;
    border: 1px solid #e6e0dc;
    border-radius: 6px;
    background: #fff;
  }
  .cv-image-wide {
    max-width: 100%;
    max-height: 155px;
    margin-top: 0.5rem;
    object-fit: cover;
  }
  @media (max-width: 1024px) {
    .cv-service {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }
  @media (max-width: 720px) {
    .cv-entry {
      grid-template-columns: 1fr;
      gap: 0.25rem;
    }
    .cv-service {
      grid-template-columns: 1fr;
    }
    .cv-image-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
    .cv-image-wide {
      max-height: 160px;
    }
  }
</style>

Academic Positions
======
<div class="cv-timeline">
  <div class="cv-entry">
    <div class="cv-date">2020 - present</div>
    <div>
      <h3>Tenure-Track Assistant Professor</h3>
      <p>Renmin University of China, Institute of Statistics and Big Data</p>
      <p>Beijing, China</p>
    </div>
  </div>
</div>

Education
======
<div class="cv-timeline">
  <div class="cv-entry">
    <div class="cv-date">2015 - 2020</div>
    <div>
      <h3>Ph.D. in Statistics</h3>
      <p>University of Georgia, Department of Statistics</p>
    </div>
  </div>
  <div class="cv-entry">
    <div class="cv-date">2011 - 2015</div>
    <div>
      <h3>Bachelor of Mathematics</h3>
      <p>Tsinghua University, Department of Mathematics and Applied Mathematics</p>
    </div>
  </div>
</div>


Service
=====
<div class="cv-service">
  <div class="cv-service-item">
    <h3>Editorial Service</h3>
    <p>Associate editor for the Data Science section of <em>The Chinese Encyclopedia</em>, Third Edition: Statistics Volume.</p>
    <div class="cv-image-grid">
      <img loading="lazy" src="https://cheng-bdal.github.io//images/百科全书P1.png" alt="Chinese Encyclopedia page 1">
      <img loading="lazy" src="https://cheng-bdal.github.io//images/百科全书P2.png" alt="Chinese Encyclopedia page 2">
      <img loading="lazy" src="https://cheng-bdal.github.io//images/百科全书P3.png" alt="Chinese Encyclopedia page 3">
      <img loading="lazy" src="https://cheng-bdal.github.io//images/百科全书P4.png" alt="Chinese Encyclopedia page 4">
    </div>
  </div>
  <div class="cv-service-item">
    <h3>Admissions and Outreach</h3>
    <p>Member of the Renmin University of China Shanghai Admissions Committee (2023-2026).</p>
    <img loading="lazy" class="cv-image-wide" src="https://cheng-bdal.github.io//images/上海招生.jpg" alt="RUC Shanghai admissions">
    <p>Representative of the Renmin University of China Jiangsu Admissions Committee in 2025; delivered a science outreach talk at Tianyi High School, Jiangsu Province. <a href="https://mp.weixin.qq.com/s/Rhzmvg_Trd_3_13nDxzjRg">Read more</a></p>
    <img loading="lazy" class="cv-image-wide" src="https://cheng-bdal.github.io//images/江苏省招生.jpg" alt="RUC Jiangsu admissions">
  </div>
  <div class="cv-service-item">
    <h3>Laboratory Mentoring</h3>
    <p>Faculty mentor for the Stat2Spark Mingli Innovation Laboratory. <a href="https://mp.weixin.qq.com/s/ci3yEQE8B6Om9nn7HDRXJA">View more</a></p>
    <img loading="lazy" class="cv-image-wide" src="https://cheng-bdal.github.io//images/明理创新实验室.png" alt="Stat2Spark Mingli Innovation Laboratory">
  </div>
</div>
