---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![Photo](../files/实验室合照.jpg)


About BDAL-RUC
======
<div class="profile-intro" markdown="1">

Hi! I’m Cheng Meng, a tenure-track Assistant Professor and Ph.D. advisor at the School of Statistics and Data Science, Renmin University of China (RUC). My research centers on big data statistics, optimal transport, artificial intelligence, and industrial statistics. I am particularly interested in statistically principled methods for complex computational and modeling problems in real applications.

I received my B.S. in Mathematics from Tsinghua University and my Ph.D. in Statistics from the University of Georgia. During my doctoral study, I was fortunate to be advised by Prof. <a href="https://bdalpingio.github.io/">Ping Ma</a> and Prof. <a href="https://zhonglabuga.github.io/">Wenxuan Zhong</a>, who co-direct the Big Data Analytics Lab (BDAL) at UGA. After joining RUC, I have been building BDAL-RUC together with a group of talented, sincere, and highly motivated students. Group members have received major honors including the Wu Yuzhang Scholarship (RUC's highest student honor), JSM Student Paper Awards, and National Graduate Scholarships.

Our work is grounded in statistical theory and closely connected to real-world applications. In recent years, the group has worked on scalable algorithms for large-scale data analysis, fast methods for optimal transport, industrial data modeling, and AI-related statistical methods, with active collaborations including projects with Huawei. I received the 2023 Junior Researcher Award from the Pan-Asian Committee for Statistical Research, and our team has won the Huawei Spark Award three times for solving major industrial challenges. Our goal is to develop reliable, efficient, and practically useful statistical and machine learning methods for industrial and interdisciplinary scientific problems.

</div>

## Featured Reports

<style>
  .page__content > p:first-of-type img {
    width: 100%;
    height: auto;
    border-radius: 6px;
  }
  .profile-intro p {
    margin: 0 0 0.55rem;
    text-align: justify;
    line-height: 1.55;
  }

  .page__content > h1,
  .page__content > h2 {
    margin: 1.45rem 0 0.65rem;
    padding-bottom: 0.35rem;
    border-bottom: 1px solid #eadfd8;
    font-size: 1.35rem;
    line-height: 1.25;
    letter-spacing: 0;
  }
  .page__content > h1:first-of-type {
    margin-top: 0.85rem;
  }

  .highlight-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.8rem;
    margin: 0.2rem 0 1.1rem;
  }
  .highlight-grid a {
    display: block;
    padding: 0.65rem;
    border: 1px solid #e7e0da;
    border-left: 3px solid #8b1e2d;
    border-radius: 6px;
    background: #fbfaf8;
    color: inherit;
    text-decoration: none;
    transition: background 0.15s ease, border-color 0.15s ease;
  }
  .highlight-grid a:hover {
    background: #f7f1ee;
    border-color: #d8c8bf;
  }
  .highlight-grid a:hover span {
    background: #f7e6e6;
    border-color: #cfa5a5;
    text-decoration: none;
  }
  .highlight-grid img {
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    border-radius: 5px;
  }
  .highlight-grid span {
    display: inline-block;
    max-width: 100%;
    margin-top: 0.45rem;
    padding: 0.12rem 0.48rem;
    border: 1px solid #d8c8bf;
    border-radius: 999px;
    background: #fff;
    color: #8b1e2d;
    font-size: 0.78rem;
    font-weight: 700;
    line-height: 1.45;
    white-space: normal;
    overflow-wrap: anywhere;
  }

  .news-list {
    display: grid;
    gap: 0.72rem;
    margin: 0.2rem 0 1rem;
  }
  .news-card {
    padding: 0.75rem 0.85rem;
    border: 1px solid #e7e0da;
    border-left: 3px solid #8b1e2d;
    border-radius: 6px;
    background: #fbfaf8;
  }
  .news-card p {
    margin: 0.35rem 0 0;
    line-height: 1.65;
  }
  .news-card a {
    display: inline-block;
    float: right;
    margin: 0.06rem 0 0.15rem 0.55rem;
    padding: 0.12rem 0.48rem;
    border: 1px solid #d8c8bf;
    border-radius: 999px;
    background: #fff;
    color: #8b1e2d;
    font-size: 0.78rem;
    font-weight: 700;
    line-height: 1.45;
    text-decoration: none;
    white-space: nowrap;
  }
  .news-card p::after {
    content: "";
    display: block;
    clear: both;
  }
  .news-card a:hover {
    background: #f7e6e6;
    border-color: #cfa5a5;
    text-decoration: none;
  }
  .news-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    align-items: center;
    font-size: 0.75rem;
    letter-spacing: 0;
    text-transform: uppercase;
  }
  .news-date {
    color: #555;
    font-weight: 700;
  }
  .news-tag {
    padding: 0.1rem 0.42rem;
    border-radius: 999px;
    font-size: 0.72rem;
    font-weight: 700;
    line-height: 1.35;
  }
  .news-tag--papers {
    background: #f7e6e6;
    color: #9b1c24;
  }
  .news-tag--awards {
    background: #f6edcf;
    color: #7a5400;
  }
  .news-tag--projects {
    background: #e4f1e8;
    color: #1f6b3a;
  }
  .news-tag--team {
    background: #e4edf7;
    color: #24527a;
  }
  .news-tag--media {
    background: #e8ecef;
    color: #4a5964;
  }

  .news-more {
    margin-top: 0.8rem;
  }
  .news-more-toggle {
    display: inline-block;
    padding: 0.38rem 0.72rem;
    border: 1px solid #d8c8bf;
    border-radius: 999px;
    background: #fbfaf8;
    cursor: pointer;
    color: #8b1e2d;
    font: inherit;
    font-weight: 600;
  }
  .news-more-toggle:hover {
    background: #f7e6e6;
  }
  .news-year-heading {
    margin: 0.85rem 0 0.45rem;
    color: #555;
    font-size: 0.98rem;
  }
  @media (max-width: 720px) {
    .page__content > p:first-of-type img {
      max-height: 46vh;
      object-fit: cover;
      object-position: center;
    }
    .profile-intro p {
      text-align: left;
    }
    .page__content > h1,
    .page__content > h2 {
      margin: 1.12rem 0 0.5rem;
      font-size: 1.18rem;
    }
    .highlight-grid {
      grid-template-columns: 1fr;
      gap: 0.55rem;
    }
    .highlight-grid a {
      display: grid;
      grid-template-columns: 5.6rem minmax(0, 1fr);
      gap: 0.65rem;
      align-items: center;
      padding: 0.55rem 0.62rem;
    }
    .highlight-grid img {
      aspect-ratio: 4 / 3;
      border-radius: 5px;
    }
    .highlight-grid span {
      margin-top: 0;
      padding: 0;
      border: 0;
      border-radius: 0;
      background: transparent;
      font-size: 0.82rem;
      line-height: 1.45;
    }
    .highlight-grid a:hover span {
      background: transparent;
      border-color: transparent;
    }
    .news-list {
      gap: 0.55rem;
      margin-bottom: 0.75rem;
    }
    .news-card {
      padding: 0.58rem 0.68rem;
      border-radius: 5px;
    }
    .news-card p {
      line-height: 1.52;
    }
    .news-card a {
      margin: 0.12rem 0 0.1rem 0.5rem;
    }
    .news-meta {
      gap: 0.32rem;
      font-size: 0.7rem;
    }
    .news-tag {
      padding: 0.08rem 0.34rem;
      font-size: 0.68rem;
    }
  }
