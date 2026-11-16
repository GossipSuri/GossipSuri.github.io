---
layout: single
title: "Research & Projects"
permalink: /research/
author_profile: true
---

<style>
.research-cards { display: grid; gap: 1.5rem; }
.research-card { display: grid; grid-template-columns: minmax(0, 40%) minmax(0, 1fr); gap: 1.6rem; align-items: center; padding: 1.6rem; border: 1px solid var(--global-border-color, #ddd); border-radius: 18px; background: var(--global-bg-color, #fff); box-shadow: 0 12px 30px rgba(0,0,0,.06); }
.research-card__visual { min-width: 0; }
.research-card__venue { display: inline-block; margin-bottom: .65rem; padding: .35rem .7rem; border-radius: 5px; background: #063ca5; color: #fff; font-size: .75em; font-weight: 700; }
.research-card__image { display: block; }
.research-card__image img { display: block; width: 100%; height: auto; max-height: 260px; object-fit: contain; background: #fff; box-shadow: 3px 4px 9px rgba(0,0,0,.18); }
.research-card__body { min-width: 0; font-size: .82em; line-height: 1.65; }
.research-card__body h2 { margin: 0 0 .9rem; padding: 0; border: 0; font-size: 1.15em; font-weight: 600; line-height: 1.5; }
.research-card__body ul { margin: 0; padding-left: 1.2rem; }
.research-card__body li { margin-bottom: .65rem; }
.research-card__body li:last-child { margin-bottom: 0; }
.research-card__links { margin-top: .4rem; }
.research-card__demo { opacity: .7; white-space: nowrap; }
@media (max-width: 700px) {
  .research-card { grid-template-columns: minmax(0, 1fr); gap: 1.25rem; padding: 1.1rem; }
  .research-card__image img { max-height: 300px; }
}
</style>

<div class="research-cards">
  <article class="research-card" aria-labelledby="designlearner-title">
    <div class="research-card__visual">
      <span class="research-card__venue">CSCW 2025</span>
      <a class="research-card__image" href="{{ '/images/projects/designlearner.png' | relative_url }}" aria-label="View DesignLearner system figure">
        <img src="{{ '/images/projects/designlearner.png' | relative_url }}" alt="DesignLearner interface, Figure 2 from the paper" loading="lazy">
      </a>
    </div>
    <div class="research-card__body">
      <h2 id="designlearner-title">Redesign of Online Design Communities: Facilitating Personalized Visual Design Learning with Structured Comments</h2>
      <ul>
        <li><strong>Xia Chen*</strong>, Xinyue Chen*, Weixian Hu, Haojia Zheng, Yujun Qian, and Zhenhui Peng†</li>
        <li>Proceedings of the ACM on Human-Computer Interaction (CSCW 2025)
          <div class="research-card__links"><a href="https://zhenhuipeng.com/docs/cscw2025_designlearner.pdf">PDF</a> &nbsp;|&nbsp; <a href="https://dl.acm.org/doi/10.1145/3757499">ACM</a> &nbsp;|&nbsp; <a href="https://www.xiaohongshu.com/discovery/item/693c1e22000000001e004007?source=webshare&xhsshare=pc_web&xsec_token=ABqIya_nbysL_9N9WLhbosYXA96SfDtqEE1mtAx4Ltg08=&xsec_source=pc_share">Video</a> </div>
        </li>
      </ul>
    </div>
  </article>

  <article class="research-card" aria-labelledby="inkideator-title">
    <div class="research-card__visual">
      <span class="research-card__venue">CHI 2026</span>
      <a class="research-card__image" href="{{ '/images/projects/inkideator.png' | relative_url }}" aria-label="View InkIdeator system figure">
        <img src="{{ '/images/projects/inkideator.png' | relative_url }}" alt="InkIdeator interface, Figure 1 from the CHI 2026 paper" loading="lazy">
      </a>
    </div>
    <div class="research-card__body">
      <h2 id="inkideator-title">InkIdeator: Supporting Chinese-Style Visual Design Ideation via AI-Infused Exploration of Chinese Paintings</h2>
      <ul>
        <li>Shiwei Wu, Ziyao Gao, Zhendong He, Zongtan He, ZhuPeng Huang, <strong>Xia Chen</strong>, Wei Zeng, Xiaojuan Ma, and Zhenhui Peng</li>
        <li>Proceedings of the 2026 CHI Conference on Human Factors in Computing Systems (CHI ’26), Article 388
          <div class="research-card__links"><a href="https://zhenhuipeng.com/docs/chi26_inkideator.pdf">PDF</a> &nbsp;|&nbsp; <a href="https://doi.org/10.1145/3772318.3791675">DOI</a></div>
        </li>
      </ul>
    </div>
  </article>

  <article class="research-card" aria-labelledby="beautyclicker-title">
    <div class="research-card__visual">
      <span class="research-card__venue">IJHCI 2025</span>
      <a class="research-card__image" href="{{ '/images/projects/beautyclicker.png' | relative_url }}" aria-label="View BeautyClicker system figure">
        <img src="{{ '/images/projects/beautyclicker.png' | relative_url }}" alt="BeautyClicker interface, Figure 3 from the paper" loading="lazy">
      </a>
    </div>
    <div class="research-card__body">
      <h2 id="beautyclicker-title">BeautyClicker: Modeling Viewers’ Click Intent of the Cover Image to Support Drafts of Beauty Product Promotion Posts</h2>
      <ul>
        <li>Xueer Lin, <strong>Xia Chen</strong>, and Zhenhui Peng†</li>
        <li>International Journal of Human–Computer Interaction (2025)
          <div class="research-card__links"><a href="https://zhenhuipeng.com/docs/ijhci2025_beautyclicker.pdf">PDF</a> &nbsp;|&nbsp; <a href="https://doi.org/10.1080/10447318.2025.2531291">DOI</a> &nbsp;|&nbsp; <span class="research-card__demo">Demo · Coming soon</span></div>
        </li>
      </ul>
    </div>
  </article>
</div>
