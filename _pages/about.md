---
layout: about
title: about
permalink: /
subtitle: Ph.D. Student, Computer Science and Engineering, POSTECH

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Data Intelligence Lab</p>
    <p>POSTECH</p>
    <p>Pohang, South Korea</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>
  @import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap");

  body {
    font-family: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Apple SD Gothic Neo", "Noto Sans KR", sans-serif;
  }

  .wj,
  .wj * {
    font-family: inherit;
  }

  .wj {
    --wj-accent: var(--global-theme-color, #0d7c86);
    --wj-line: rgba(127, 127, 127, 0.22);
    --wj-soft: rgba(127, 127, 127, 0.06);
    --wj-softer: rgba(127, 127, 127, 0.1);
    --wj-muted: #6b7280;
    clear: both;
    margin-top: 2rem;
    line-height: 1.55;
  }

  @supports (color: color-mix(in srgb, red, blue)) {
    .wj {
      --wj-muted: color-mix(in srgb, currentColor 62%, transparent);
    }
  }

  .wj-card {
    border: 1px solid var(--wj-line);
    border-radius: 14px;
    background: var(--wj-soft);
    padding: 1.4rem 1.6rem 1.5rem;
    margin: 0 0 1.15rem;
  }

  .wj-card > h2 {
    position: relative;
    margin: 0 0 1rem;
    padding-left: 0.8rem;
    font-size: 1.25rem;
    font-weight: 700;
    letter-spacing: -0.01em;
    line-height: 1.3;
    border: none;
  }

  .wj-card > h2::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0.2em;
    bottom: 0.2em;
    width: 4px;
    border-radius: 2px;
    background: var(--wj-accent);
    opacity: 0.9;
  }

  .wj ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  .wj-bullets li {
    position: relative;
    padding-left: 1.1rem;
    margin: 0 0 0.35rem;
    font-size: 0.98rem;
  }

  .wj-bullets li::before {
    content: "";
    position: absolute;
    left: 0.1rem;
    top: 0.62em;
    width: 5px;
    height: 5px;
    border-radius: 50%;
    background: var(--wj-accent);
    opacity: 0.75;
  }

  .wj-row {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 0.75rem 1.25rem;
    flex-wrap: wrap;
  }

  .wj-date {
    flex: none;
    font-size: 0.85rem;
    font-variant-numeric: tabular-nums;
    color: var(--wj-muted);
    white-space: nowrap;
  }

  /* Education */
  .wj-edu li + li {
    margin-top: 1.1rem;
    padding-top: 1.1rem;
    border-top: 1px dashed var(--wj-line);
  }

  .wj-school {
    font-size: 1.02rem;
    font-weight: 650;
    letter-spacing: -0.005em;
  }

  .wj-school .wj-loc {
    font-weight: 400;
    color: var(--wj-muted);
  }

  .wj-degree {
    margin-top: 0.2rem;
    font-size: 0.94rem;
  }

  .wj-lab {
    margin-top: 0.15rem;
    font-size: 0.88rem;
    color: var(--wj-muted);
  }

  /* Publications */
  .wj-year {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    margin: 1.5rem 0 0.35rem;
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 0.09em;
    text-transform: uppercase;
    color: var(--wj-muted);
  }

  .wj-year:first-of-type {
    margin-top: 0.2rem;
  }

  .wj-year::after {
    content: "";
    flex: 1 1 auto;
    height: 1px;
    background: var(--wj-line);
  }

  .wj-pub {
    padding: 0.7rem 0.75rem;
    margin: 0 -0.75rem;
    border-radius: 10px;
    transition: background-color 0.15s ease;
  }

  .wj-pub:hover {
    background: var(--wj-softer);
  }

  .wj-pub-title {
    font-size: 1rem;
    font-weight: 600;
    line-height: 1.45;
    letter-spacing: -0.005em;
  }

  .wj-authors {
    margin-top: 0.28rem;
    font-size: 0.89rem;
    line-height: 1.5;
  }

  .wj-me {
    font-weight: 700;
    text-decoration: underline;
    text-underline-offset: 2.5px;
    text-decoration-thickness: 1px;
  }

  .wj-venue {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-top: 0.45rem;
    font-size: 0.85rem;
    color: var(--wj-muted);
  }

  .wj-tag {
    display: inline-block;
    padding: 0.1rem 0.55rem;
    border: 1px solid var(--wj-line);
    border-radius: 999px;
    background: var(--wj-softer);
    color: var(--wj-accent);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.01em;
    white-space: nowrap;
  }

  .wj-tag-oral {
    border-color: transparent;
    background: var(--wj-accent);
    color: #fff;
  }

  /* Services & teaching */
  .wj-sub {
    margin: 0 0 0.6rem;
    font-size: 0.95rem;
    font-weight: 650;
  }

  .wj-rows li {
    padding: 0.42rem 0;
    font-size: 0.93rem;
  }

  .wj-rows li + li {
    border-top: 1px solid var(--wj-line);
  }

  .wj-meta {
    color: var(--wj-muted);
  }

  .wj-code {
    display: inline-block;
    padding: 0.02rem 0.4rem;
    border-radius: 6px;
    background: var(--wj-softer);
    font-size: 0.8rem;
    font-weight: 600;
    color: var(--wj-muted);
  }

  @media (max-width: 576px) {
    .wj-card {
      padding: 1.15rem 1.1rem 1.25rem;
      border-radius: 12px;
    }

    .wj-pub {
      margin: 0 -0.4rem;
      padding: 0.6rem 0.4rem;
    }
  }