</style>

<div class="highlight-grid">
  <a href="https://mp.weixin.qq.com/s/jtmVn6od7OL0Z7EPplROpQ">
    <img loading="lazy" src="https://cheng-bdal.github.io//images/赛道.jpg" alt="Huawei Feature: Cheng Meng's Third Spark Award">
    <span>Huawei Feature: Cheng Meng's Third Spark Award →</span>
  </a>
  <a href="https://mp.weixin.qq.com/s/bSx9Vl2pe-LEdYZdeyDGRQ">
    <img loading="lazy" src="https://cheng-bdal.github.io//images/新生讲话.jpg" alt="RUC Feature: Faculty Speech at the Opening Ceremony">
    <span>RUC Feature: Faculty Speech at the Opening Ceremony →</span>
  </a>
  <a href="https://mp.weixin.qq.com/s/OQwr1EvCYTcqG4Tm2Yl84Q">
    <img loading="lazy" src="https://cheng-bdal.github.io//images/清华校友.jpg" alt="Tsinghua Alumni Feature: Cheng Meng's Story">
    <span>Tsinghua Alumni Feature: Cheng Meng's Story →</span>
  </a>
</div>

## Latest News

<div class="news-list">
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-06</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>Two BDAL-RUC papers have been accepted by STAI-X.</strong> Congratulations to Jun Zhu et al. for "SSP-Ensemble: A Sufficient Subspace Projection Ensemble for Multiclass Classification" and Peize Wang et al. for "KPOTD: Kernel Principal Optimal Transport Directions for Nonlinear Sufficient Dimension Reduction," both accepted by the inaugural STAI-X conference.</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-06</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>A new Mingli College project begins.</strong> Junlie Huang's project "Research on High-Precision Fault Early-Warning Algorithms Based on Statistics" has been approved as a Renmin University of China Mingli College "Qiushi Graduate Education Research" project. <a href="https://mp.weixin.qq.com/s/RctY4tEAfXxE1zw6Io4I-g">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-06</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>Four student projects won institute-level support.</strong> Projects by Tao Wang, Junlie Huang, Dunyao Xue, and Chengshuo Du were approved as 2026 Graduate Student Scientific Research Fund Projects of the Institute of Statistics and Big Data, among 8 awardees institute-wide.</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-05</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>Another group paper has been accepted by JCGS.</strong> Congratulations to Junyi Lin et al. on "Sparsification Subsampling for Partial Least Squares Regression" being accepted by JCGS. <a href="https://mp.weixin.qq.com/s?__biz=MzI0NTE1MDk4Mg==&mid=2247493940&idx=1&sn=3f41517b696d31773e31a21693ad8c35&chksm=e8f6112b10b60af59a6e06b2b853b016819e8df11bd3e59f74027f2f0f3b6a7008093539b5aa&mpshare=1&scene=1&srcid=0612HIgIPk4SNGTgunx3oLYC&sharer_shareinfo=9485eab15d920ade4b142f3ec70593ac&sharer_shareinfo_first=9485eab15d920ade4b142f3ec70593ac#rd">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-05</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>Our improved MoE work has been accepted by ICML 2026.</strong> Congratulations to Xinlai Kang, Dunyao Xue, Zhengbo Wang, Chengshuo Du et al. on "Breaking the Echo Chamber: A Dynamic Ensemble Pruning Perspective on MoE," also featured by the well-known machine learning public account "Machine Heart" (Ji Qi Zhi Xin). <a href="https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2651034543&idx=2&sn=8c0a91d51644de87618d0cdd9585429d">Read more →</a></p>
  </article>
