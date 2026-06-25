---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<style>
.home-intro {
  font-size: 1.12rem;
  line-height: 1.9;
  margin-bottom: 1.2rem;
  color: #2d3748;
}

  .welcome-banner {
  display: inline-block;
  margin-bottom: 1.1rem;
  padding: 0.45rem 0.9rem;
  border-radius: 999px;
  background: linear-gradient(135deg, #eef4ff 0%, #fff3f7 100%);
  border: 1px solid #dbe7fb;
  color: #355c9a;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.01em;
  box-shadow: 0 4px 12px rgba(40, 56, 90, 0.05);
}

.home-intro strong {
  color: #234a8f;
}

.home-highlight {
  border-left: 6px solid #f06c86;
  background: linear-gradient(135deg, #fff6f8 0%, #f4f8ff 100%);
  padding: 1.05rem 1.25rem;
  border-radius: 14px;
  margin: 1.6rem 0 2rem 0;
  font-size: 1.12rem;
  line-height: 1.85;
  color: #334155;
  box-shadow: 0 6px 18px rgba(42, 71, 120, 0.08);
}

h2 {
  color: #243b53;
  margin-top: 2.2rem;
  margin-bottom: 1rem;
  font-weight: 700;
}

h3 {
  color: #2b3a55;
}

a {
  color: #2f5da8;
  text-decoration: none;
}

a:hover {
  color: #d95d7a;
  text-decoration: underline;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.2rem;
  margin: 1.5rem 0 2.2rem 0;
}

.info-card {
  border-radius: 18px;
  padding: 1.25rem 1.2rem 1.05rem 1.2rem;
  box-shadow: 0 6px 18px rgba(0,0,0,0.06);
  border: 1px solid rgba(0,0,0,0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.info-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 24px rgba(40, 56, 90, 0.09);
}

.info-card h3 {
  margin-top: 0;
  margin-bottom: 0.9rem;
  font-size: 1.24rem;
}

.info-card ul {
  margin-bottom: 0;
  padding-left: 1.2rem;
}

.info-card li {
  margin-bottom: 0.45rem;
  font-size: 1.05rem;
  line-height: 1.75;
  color: #374151;
}

.card-blue {
  background: linear-gradient(135deg, #edf4ff 0%, #f8fbff 100%);
  border-color: #d7e6ff;
}

.card-pink {
  background: linear-gradient(135deg, #fff2f6 0%, #fff9fb 100%);
  border-color: #ffd8e3;
}

.card-yellow {
  background: linear-gradient(135deg, #fff8e7 0%, #fffdf6 100%);
  border-color: #f6e6b3;
}

.card-green {
  background: linear-gradient(135deg, #eefbf4 0%, #f8fffb 100%);
  border-color: #d8f0df;
}

.paper-box {
  display: flex;
  flex-wrap: wrap;
  gap: 1.2rem;
  align-items: stretch;
  background: #ffffff;
  border: 1px solid #e9edf4;
  border-radius: 18px;
  padding: 1.2rem;
  margin-bottom: 1.4rem;
  box-shadow: 0 8px 22px rgba(40, 56, 90, 0.06);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.paper-box:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 28px rgba(40, 56, 90, 0.09);
}

.paper-box-image {
  flex: 1 1 280px;
  max-width: 360px;
}

.paper-box-image img {
  width: 100%;
  border-radius: 12px;
}

.paper-box-text {
  flex: 2 1 380px;
  font-size: 1.04rem;
  line-height: 1.8;
  color: #374151;
}

.paper-box-text h3 {
  margin-top: 0.2rem;
  margin-bottom: 0.6rem;
  font-size: 1.28rem;
  color: #243b53;
}

.badge-soft {
  display: inline-block;
  padding: 0.25rem 0.72rem;
  border-radius: 999px;
  background: #ffe3ea;
  color: #b24768;
  font-size: 0.86rem;
  font-weight: 700;
  margin-bottom: 0.85rem;
}

.badge-blue {
  background: #e2edff;
  color: #3c66b0;
}

.badge-green {
  background: #ddf5e7;
  color: #2d7f5e;
}

.news-list,
.award-list,
.edu-list {
  font-size: 1.04rem;
  line-height: 1.8;
  color: #374151;
}

.news-list li,
.award-list li,
.edu-list li {
  margin-bottom: 0.45rem;
}

.fun-facts {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 0.9rem;
  margin-top: 1rem;
}

.fact-box {
  background: linear-gradient(135deg, #ffffff 0%, #f9fbff 100%);
  border: 1px solid #e7edf5;
  border-radius: 16px;
  padding: 1rem 1rem 0.9rem 1rem;
  text-align: center;
  box-shadow: 0 5px 16px rgba(40, 56, 90, 0.05);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.fact-box:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 22px rgba(40, 56, 90, 0.08);
}

.fact-number {
  font-size: 1.95rem;
  font-weight: 800;
  color: #ef6b7f;
  line-height: 1.2;
}

.fact-label {
  margin-top: 0.4rem;
  font-size: 1.03rem;
  color: #4b5563;
  line-height: 1.6;
}

.contact-box {
  background: linear-gradient(135deg, #f4f8ff 0%, #fff7fa 100%);
  border: 1px solid #e4ebf5;
  border-radius: 16px;
  padding: 1rem 1.2rem;
  margin-top: 1rem;
  font-size: 1.04rem;
  line-height: 1.8;
  color: #374151;
  box-shadow: 0 5px 16px rgba(40, 56, 90, 0.04);
}

.anchor {
  display: block;
  position: relative;
  top: -80px;
  visibility: hidden;
}

@media (max-width: 768px) {
  .home-intro {
    font-size: 1.02rem;
  }

  .home-highlight {
    font-size: 1.03rem;
  }

  .paper-box-text h3 {
    font-size: 1.16rem;
  }

  .info-card h3 {
    font-size: 1.14rem;
  }

  .fact-number {
    font-size: 1.7rem;
  }

  .fact-label {
    font-size: 0.98rem;
  }
}
</style>

<span class='anchor' id='about-me'></span>


<div class="welcome-banner">Welcome! I’m glad you’re here :) </div>


<div class="home-intro">
My name is Chenyu Liu. I am a Ph.D. student in Epidemiology and Biostatistics at Case Western Reserve University, where I work on both methodological and applied problems. Methodologically, I study separation in logistic regression and develop correction procedures to address odds ratio inflation. On the applied side, I analyze complex clinical and omics datasets to identify meaningful biomarkers and improve statistical inference in translational research.
</div>

<div class="home-highlight">
My research sits at the intersection of statistical methodology, high-dimensional omics data, and biomedical applications. I am particularly interested in Alzheimer's disease, microbiome studies, proteomics, and Bayesian modeling.
</div>

<div class="card-grid">

  <div class="info-card card-blue">
    <h3>📊 Research Interests</h3>
    <ul>
      <li>Bayesian modeling</li>
      <li>Logistic regression and separation</li>
      <li>Microbiome data analysis</li>
      <li>Proteomics and biomarker discovery</li>
    </ul>
  </div>

  <div class="info-card card-pink">
    <h3>🧬 Current Research</h3>
    <ul>
      <li>Alzheimer’s disease and the gut-brain axis</li>
      <li>Low-biomass blood metagenomics</li>
      <li>High-dimensional omics integration</li>
      <li>Clinical and translational biostatistics</li>
    </ul>
  </div>

  <div class="info-card card-yellow">
    <h3>💻 Methods & Tools</h3>
    <ul>
      <li>R, Python, MATLAB</li>
      <li>Stan and brms</li>
      <li>Bioinformatics: QIIME2, MetaPhlAn, HUMAnN</li>
      <li>Sequence analysis: Kraken2, Bracken, Bowtie2, minimap2</li>
    </ul>
  </div>

</div>

<span class='anchor' id='travel-snapshot'></span>

## 🌍 Outside of Research

<div class="info-card card-green">
  <p>
    Outside of research, I enjoy photography, traveling, kayaking, and exploring new cuisines. I've recently taken up baking — still very much a work in progress!
  </p>
</div>


## ✈️ Travel Snapshot

<div class="fun-facts">
  <div class="fact-box">
    <div class="fact-number">20</div>
    <div class="fact-label">Provinces / municipalities / autonomous regions in China</div>
  </div>
  <div class="fact-box">
    <div class="fact-number">12</div>
    <div class="fact-label">States in the United States</div>
  </div>
  <div class="fact-box">
    <div class="fact-number">8</div>
    <div class="fact-label">Countries visited</div>
  </div>
</div>

<span class='anchor' id='news'></span>
## 🎉 News

<ul class="news-list">
  <li><strong>2026.05</strong> I successfully defended my dissertation proposal and became a PhD Candidate!</li>
  <li><strong>2026.04</strong> Our comprehensive review on the Gut-Brain Axis was accepted by <em>Frontiers in Molecular Biosciences</em>!</li>
  <li><strong>2026.03</strong> Presented my research on the Separation Problem at the ENAR 2026 Spring Meeting!</li>
  <li><strong>2025.11</strong> Our proteomics analysis on chronic kidney disease was accepted by <em>Kidney Medicine</em>!</li>
  <li><strong>2025.08</strong> Received a Conference Fellowship for the Alzheimer’s Association International Conference 2025!</li>
</ul>

<span class='anchor' id='selected-research'></span>
## 📄 Selected Research

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/DISCO.png" alt="logistic regression project">
  </div>

  <div class="paper-box-text">
    <div class="badge-soft">Methodology</div>
    <h3>Suppressing Odds Ratio Inflation in Logistic Regression</h3>
    <p>
      I develop diagnostic tools and correction procedures for inflated odds ratio estimates under perfect or near separation in logistic regression.
    </p>
    <p><strong>Keywords:</strong> logistic regression, separation, odds ratio inflation, Bayesian methods</p>
      <p>
    <strong>Package:</strong> <a href="https://github.com/bioscinema/DISCO" target="_blank">DISCO</a></p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/GBA.png" alt="microbiome and Alzheimer's project">
  </div>

  <div class="paper-box-text">
    <div class="badge-soft badge-blue">Biomedical Application</div>
    <h3>Gut Microbiome and Alzheimer’s Disease</h3>
    <p>
      I study microbiome alterations associated with Alzheimer’s disease and APOE-related risk, with emphasis on shotgun metagenomic analysis, the gut-brain axis, and microbial mechanisms relevant to neurodegeneration.
    </p>
    <p><strong>Keywords:</strong> Alzheimer’s disease, microbiome, APOE4, gut-brain axis</p>
    <p>
    <strong>Related Publication:</strong> <a href="https://www.frontiersin.org/journals/molecular-biosciences/articles/10.3389/fmolb.2026.1735332/full" target="_blank">Comprehensive Review</a></p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/UKB.png" alt="proteomics project">
  </div>

  <div class="paper-box-text">
    <div class="badge-soft badge-green">Omics & Clinical Data</div>
    <h3>Proteomics Discovery</h3>
    <p>
      I analyze high-dimensional proteomic and clinical data to identify biomarkers associated with cardiovascular phenotypes and treatment-related changes.
    </p>
    <p><strong>Keywords:</strong> proteomics, biomarker discovery, cardiovascular outcomes, high-dimensional data</p>
    <p>
    <strong>Related Publication:</strong> <a href="https://www.sciencedirect.com/science/article/pii/S2590059525002274" target="_blank">A Pilot Study</a></p>
  </div>
</div>


<span class='anchor' id='education'></span>
## 🎓 Education

<ul class="edu-list">
  <li><strong>Ph.D. in Epidemiology and Biostatistics</strong>, Case Western Reserve University, 2023 - present</li>
  <li><strong>M.S. in Statistics</strong>, Case Western Reserve University, 2021 - 2023</li>
  <li><strong>B.S. in Statistics</strong>, Wuhan University of Technology, 2016 - 2020</li>
</ul>

<span class='anchor' id='service'></span>
## 🤝 Service

<ul class="award-list">
  <li><strong>President</strong>, American Statistical Association Student Chapter, Case Western Reserve University, 2024 – 2026</li>
  <li><strong>Student Representative</strong>, Department of Population and Quantitative Health Sciences, Case Western Reserve University, 2024 – present</li>
  <li><strong>Statistical Consultant</strong>, collaborative biomedical research projects, 2024 – present</li>
  <li><strong>Poster Judge</strong>, Fall Intersection, Case Western Reserve University, 2025</li>
</ul>

<span class='anchor' id='awards'></span>
## 🏅 Honors and Awards

<ul class="award-list">
  <li>Conference Fellowship, Alzheimer’s Association International Conference, 2025</li>
  <li>Outstanding Graduates Award, Wuhan University of Technology, 2020</li>
</ul>