</style>

<div class="wj">

<section class="wj-card">
  <h2>Research Interests</h2>
  <ul class="wj-bullets">
    <li>Information retrieval and recommendation system</li>
  </ul>
</section>

<section class="wj-card">
  <h2>Education</h2>
  <ul class="wj-edu">
    <li>
      <div class="wj-row">
        <div>
          <div class="wj-school">Pohang University of Science and Technology (POSTECH)<span class="wj-loc">, South Korea</span></div>
          <div class="wj-degree">Ph.D., Computer Science and Engineering</div>
          <div class="wj-lab">Data Intelligence Lab (advisor: HwanJo Yu)</div>
        </div>
        <div class="wj-date">2022.09 – Present</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>
          <div class="wj-school">Pohang University of Science and Technology (POSTECH)<span class="wj-loc">, South Korea</span></div>
          <div class="wj-degree">B.S., Computer Science and Engineering</div>
        </div>
        <div class="wj-date">2018.03 – 2022.08</div>
      </div>
    </li>
  </ul>
</section>

<section class="wj-card">
  <h2>Publications</h2>

  <div class="wj-year">Preprints</div>
  <ul class="wj-pubs">
    <li class="wj-pub">
      <div class="wj-pub-title">FedGRACE: Federated Geometric Representation Anchoring via Controlled-Collapse ETF for LLM-Enhanced Recommendation</div>
      <div class="wj-authors">DoYeon Lim, JaeHyung Lim, <span class="wj-me">WooJoo Kim</span>, HwanJo Yu</div>
    </li>
    <li class="wj-pub">
      <div class="wj-pub-title">VLM2Rec: Resolving Modality Collapse in Vision-Language Model Embedders for Multimodal Sequential Recommendation</div>
      <div class="wj-authors">JunYoung Kim, <span class="wj-me">WooJoo Kim</span>, WonBin Kweon, JaeHyung Lim, DongHa Kim, HwanJo Yu</div>
    </li>
    <li class="wj-pub">
      <div class="wj-pub-title">Personalized and Multi-View Representation for Federated Cold-Start Recommendation</div>
      <div class="wj-authors">JaeHyung Lim, WonBin Kweon, <span class="wj-me">WooJoo Kim</span>, JunYoung Kim, DongHa Kim, HwanJo Yu</div>
    </li>
  </ul>

  <div class="wj-year">2026</div>
  <ul class="wj-pubs">
    <li class="wj-pub">
      <div class="wj-pub-title">Personalized Federated Recommendation via Long-Horizon Local Optimization and Regularized Knowledge Guidance</div>
      <div class="wj-authors">JaeHyung Lim, WonBin Kweon, <span class="wj-me">WooJoo Kim</span>, JunYoung Kim, DongHa Kim, HwanJo Yu</div>
      <div class="wj-venue"><span class="wj-tag">JIIS'26</span> Journal of Intelligent Information Systems</div>
    </li>
    <li class="wj-pub">
      <div class="wj-pub-title">TRACER: Balancing Stability-Plasticity-Cognitivity Trilemma for LLM Enhanced Continual Recommendation</div>
      <div class="wj-authors"><span class="wj-me">WooJoo Kim</span>, HyunSik Yoo, JunYoung Kim, JaeHyung Lim, SeongKu Kang, HwanJo Yu</div>
      <div class="wj-venue"><span class="wj-tag">CIKM'26</span><span class="wj-tag wj-tag-oral">Oral</span> ACM International Conference on Information and Knowledge Management</div>
    </li>
    <li class="wj-pub">
      <div class="wj-pub-title">GOD: Enhancing Generalization via Deep Grafting for Sequential Recommendation</div>
      <div class="wj-authors"><span class="wj-me">WooJoo Kim</span>, JunYoung Kim, JaeHyung Lim, HwanJo Yu</div>
      <div class="wj-venue"><span class="wj-tag">CIKM'26</span><span class="wj-tag wj-tag-oral">Oral</span> ACM International Conference on Information and Knowledge Management</div>
    </li>
    <li class="wj-pub">
      <div class="wj-pub-title">From Overlooked to Explored: Recovering Item Relations via Mixture of Perspectives for Sequential Recommendation</div>
      <div class="wj-authors">JunYoung Kim, WonBin Kweon, <span class="wj-me">WooJoo Kim</span>, JaeHyung Lim, DongHa Kim, HwanJo Yu</div>
      <div class="wj-venue"><span class="wj-tag">CIKM'26</span> ACM International Conference on Information and Knowledge Management</div>
    </li>
    <li class="wj-pub">
      <div class="wj-pub-title">FLAME: Condensing Ensemble Diversity into a Single Network for Efficient Sequential Recommendation</div>
      <div class="wj-authors"><span class="wj-me">WooJoo Kim</span>, JunYoung Kim, JaeHyung Lim, SeongJin Choi, SeongKu Kang, HwanJo Yu</div>
      <div class="wj-venue"><span class="wj-tag">SIGIR'26</span> International ACM SIGIR Conference on Research and Development in Information Retrieval</div>
    </li>
  </ul>

  <div class="wj-year">2025</div>
  <ul class="wj-pubs">
    <li class="wj-pub">
      <div class="wj-pub-title">Federated Continual Recommendation</div>
      <div class="wj-authors">JaeHyung Lim, WonBin Kweon, <span class="wj-me">WooJoo Kim</span>, JunYoung Kim, SeongJin Choi, DongHa Kim, HwanJo Yu</div>
      <div class="wj-venue"><span class="wj-tag">CIKM'25</span> ACM International Conference on Information and Knowledge Management</div>
    </li>
  </ul>