</div>

<div class="news-more">
  <button type="button" class="news-more-toggle" onclick="var target=document.getElementById('more-news-list'); target.hidden=!target.hidden; this.textContent=target.hidden?'Show More News':'Show Less News';">Show More News</button>
  <div id="more-news-list" hidden>

<h3 class="news-year-heading">2026</h3>

<div class="news-list">
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-05</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>A teaching innovation project received a Beijing municipal award.</strong> Cheng Meng participated in "Building a New Campus-Wide Academy System to Create a 'Three-Span, Three-Exchange, Three-Learning' Ecosystem for Future Talent Development," which won the Second Prize of the Beijing Higher Education Teaching Achievement Award. <a href="https://mp.weixin.qq.com/s/tblNY71IJZHax3ybNhkG0A">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-04</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Four students brought home Travel Awards.</strong> Congratulations to Tao Wang, Chengshuo Du, Xiaxue Ouyang, and Junyi Lin for winning the Travel Award at the 1st "Mao Shisong Statistical Education Doctoral Forum." <a href="https://mp.weixin.qq.com/s?__biz=MzI0NTE1MDk4Mg==&mid=2247493720&idx=1&sn=33806c9917daa341d2b28715e7154461">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-03</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>The core-elements subsampling work has been accepted by JCGS.</strong> Congratulations to Dunyao Xue et al. on "Core-elements Subsampling for Alternating Least Squares" being accepted by JCGS. <a href="https://mp.weixin.qq.com/s?__biz=MzI0NTE1MDk4Mg==&mid=2247493684&idx=1&sn=2890bbd35e47576683e9019d532ff71d&chksm=e8c4425f7136d1bed9b4acf814b19ef8179428e79e09fa51e30af3cdfa9842fd2b54290b4c16&mpshare=1&scene=1&srcid=0414OajaNWC2FQBekHecF670&sharer_shareinfo=bcb12df34a4a3d6bd935ea3dc2d09229&sharer_shareinfo_first=bcb12df34a4a3d6bd935ea3dc2d09229#rd">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-03</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Dunyao Xue was selected for RUC's talent training program.</strong> Congratulations on being selected for the 2025-2026 Renmin University of China "Top Innovative Talents Training Funding Program" (2 awardees institute-wide), marking the team's second such honor after Mengyu Li.</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-03</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>The team won another Huawei Spark Award.</strong> Congratulations to Jun Zhu and Cheng Meng on winning the Spark Award in Huawei's "Challenge Bounty" Issue 131 for the challenge "Online Lithium Plating Detection." <a href="https://mp.weixin.qq.com/s/aECgm4y8pQs_ImBtHJ-7Pw">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-01</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>An optimal transport sparsification paper was accepted.</strong> Congratulations to Ouyang Xiaxue et al. on their paper "Sparsification Techniques for Large-scale Optimal Transport Problems" being accepted by WIREs Computational Statistics. The work was also featured by the well-known statistics platform Capital of Statistics. <a href="https://mp.weixin.qq.com/s/f_F0dMu3QbU_GCBHDJIv4A">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-01</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>A rigid-motion-invariant metric paper was accepted by ICLR.</strong> Congratulations to Junyi Lin, Dunyao Xue, et al. on their paper "An Efficient SE(p)-Invariant Transport Metric Driven by Polar Transport Discrepancy-Based Representation" being accepted by ICLR. The work was also featured by the well-known AI media outlet Synced. <a href="https://mp.weixin.qq.com/s/JMUyM_UScUCKwxmcGBlTAQ">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-01</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>A Huawei collaboration received annual recognition.</strong> Congratulations to Cheng Meng for receiving the "Best Collaborative Team Achievement Award" from the Huawei 2012 Labs Central Research Institute for 2025!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2026-01</span><span class="news-tag news-tag--team">Team</span></div>
    <p><strong>Five students were featured in the 2025 RUC Statistics Student Profile Series.</strong> Congratulations to Mengyu Li, Junlie Huang, Chengshuo Du, Tao Wang, and Dunyao Xue, five students featured in the 2025 RUC Statistics Student Profile Series. <a href="https://mp.weixin.qq.com/s/ZAW9in5xx4kh3uWEm1sinA">Read more →</a></p>
