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
  font-size: 1.05rem;
  line-height: 1.8;
  margin-bottom: 1.2rem;
}

.home-highlight {
  border-left: 5px solid #e97b8c;
  background: #f8f8f8;
  padding: 1rem 1.2rem;
  border-radius: 10px;
  margin: 1.5rem 0 2rem 0;
  font-size: 1.08rem;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.2rem;
  margin: 1.5rem 0 2.2rem 0;
}

.info-card {
  background: #fafafa;
  border: 1px solid #e8e8e8;
  border-radius: 14px;
  padding: 1.2rem 1.2rem 1rem 1.2rem;
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}

.info-card h3 {
  margin-top: 0;
  margin-bottom: 0.8rem;
}

.info-card ul {
  margin-bottom: 0;
}

.paper-box {
  display: flex;
  flex-wrap: wrap;
  gap: 1.2rem;
  align-items: stretch;
  background: #fff;
  border: 1px solid #ececec;
  border-radius: 16px;
  padding: 1rem;
  margin-bottom: 1.4rem;
  box-shadow: 0 2px 10px rgba(0,0,0,0.04);
}

.paper-box-image {
  flex: 1 1 280px;
  max-width: 360px;
}

.paper-box-image img {
  width: 100%;
  border-radius: 10px;
}

.paper-box-text {
  flex: 2 1 380px;
}

.badge-soft {
  display: inline-block;
  padding: 0.2rem 0.65rem;
  border-radius: 999px;
  background: #f7d9df;
  color: #a33a57;
  font-size: 0.82rem;
  font-weight: 600;
  margin-bottom: 0.8rem;
}

.section-space {
  margin-top: 2.2rem;
}
</style>

<span class='anchor' id='about-me'></span>

<div class="home-intro">
  My name is <strong>Chenyu Liu</strong>. I am a Ph.D. student in <strong>Epidemiology and Biostatistics</strong> at <strong>Case Western Reserve University</strong>. My research lies at the intersection of <strong>statistical methodology</strong>, <strong>high-dimensional omics data</strong>, and <strong>biomedical applications</strong>, with a particular interest in Alzheimer’s disease, microbiome studies, proteomics, and Bayesian modeling.
</div>

<div class="home-intro">
  I work on both methodological and applied problems. On the methods side, I study separation in logistic regression and develop correction procedures for odds ratio inflation. On the applied side, I analyze complex clinical and omics datasets to identify meaningful biomarkers and improve statistical inference in translational research.
</div>

<div class="home-highlight">
  My research focuses on developing reliable statistical methods for complex biomedical data and applying them to problems in Alzheimer’s disease, microbiome science, and precision health.
</div>

Feel free to reach out if you would like to discuss research, collaboration, or related projects.

<div class="card-grid">

  <div class="info-card">
    <h3>📊 Research Interests</h3>
    <ul>
      <li>Bayesian modeling</li>
      <li>Logistic regression and separation</li>
      <li>Microbiome data analysis</li>
      <li>Proteomics and biomarker discovery</li>
    </ul>
  </div>

  <div class="info-card">
    <h3>🧬 Current Topics</h3>
    <ul>
      <li>Alzheimer’s disease and gut-brain axis</li>
      <li>Low-biomass blood metagenomics</li>
      <li>High-dimensional omics integration</li>
      <li>Clinical and translational biostatistics</li>
    </ul>
  </div>

  <div class="info-card">
    <h3>💻 Methods & Tools</h3>
    <ul>
      <li>R, Python, MATLAB</li>
      <li>Stan, brms, generalized linear models</li>
      <li>Shotgun metagenomics workflows</li>
      <li>Reproducible statistical computing</li>
    </ul>
  </div>

</div>

## 📰 News

- **2025**: Received a Conference Fellowship for the Alzheimer’s Association International Conference.
- **2025**: Worked on proteome-wide association analysis of diastolic dysfunction in UK Biobank.
- **2025**: Continued collaborative work on gut microbiome alterations related to Alzheimer’s disease.
- **2024**: Presented work on odds ratio inflation and separation in logistic regression.

## 📄 Selected Research

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/500x300.png" alt="research image">
  </div>

  <div class="paper-box-text" markdown="1">
  <div class="badge-soft">Methodology</div>

  ### Suppressing Odds Ratio Inflation in Logistic Regression

  Developed diagnostic ideas for separation severity in logistic regression and worked on correction procedures for inflated odds ratio estimates under perfect or near separation.

  **Keywords:** logistic regression, separation, odds ratio inflation, Bayesian methods

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/500x300.png" alt="research image">
  </div>

  <div class="paper-box-text" markdown="1">
  <div class="badge-soft">Biomedical Application</div>

  ### Gut Microbiome and Alzheimer’s Disease

  Studied microbiome alterations associated with Alzheimer’s disease and APOE-related risk, with emphasis on shotgun metagenomic analysis, the gut-brain axis, and microbial mechanisms relevant to neurodegeneration.

  **Keywords:** Alzheimer’s disease, microbiome, APOE4, gut-brain axis

  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <img src="/images/500x300.png" alt="research image">
  </div>

  <div class="paper-box-text" markdown="1">
  <div class="badge-soft">Omics & Clinical Data</div>

  ### Proteomics and Biomarker Discovery

  Analyzed high-dimensional proteomic and clinical data to identify biomarkers associated with cardiovascular phenotypes and treatment-related changes.

  **Keywords:** proteomics, biomarker discovery, cardiovascular outcomes, high-dimensional data

  </div>
</div>

## 🎓 Education

- **Ph.D. in Epidemiology and Biostatistics**, Case Western Reserve University, 2023 to present  
- **M.S. in Statistics**, Case Western Reserve University, 2021 to 2023  
- **B.S. in Statistics**, Wuhan University of Technology, 2016 to 2020  

## 🏅 Honors and Awards

- Conference Fellowship, Alzheimer’s Association International Conference, 2025  
- Outstanding Graduates Award, Wuhan University of Technology, 2020  

