html
<style>
.news-wrapper {
  display: flex;
  align-items: stretch;
  gap: 28px;
  margin: 28px 0 36px 0;
}

.news-left {
  flex: 1.45;
}

.news-left h2 {
  margin-top: 0;
  margin-bottom: 14px;
  font-size: 1.5rem;
  font-weight: 700;
}

.news-list {
  list-style: none;
  padding-left: 0;
  margin: 0;
}

.news-list li {
  margin-bottom: 10px;
  line-height: 1.55;
  font-size: 0.96rem;
}

.news-date {
  font-style: italic;
  font-weight: 600;
  color: #555;
  white-space: nowrap;
}

.news-right {
  flex: 0.85;
  display: flex;
  justify-content: center;
  align-items: center;
}

.news-right img {
  width: 100%;
  max-width: 260px;
  aspect-ratio: 3 / 4;
  object-fit: cover;
  border-radius: 12px;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.14);
}

@media (max-width: 768px) {
  .news-wrapper {
    flex-direction: column;
  }

  .news-right img {
    max-width: 100%;
    aspect-ratio: 16 / 9;
  }
}
</style>

<div class="news-wrapper">

  <div class="news-left">

## 🔥 News

<ul class="news-list">
  <li><span class="news-date">30 Jun 2026</span>, our paper <b>LLF-GS SLAM</b> is under review by <b>IEEE TMM</b>.</li>
  <li><span class="news-date">19 Mar 2025</span>, our paper <b>RGBDS-SLAM</b> has been published by <b>IEEE RA-L 2025</b>.</li>
  <li><span class="news-date">9 Oct 2024</span>, I was selected for the <b>Young Talents Support Project for Doctoral Students</b> by the China Association for Science and Technology, with a support period of 2 years.</li>
  <li><span class="news-date">6 Sep 2024</span>, our survey paper on <b>3D Gaussian Splatting</b> has been published by <b>Robot 2024</b>.</li>
  <li><span class="news-date">6 Mar 2024</span>, our paper <b>SemanticTopoLoop</b> has been published by <b>IEEE RA-L 2024</b>.</li>
  <li><span class="news-date">13 Jul 2022</span>, our paper <b>Object-Aware SLAM</b> has been published by <b>IEEE RA-L / IROS 2022</b>.</li>
</ul>

  </div>

  <div class="news-right">
    <img src="/images/phd-plan.png" alt="Research figure">
  </div>

</div>