</article>
</div>

<h3 class="news-year-heading">2025</h3>

<div class="news-list">
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-11</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Postdoctoral research received new support.</strong> Congratulations to Mengyu Li on receiving the China Postdoctoral Science Foundation！ <a href="https://mp.weixin.qq.com/s/Ziaz-dZziQIdrkS6bBu6uQ">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-11</span><span class="news-tag news-tag--team">Team</span></div>
    <p><strong>The team joined a NeurIPS offline exchange in Beijing.</strong> Congratulations to Tao Wang for being invited to attend the NeurIPS 2025 offline sharing session in Beijing and for presenting a poster. <a href="https://mp.weixin.qq.com/s/DaLrbOeDIacQ-XAorbPVGA">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-11</span><span class="news-tag news-tag--team">Team</span></div>
    <p><strong>A Tsinghua sports story was recorded and shared.</strong> Cheng Meng was selected as one of the 25 representatives of Tsinghua's sports athletes to share the growth and stories of the sports team. <a href="https://mp.weixin.qq.com/s/vy3i4iGzefxdtZy2zuq0dQ">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-11</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>A multimodal image registration paper was accepted by Pattern Recognition.</strong> Congratulations to Mengyu Li and co-authors on their paper “Iterative Optimal Transport for Multimodal Image Registration” being accepted by Pattern Recognition! This marks the 13th paper from our group published in an RUC A- class journal!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-11</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>BDAL students stood out at the CSIAM Student Forum.</strong> Congratulations to Junlie Huang, Chengshuo Du, Tao Wang and Dunyao Xue for winning Outstanding Poster Awards at the 9th CSIAM Student Forum. BDAL-RUC received the most awards among participating institutions, and the achievement was also covered by RUC News. <a href="https://mp.weixin.qq.com/s/krRC5HjTbBXFPWO6ZEP19Q">WeChat report →</a> <a href="https://news.ruc.edu.cn/1984663406100312065.html">RUC News →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-11</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Jun Zhu received a doctoral comprehensive scholarship.</strong> Congratulations to Zhu Jun for receiving the Doctoral Student Comprehensive Scholarship (only 4 recipients across the entire institute)!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-10</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Seven students received first-class graduate academic scholarships.</strong> Congratulations to Junlie Huang, Jun Zhu, Tao Wang, Xiaxue Ouyang, Junyi Lin, Dunyao Xue, and Zhipeng Xiang for receiving the First-Class Graduate Academic Scholarship from the Institute of Statistics and Big Data (awarded to the top 30% of the class)!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-10</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Stat2Spark presented at the Mingli College academic annual conference.</strong> Junlie Huang, on behalf of the Stat2Spark team, participated in the 2025 Mingli College Academic Annual Conference, received the “Outstanding Research Team Award of Mingli College” presented by President Shangli Lin, and gave a presentation at the Mingli Innovation Lab Sub-Forum showcasing the team’s latest research achievements. <a href="https://mp.weixin.qq.com/s/LEnJWeN-nbosP2ZigYn-pQ?scene=1&click_id=1">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-10</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>An undergraduate teaching project won RUC's Special Prize.</strong> Congratulations to Cheng Meng for participating in the project “Building a New Collegiate System for All Students to Foster an Innovative ‘Three Crosses, Three Integrations, and Three Learnings’ Talent Development Ecosystem for the Future”, which won the Special Prize (Undergraduate Category) of the Renmin University of China Teaching Achievement Awards!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-10</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>A postgraduate teaching project won RUC's First Prize.</strong> Congratulations to Cheng Meng for participating in the project “Construction and Practice of a ‘Big Data Statistics+’ Innovative and Interdisciplinary International Talent Training System”, which won the First Prize (Postgraduate Category) of the Renmin University of China Teaching Achievement Awards!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-09</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>An interval-valued random object paper was accepted by Statistics and Computing.</strong> Congratulations to Xinlai Kang, Xiaxue Ouyang and co-authors on their paper “Hausdorff Correlation for Interval-valued Random Objects” being accepted by Statistics and Computing! This marks the 12th paper from our group published in an RUC A- class journal!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-09</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>A 3DGS Gaussian reduction paper received a NeurIPS Spotlight.</strong> Congratulations to Tao Wang, Mengyu Li, Geduo Zeng, and co-authors on their paper "Gaussian Herding Across Pens: An Optimal Transport Perspective on Global Gaussian Reduction for 3DGS" being accepted by NeurIPS 2025 as a Spotlight. The work was also featured by the well-known AI media outlet Synced. <a href="https://mp.weixin.qq.com/s/N34W_LK0jYPrmWWtGxVp4w">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-08</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>Xiaxue Ouyang's graduate research fund project was approved.</strong> Congratulations to Xiaxue Ouyang for leading the project "Efficient Feature Selection Driven by Adaptive Subsampling and Bio-inspired Encoding Expansion and Sparse Representation Methods," which has been approved as a 2025 Graduate Scientific Research Fund Project by the Institute of Statistics and Big Data.</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-08</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>The active learning algorithm SPOT was accepted by BDMA.</strong> Congratulations to Cheng Meng and co-authors on their paper "SPOT: An Active Learning Algorithm for Efficient Deep Neural Network Training" being accepted by Big Data Mining and Analytics (IF: 13.6)!</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-07</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Mengyu Li was selected for Tsinghua University's Shuimu Scholar Program.</strong> Congratulations to Mengyu Li on being selected for Tsinghua University’s “Shuimu Scholar” Program! The “Shuimu Scholar” Program is a key initiative of Tsinghua University aimed at cultivating high-level young talents. Its goal is to foster a group of outstanding young scholars who are dedicated to academic research, innovative in spirit, socially responsible, and equipped with a global vision. The program supports no more than 100 individuals each year.</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-06</span><span class="news-tag news-tag--media">Media</span></div>
    <p><strong>Statistics outreach appeared across multiple platforms.</strong> Cheng Meng was invited to multiple platforms to introduce the statistics major and share stories from his personal growth journey. <a href="https://www.bilibili.com/video/BV1gZM1zSEKs/?spm_id_from=333.337.search-card.all.click&vd_source=e6527d198967f47b463a38a48f92d812">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-06</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><span class="news-emphasis--red"><strong>Mengyu Li received RUC's highest student honor.</strong> Congratulations to Mengyu Li on receiving the "Wu Yuzhang Scholarship," RUC's highest student honor, awarded each year to only four doctoral students. <a href="https://mp.weixin.qq.com/s/zID17NSsC8q4sK_bimLOJQ">Read more →</a></span></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-06</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>A double optimal transport paper was accepted by Bioinformatics.</strong> Congratulations to Mengyu Li and co-authors on their paper "Double Optimal Transport for Differential Gene Regulatory Network Inference with Unpaired Samples" being accepted by Bioinformatics in June 2025! This is the group's 11th paper in an RUC Class A- journal.</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-05</span><span class="news-tag news-tag--team">Team</span></div>
    <p><strong>Mengyu Li and Qiannan Huang successfully passed their thesis defenses.</strong> Congratulations to Dr. Mengyu Li and Qiannan Huang. May they carry confidence, perseverance, and idealism into the next stage.</p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-05</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>A leverage-score approximation paper was accepted by JCGS.</strong> Congratulations to Junlie Huang, Xinlai Kang, Qiannan Huang, and others on their paper "Efficient Approximation of Leverage Scores in Two-dimensional Autoregressive Models with Application to Image Anomaly Detection" being accepted by JCGS! This marks the 9th paper from our group published in a Category 1B journal of the Research Institute!