</section>

<section class="wj-card">
  <h2>Academic Services</h2>
  <div class="wj-sub">Program Committee / Reviewer</div>
  <ul class="wj-rows">
    <li>
      <div class="wj-row">
        <div>Conference on Neural Information Processing Systems <span class="wj-meta">(NeurIPS)</span></div>
        <div class="wj-date">2023</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>Conference on Empirical Methods in Natural Language Processing <span class="wj-meta">(EMNLP)</span></div>
        <div class="wj-date">2024</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>IEEE International Conference on Data Mining <span class="wj-meta">(ICDM)</span></div>
        <div class="wj-date">2025</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>ACM The Web Conference <span class="wj-meta">(WWW)</span></div>
        <div class="wj-date">2026</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>International ACM SIGIR Conference on Research and Development in Information Retrieval <span class="wj-meta">(SIGIR)</span></div>
        <div class="wj-date">2026</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>ACM International Conference on Information and Knowledge Management <span class="wj-meta">(CIKM)</span></div>
        <div class="wj-date">2026</div>
      </div>
    </li>
  </ul>
</section>

<section class="wj-card">
  <h2>Teaching</h2>
  <ul class="wj-rows">
    <li>
      <div class="wj-row">
        <div>Introduction to Data Analysis <span class="wj-code">CSED22</span> <span class="wj-meta">· TA, POSTECH</span></div>
        <div class="wj-date">2023</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>Artificial Intelligence <span class="wj-code">CSED342</span> <span class="wj-meta">· TA, POSTECH</span></div>
        <div class="wj-date">2023</div>
      </div>
    </li>
    <li>
      <div class="wj-row">
        <div>Artificial Intelligence <span class="wj-code">CSED342</span> <span class="wj-meta">· TA, POSTECH</span></div>
        <div class="wj-date">2022</div>
      </div>
    </li>
  </ul>
</section>

</div>
