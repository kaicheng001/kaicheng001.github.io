---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
   - /about/
   - /about.html
---

<style>
/* Georgia字体样式设置 */
body, p, li, .page__content, .archive__item-excerpt, 
.page__meta, .page__lead, .publication__item, .news__item {
  font-family: 'Georgia', serif !important;
  font-size: 1.05rem;
  line-height: 1.7;
  color: #333;
}

.page__content p {
  letter-spacing: 0.01em;
  margin-bottom: 1.2em;
}

blockquote {
  font-family: 'Georgia', serif !important;
  font-style: italic;
}

/* 保持标题字体不变或设置为衬线字体 */
h1, h2, h3, h4, h5, h6 {
  font-weight: 600;
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a fourth-year undergraduate student majoring in Artificial Intelligence at Southeast University, and an incoming master's student at the School of Information Science and Technology, University of Science and Technology of China, advised by Prof. [Jiajun Deng](https://djiajunustc.github.io/) and Prof. [Wengang Zhou](http://staff.ustc.edu.cn/~zhwg/).

My research interests lie broadly in computer vision and machine learning, with a current focus on:
- **Embodied AI**
- **World Models**

I enjoy exploring open problems at the frontier of AI, with a strong emphasis on practical, hands-on implementation. Beyond academia, I am an enthusiastic advocate for open-source software and the collaborative culture it cultivates.


# 🔥 News
- *2025.05*: &nbsp;🔥🔥  We present the paper: <b><em>Table-r1</em>: Self-supervised and Reinforcement Learning for Program-based Table Reasoning in Small Language Models</b>.

# 📝 Publications


<div style="display: flex; align-items: flex-start; gap: 28px; margin: 20px 0 28px 0;">
  <div style="position: relative; display: inline-block;">
    <!-- 比例自适应，最大宽高限制 -->
    <img src="/images/table-r1_overview.png"
         alt="Table-r1"
         style="max-width: 360px; max-height: 270px; width: auto; height: auto; border-radius: 7px; box-shadow: 0 2px 8px #eee;">
    <span style="position: absolute; top: 6px; left: 0; display: flex; flex-direction: row; font-size: 0.75em; font-weight: 600; border-radius: 2.5px; overflow: hidden; box-shadow: 0 1px 4px #bbb;">
      <span style="background: #444; color: #fff; padding: 1.5px 6px 1.5px 5px; letter-spacing: 0.5px;">Under Review</span>
    </span>
  </div>
  <div style="display: flex; align-items: center;">
    <span>
    Rihui Jin, Zheyu Xin, <b>Xing Xie</b>, Zuoyi Li, Guilin Qi, Yongrui Chen, Xinbang Dai, Tongtong Wu, Gholamreza Haffari,
      <b><em> Table-r1</em>: Self-supervised and Reinforcement Learning for Program-based Table Reasoning in Small Language Models</b>.
      <span style="color: #888;">arXiv, 2025</span>
    </span>
  </div>
</div>


# 🎖 Honors and Awards
- *2025.05* **Outstanding Paper Award**, Southeast University.  
- *2024.10* **Merit Student**, Southeast University.
- *2024.07* **Finalist of Best Poster Award**, *IEEE-CYBER 2024* in Copenhagen, Danmark.
<!-- - *2024.07* **Finalist of Best Poster Award**, *IEEE-CYBER 2024* in Copenhagen, Danmark, 2024. [\[Certifice\]](../files/finalist_of_best_poster_award.pdf) -->


# 📖 Educations
- *2022.08 - present*, School of Artificial Intelligence, Southeast University.