<a href="https://mp.weixin.qq.com/s/68Qa5Yv9DNXlm035fzIhjQ">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-05</span><span class="news-tag news-tag--media">Media</span></div>
    <p><span class="news-emphasis--red"><strong>Cheng Meng spoke as a Tsinghua alumnus ten years after graduation.</strong> Cheng Meng was invited to speak at a Tsinghua alumni symposium, with additional coverage by the Department of Statistics and Data Science. <a href="https://mp.weixin.qq.com/s/d8KrSRIqVNIQVdvBO0yjFw">Event report →</a> <a href="https://mp.weixin.qq.com/s/utOxnb63ZurO7jPo6NpkAg">Department report →</a></span></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-04</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Three students received Travel Awards at the doctoral forum.</strong> Congratulations to Junyi Lin, Junlie Huang and Dunyao Xue for receiving the Travel Award and being selected for the Doctoral Forum at the 2025 Annual Conference of the Youth Statisticians Association of the National Industrial Statistics Teaching and Research Association and the 3rd International Symposium on Statistical Theory and its Applications, with additional coverage by the academic platform "Gouxiong Hui". <a href="https://mp.weixin.qq.com/s/ko2HoiA6hpjWPdyo8Q8E-g">Forum report →</a> <a href="https://mp.weixin.qq.com/s/secOUhCJQb0NYumfMlM5qQ">Platform report →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-03</span><span class="news-tag news-tag--projects">Projects</span></div>
    <p><strong>The team won Huawei's Spark Award for the third time.</strong> Congratulations to Cheng Meng for leading students Hao Zheng, Tao Wang, Haoxian Liang, and Mengyu Li to win the Huawei "Challenge Solving" 114th Spark Award. This is the team's third time receiving this honor; Haoxian Liang was also interviewed by Mingli College. <a href="https://mp.weixin.qq.com/s/NXFraboslDTdyHaGAFEjFA">Huawei report →</a> <a href="https://mp.weixin.qq.com/s/0SyJYpWQNhOvDi2sjYaxOg">My Spark Moments →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2025-03</span><span class="news-tag news-tag--papers">Papers</span></div>
    <p><strong>A hyperbolic Wasserstein distance paper was accepted by IEEE TNNLS.</strong> Congratulations! The paper "Efficient Variants of Wasserstein Distance in Hyperbolic Space via Space-filling Curve Projection" by Tao Li, Jun Zhu, and others has been accepted by IEEE TNNLS (IF: 10.2)! This is the third 1A-class journal publication from our group at the research institute!
