---
layout: archive  # 选择一个适合的布局，如 'page' 或者 'default'
permalink: /students/
title: "Students"
author_profile: true  # 可选，视需要是否显示作者信息
---

<style>
  table {
    width: 100%;
    table-layout: fixed;
    border-collapse: separate;
    border-spacing: 0 1rem;
  }
  table, tr, td {
    border: none !important;
  }
  img {
    width: min(100%, 220px);
    height: 250px;
    object-fit: cover;
    border-radius: 8px;
  }
  td {
    width: 33.333%;
    vertical-align: top;
    text-align: center;
    padding: 10px 9px;
    line-height: 1.35;
    font-size: 0.84rem;
    color: #555;
  }
  .student-name {
    display: inline-block;
    margin-top: 0.45rem;
    color: #222;
    font-size: 0.98rem;
    font-weight: 700;
  }
  td a {
    display: inline-block;
    margin-left: 0.25rem;
    padding: 0.08rem 0.38rem;
    border: 1px solid #d8c8bf;
    border-radius: 999px;
    background: #fff;
    font-size: 0.76rem;
    font-weight: 600;
    color: #8b1e2d;
    line-height: 1.35;
    text-decoration: none;
  }
  td a:hover {
    background: #f7e6e6;
    text-decoration: none;
  }
  .student-email {
    color: #777;
    font-size: 0.78rem;
  }
  .student-jump {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin: 0.25rem 0 1.1rem;
  }
  .student-jump a {
    display: inline-block;
    margin-left: 0;
    padding: 0.28rem 0.6rem;
    border: 1px solid #d8c8bf;
    border-radius: 6px;
    background: #fbfaf8;
    color: #8b1e2d;
    font-size: 0.82rem;
    font-weight: 700;
    text-decoration: none;
  }
  .student-jump a:hover {
    background: #f7e6e6;
    text-decoration: none;
  }
  .student-jump .jump-count {
    display: inline-block;
    margin-left: 0.32rem;
    padding: 0 0.32rem;
    border-radius: 999px;
    background: #f4eeee;
    color: #7a4b4b;
    font-size: 0.7rem;
    font-weight: 700;
    line-height: 1.45;
  }
  .student-grid tr {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.85rem;
    margin-bottom: 0.85rem;
  }
  .student-grid td {
    display: block;
    width: auto;
    min-height: 100%;
    padding: 0.85rem 0.75rem;
    border: 1px solid #e6e0dc !important;
    border-left: 3px solid #8b1e2d !important;
    border-radius: 6px;
    background: #fbfaf8;
  }
  .student-grid td:empty {
    display: none;
  }
  .student-grid img {
    width: min(100%, 190px);
    height: 218px;
  }
  .alumni-story {
    border-spacing: 0 0.95rem;
  }
  .alumni-story tr {
    display: grid;
    grid-template-columns: 0.88fr 1fr 1fr;
    gap: 0.75rem;
    padding: 0.78rem;
    border: 1px solid #e6e0dc;
    border-left: 3px solid #8b1e2d;
    border-radius: 6px;
    background: #fbfaf8;
  }
  .alumni-story td {
    display: block;
    width: auto;
    padding: 0;
    background: transparent;
    color: #555;
  }
  .alumni-story td:first-child {
    padding-right: 0.35rem;
    border-right: 1px solid #eadfd8 !important;
  }
  .alumni-story img {
    width: 100%;
    max-width: 220px;
    height: 185px;
    object-fit: cover;
  }
  @media (max-width: 1024px) and (min-width: 721px) {
    table,
    tbody {
      display: block;
      width: 100%;
    }
    tr {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.85rem;
      margin-bottom: 0.85rem;
    }
    td {
      display: block;
      width: auto;
      padding: 0.85rem 0.75rem;
      border: 1px solid #e6e0dc !important;
      border-radius: 6px;
      background: #fff;
    }
    td:empty {
      display: none;
    }
    .alumni-story tr {
      grid-template-columns: 1fr 1fr;
    }
    .alumni-story td:first-child {
      grid-column: 1 / -1;
      padding-right: 0;
      padding-bottom: 0.7rem;
      border-right: 0 !important;
      border-bottom: 1px solid #eadfd8 !important;
    }
  }
  @media (max-width: 720px) {
    table,
    tbody,
    tr,
    td {
      display: block;
      width: 100%;
    }
    table {
      border-spacing: 0;
    }
    tr {
      margin: 0;
    }
    td {
      margin: 0 0 0.8rem;
      padding: 0.8rem 0.75rem;
      border: 1px solid #e6e0dc !important;
      border-radius: 6px;
      background: #fff;
      font-size: 0.82rem;
    }
    td:empty {
      display: none;
    }
    table img {
      width: min(100%, 180px);
      height: 210px;
    }
    .student-name {
      font-size: 0.95rem;
    }
    .student-email {
      overflow-wrap: anywhere;
    }
    .student-grid tr,
    .alumni-story tr {
      display: block;
      padding: 0;
      border: 0;
      background: transparent;
    }
    .student-grid img,
    .alumni-story img {
      width: min(100%, 180px);
      height: 210px;
    }
    .alumni-story td:first-child {
      padding-right: 0.75rem;
      border-right: 1px solid #e6e0dc !important;
    }
  }