<a href="https://mp.weixin.qq.com/s/1LUVaZowmOd9oIREQAScgA">Read more →</a></p>
</article>
</div>

<h3 class="news-year-heading">2024</h3>

<div class="news-list">
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2024-12</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Mengyu Li was selected for the CAST Young Talent Support Program.</strong> Congratulations to Mengyu Li on being selected for the 2024 CAST Young Talent Support Program for Doctoral Students, supported by CAAS. <a href="https://mp.weixin.qq.com/s/rRtjWDszTF0U0GonVTHsRA">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2024-11</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Qiannan Huang received a JD Scholarship nomination.</strong> Congratulations! Qiannan Huang has been awarded the JD Scholarship Nomination.
<a href="https://mp.weixin.qq.com/s/yr_M4j9BJM41Ku5_H25O0Q">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2024-11</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Qiannan Huang received a National Scholarship.</strong> Congratulations! Qiannan Huang has been awarded the National Scholarship for Master's Students in the 2024 Student Award Review! This is BDAL Lab's third National Scholarship, following the 2023 Doctoral National Scholarship awarded to Mengyu Li and the 2021 Master's National Scholarship awarded to Dianjun Lin. <a href="https://cheng-bdal.github.io//images/黄倩楠国奖.jpg">Read more →</a></p>
  </article>
  <article class="news-card">
    <div class="news-meta"><span class="news-date">2024-10</span><span class="news-tag news-tag--awards">Awards</span></div>
    <p><strong>Mengyu Li received a CSIAM Outstanding Poster Award.</strong> Congratulations! Mengyu Li was awarded the Outstanding Poster Award at the 22nd Annual Conference of the China Society for Industrial and Applied Mathematics. <a href="https://mp.weixin.qq.com/s/ffKNLItqx5vv-P0r3Yd2QQ">Read more →</a></p>
</article>
</div>
</div>
</div>