</style>


<nav class="student-jump" aria-label="Team section navigation">
  <a href="#current-phd">Current Ph.D.<span class="jump-count">15</span></a>
  <a href="#current-ms-undergraduate">Current M.S. / Undergraduate<span class="jump-count">10</span></a>
  <a href="#graduated-phd">Graduated Ph.D.<span class="jump-count">3</span></a>
  <a href="#graduated-ms">Graduated M.S. +<span class="jump-count">7</span></a>
</nav>

## Current Ph.D. Students
{: #current-phd }

<table class="student-grid">
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/黄君烈.jpg" alt="Junlie Huang"><br><strong class="student-name">Junlie Huang</strong><a href="https://junlie22.github.io/">Website</a><br>PhD candidate (2022)<br>Joint advisor: Associate Professor Shaojun Guo<br>BS: Tsinghua University<br>Mathematics and Applied Mathematics<br><span class="student-email">hjl22 at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/朱珺.png" alt="Jun Zhu"><br><strong class="student-name">Jun Zhu</strong><a href="https://dfsxzj.github.io/homepage/">Website</a><br>PhD candidate (2022)<br>BS: Southeast University<br>School of Mathematics<br><span class="student-email">dfsxzj at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/杜承朔.jpg" alt="Chengshuo Du"><br><strong class="student-name">Chengshuo Du</strong><a href="https://chengshuodu.github.io/">Website</a><br>PhD candidate (2023)<br>Joint advisor: Associate Professor Shaojun Guo<br>BS: Beijing University of Aeronautics and Astronautics<br>School of Mathematics<br><span class="student-email">duchengshuo at ruc dot edu dot cn</span></td>
  </tr>
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/欧阳夏雪.jpg" alt="Xiaxue Ouyang"><br><strong class="student-name">Xiaxue Ouyang</strong><a href="https://xiaxueouyang2001.github.io/">Website</a><br>PhD candidate (2023)<br>Joint advisor: Associate Professor Kejun He<br>BS: Wuhan University<br>School of Mathematics<br><span class="student-email">ouyangxiaxue at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/王涛.jpg" alt="Tao Wang"><br><strong class="student-name">Tao Wang</strong><a href="https://taowang0105.github.io/">Website</a><br>PhD candidate (2023)<br>BS: Tianjin University<br>School of Mathematics<br><span class="student-email">wang_tao at ruc dot edu dot cn</span></td>
    <!-- <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/金贝宁.jpg" alt="Beining Jin"><br>Beining Jin<br>PhD candidate (2024)<br>BS: Beijing University of Technology<br>School of Science<br>Jinbeining at foxmail dot com</td> -->
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/林俊一.jpg" alt="Junyi Lin"><br><strong class="student-name">Junyi Lin</strong><a href="https://junyilin559.github.io/">Website</a><br>PhD candidate (2024)<br>Joint advisor: Associate Professor Kejun He<br>BS: Nankai University<br>School of Statistics and Data Science<br><span class="student-email">junyilin at ruc dot edu dot cn</span></td>
  </tr>
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/王培泽.jpg" alt="Peize Wang"><br><strong class="student-name">Peize Wang</strong><br>PhD candidate (2024)<br>BS: Xiamen University<br>School of Mathematical Sciences<br><span class="student-email">wpz2024 at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/薛敦耀.jpg" alt="Dunyao Xue"><br><strong class="student-name">Dunyao Xue</strong><a href="https://sapphirexdy.github.io/">Website</a><br>PhD candidate (2024)<br>Joint advisor: Associate Professor Wenlin Dai<br>BS: Lanzhou University<br>Cuiying Honors College<br><span class="student-email">xuedunyao1202 at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/董雨铮.jpg" alt="Yuzheng Dong"><br><strong class="student-name">Yuzheng Dong</strong><br>PhD candidate (2025)<br>BS: Beijing Normal University<br>School of Mathematical Sciences<br><span class="student-email">dongyz0514 at ruc dot edu dot cn</span></td>
  </tr>
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/向智鹏.jpg" alt="Zhipeng Xiang"><br><strong class="student-name">Zhipeng Xiang</strong><br>PhD candidate (2025)<br>BS: Nankai University<br>School of Statistics and Data Science<br><span class="student-email">ycx_lives at 163 dot com</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/李泽.jpg" alt="Ze Li"><br><strong class="student-name">Ze Li</strong><br>PhD candidate (2025)<br>Joint advisor: Researcher Zhang Jingyi<br>BS: Zhengzhou University<br><span class="student-email">li.ze at bupt dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/张宇飞.jpg" alt="Yufei Zhang"><br><strong class="student-name">Yufei Zhang</strong><br>PhD candidate (2025)<br>Joint advisor: Researcher Zhang Jingyi<br>BS: Yanshan University<br><span class="student-email">2025010723 at bupt dot cn</span></td>
  </tr>
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/白静言.jpg" alt="Jingyan Bai"><br><strong class="student-name">Jingyan Bai</strong><br>PhD candidate (2026)<br>BS: Tsinghua University<br>Department of Mathematical Sciences<br><span class="student-email">1577217284 at qq dot com</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/李雨凝.jpg" alt="Yuning Li"><br><strong class="student-name">Yuning Li</strong><br>PhD candidate (2026)<br>Joint advisor: Researcher Zhang Jingyi<br>BS: Huazhong Agricultural University, Information and Computing Science<br><span class="student-email">13204761705 at 163 dot com</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/刘可欣.jpg" alt="Kexin Liu"><br><strong class="student-name">Kexin Liu</strong><br>PhD candidate (2026)<br>Joint advisor: Researcher Zhang Jingyi<br><span class="student-email">kxliu2025 at bupt dot cn</span></td>
  </tr>
</table>

## Current M.S. and Undergraduate Students
{: #current-ms-undergraduate }

<table class="student-grid">
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/梁浩贤.jpg" alt="Haoxian Liang"><br><strong class="student-name">Haoxian Liang</strong><a href="https://haoxian1024.github.io/">Website</a><br>M.S. (2024)<br>BS: Renmin University of China<br>School of Mathematical Sciences<br><span class="student-email">haoxian_liang at mail dot bnu dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/胡婧璇.jpg" alt="Jingxuan Hu"><br><strong class="student-name">Jingxuan Hu</strong><br>M.S. (2025)<br>BS: Beijing Jiaotong University<br>School of Economics and Management<br><span class="student-email">2025104242 at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/蒋文浩.jpg" alt="Wenhao Jiang"><br><strong class="student-name">Wenhao Jiang</strong><br>M.S. (2025)<br>BS: Renmin University of China<br>School of Mathematics<br><span class="student-email">2021201382 at ruc dot edu dot cn</span></td>
  </tr>
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/吕佳迪.jpg" alt="Jiadi Lv"><br><strong class="student-name">Jiadi Lv</strong><br>M.S. (2025)<br>BS: Zhongnan University of Economics and Law<br>School of Statistics and Mathematics<br><span class="student-email">2025104254 at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/王政博.jpg" alt="Zhengbo Wang"><br><strong class="student-name">Zhengbo Wang</strong><br>M.S. (2025)<br>BS: Dongbei University of Finance and Economics<br>School of Accounting<br><span class="student-email">2025104259 at ruc dot edu dot cn</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/陈佳丰.jpg" alt="Jiafeng Chen"><br><strong class="student-name">Jiafeng Chen</strong><br>M.S. (2025)<br>Joint advisor: Researcher Zhang Jingyi<br>BS: Shanxi University of Finance and Economics, Statistics<br><span class="student-email">2025111691 at bupt dot cn</span></td>
  </tr>
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/郝卓轩.jpg" alt="Zhuoxuan Hao"><br><strong class="student-name">Zhuoxuan Hao</strong><br>M.S. (2026)<br>Joint advisor: Researcher Zhang Jingyi<br>BS: Hunan Normal University<br>Mathematics and Applied Mathematics<br><span class="student-email">m17835179527 at 163 dot com</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/罗茜.jpg" alt="Qian Luo"><br><strong class="student-name">Qian Luo</strong><br>M.S. (2026)<br>Joint advisor: Researcher Zhang Jingyi<br><span class="student-email">2867202110 at qq dot com</span></td>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/蒋璇.jpg" alt="Xuan Jiang"><br><strong class="student-name">Xuan Jiang</strong><br>Undergraduate (2024)<br>Joint advisor: Researcher Zhang Jingyi<br>BS: Beijing University of Posts and Telecommunications, School of Mathematics<br><span class="student-email">2024212523 at bupt dot cn</span></td>
  </tr>
  <tr>
    <td><img loading="lazy" src="https://cheng-bdal.github.io//images/头像/朱同臣.jpg" alt="Tongchen Zhu"><br><strong class="student-name">Tongchen Zhu</strong><br>Undergraduate (2024)<br>Joint advisor: Researcher Zhang Jingyi<br>Beijing University of Posts and Telecommunications, Digital Media Technology<br><span class="student-email">2024213885 at bupt dot cn</span></td>
    <td></td>
    <td></td>
  </tr>
</table>

## Graduated PhD Students
{: #graduated-phd }
<style>
  img {
    width: min(100%, 220px);
    height: 250px;
    object-fit: cover;
    border-radius: 8px;
    vertical-align: top;
  }
</style>

<table class="alumni-story">
  <tr>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/头像/康欣来.jpg" alt="Xinlai Kang"><br>
      <strong class="student-name">Xinlai Kang</strong><a href="https://kxlkxl1999.github.io/">Website</a><br>
      PhD (2026)<br>
      BS: Renmin University of China<br>
      School of Statistics<br>
      <span class="student-email">kangxinlai at ruc dot edu dot cn</span>
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/康欣来毕业照/康欣来毕业照1.jpg" alt="Xinlai Kang"><br>
      Graduation Message: Take a broad and long-term view.<br>
      <br>
      <br>
      <br>
      <br>
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/康欣来毕业照/康欣来毕业照2.jpg" alt="Xinlai Kang"><br>
      Graduation Commemoration on May 28, 2026<br>
      Next affiliation: Huawei Central Research Institute<br>
      Foundation Model Laboratory<br>
      <br>
      <br>
    </td>
  </tr>
  <tr>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/头像/李梦雨.jpg" alt="Mengyu Li"><br>
      <strong class="student-name">Mengyu Li</strong><a href="https://mengyu8042.github.io/">Website</a><br>
      PhD (2025)<br>
      BS: Beijing Normal University<br>
      School of Mathematics<br>
      <span class="student-email">mengyuli (at) tsinghua.edu.cn</span>
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/李梦雨毕业照/李梦雨毕业照1.jpg" alt="Mengyu Li"><br>
    Graduation Message: Nothing is impossible to a willing heart.<br>
    <br>
    <br>
    <br>
    <br>
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/李梦雨毕业照/李梦雨毕业照2.jpg" alt="Mengyu Li"><br>
      Graduation Commemoration on May 16, 2025<br>
      Shuimu Scholar, Department of Statistics, Tsinghua University<br>
      <br>
      <br>
      <br>
    </td>
  </tr>
  <tr>
    <td>
     <img loading="lazy" src="https://cheng-bdal.github.io//images/头像/李涛.jpg" alt="Tao Li"><br>
      <strong class="student-name">Tao Li</strong><a href="https://github.com/sherlockLitao">Website</a><br>
      PhD (2024)<br>
      Nanjing University<br>
      Department of Mathematics<br>
      <span class="student-email">lt1306516392 at gmail dot com</span>
    </td>
    <td>
    <img loading="lazy" src="https://cheng-bdal.github.io//images/李涛毕业礼物.jpg" alt="Tao Li"><br>
    Graduation Message: The iron pass was daunting, yet now we begin anew with confident steps.<br>
    <br>
    <br>
    <br>
    <br>
    </td>
    <td>
    <img loading="lazy" src="https://cheng-bdal.github.io//images/李涛毕业照.jpg" alt="Tao Li"><br>
    Graduation Commemoration on May 17, 2024<br>
    Next affiliation: China Galaxy Securities<br>
    <br>
    <br>
    <br>
    </td>
  </tr>
</table>

## Graduated M.S. Students
{: #graduated-ms }
<table class="alumni-story">
  <tr>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/头像/黄倩楠.jpg" alt="Qiannan Huang"><br>
      <strong class="student-name">Qiannan Huang</strong><br>
      M.S. (2025)<br> 
      BS: Tianjin University<br>
      School of Mathematics<br>
      <span class="student-email">joliarbre99 at gmail dot com</span>
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/黄倩楠毕业照/黄倩楠毕业照1.jpg" alt="Qiannan Huang"><br>
      Graduation Message: Success begins with the right direction.<br>
      Special Thanks：<a href="https://space.bilibili.com/652096797?spm_id_from=333.337.0.0">我是超人CR</a><br>
      <br>
      <br>
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/黄倩楠毕业照/黄倩楠毕业照2.jpg" alt="Qiannan Huang"><br>
      Graduation Commemoration on May 25, 2025<br>
      Next affiliation:<br>
      HKU Business School<br>
      Graduation Message: <a href="https://mp.weixin.qq.com/s/JjcNgioFblkL_FJBtw1wbw">Link</a>
      <br>
      <br>
    </td>
  </tr>
  <tr>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/头像/曾贺舵.jpg" alt="Geduo Zeng"><br>
      <strong class="student-name">Geduo Zeng</strong><br>
      M.S. (2026)<br>
      BS: Wuhan University<br>
      School of Mathematics
      <!-- geduo zeng at ruc dot edu dot cn -->
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/头像/郑浩.jpg" alt="Hao Zheng"><br>
      <strong class="student-name">Hao Zheng</strong><br>
      M.S. (2026)<br>
      BS: Shandong University<br>
      School of Mathematics
      <!-- 2023103362 at ruc dot edu dot cn -->
    </td>
    <td>
      <img loading="lazy" src="https://cheng-bdal.github.io//images/头像/柳欣怡.jpg" alt="Xinyi Liu"><br>
      <strong class="student-name">Xinyi Liu</strong><br>
      Undergraduate (2025)<br>
      Renmin University of China<br>
      Business School<br>
      <span class="student-email">guyu04202025 at gmail dot com</span><br>
      Next affiliation:<br>
      University of Georgia<br>
      <br>
    </td>
  </tr>
</table>


- Xitong Wei (M.S., 2022, Meituan)
- Dianjun Lin (M.S., 2022, PhD student at The Pennsylvania State University)
- Xin Wang (M.S., 2022, PhD student at University of Washington)





