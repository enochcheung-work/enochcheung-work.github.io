---
layout: default
title: Portfolio
---

## Portfolio

<p class="page-intro"> 
I translate health-domain evidence and quantitative analysis into decision support for digital health platforms —
with a focus on adoption constraints, systems context, and prioritisation.
</p>

<div class="section-title">Featured: Academic work applied to platform analysis</div>

<div class="cards">
  <a class="card" href="/msc-health/">
    <div class="card-title">MSc → Platform Strategy Lens</div>
    <div class="card-desc">
      How health economics, systems thinking, and research methods translate into platform and business analysis
      for healthcare decisions.
    </div>
    <div class="card-meta">University of Groningen · Distinction</div>
  </a>

  <a class="card" href="/thesis/">
    <div class="card-title">Master’s Thesis → Qualitative Evidence for Platform Decisions</div>
    <div class="card-desc">
      Evidence synthesis on why digital health interventions succeed or fail across contexts —
      and what this implies for adoption, implementation, and scaling.
    </div>
    <div class="card-meta">Systematic literature review · Decision-oriented framing</div>
  </a>
</div>

<div class="section-title">Secondary: Quantitative decision-support and modelling</div>

<div class="cards">
  <a class="card card-secondary" href="/norovirus-model/">
    <div class="card-title">Norovirus Modelling → Strategy Comparison</div>
    <div class="card-desc">
      Excel-based quantitative analysis with visual outputs to compare strategies and support prioritisation
      decisions under uncertainty.
    </div>
    <div class="card-meta">Excel · Visualisation · VBA automation</div>
  </a>
</div>

<div class="section-title">Projects: Data visualisation and performance analytics</div>

<div class="projects">
  <a class="project" href="/data-studio-dashboard">
    <div class="project-title">Data Studio Dashboard — Product/Marketing Performance</div>
    <img src="images/data_studio_dashboard.png?raw=true" alt="Data Studio dashboard thumbnail">
  </a>

  <a class="project" href="/visualisation_tableau_canva">
    <div class="project-title">Data Visualisation — Tableau and Canva</div>
    <img src="images/visualisation_tableau_canva.png?raw=true" alt="Tableau and Canva visualisation thumbnail">
  </a>

  <a class="project" href="/organic_conversion_optimisation">
    <div class="project-title">Organic Traffic and Conversion Rate</div>
    <img src="images/organic_conversion_optimisation.png?raw=true" alt="Organic traffic and conversion thumbnail">
  </a>

  <a class="project" href="/serp_seo">
    <div class="project-title">SEO Analytics</div>
    <img src="images/serp_seo.png?raw=true" alt="SEO analytics thumbnail">
  </a>

  <a class="project" href="/sem_keyword">
    <div class="project-title">SEM Keyword Monitoring</div>
    <img src="images/sem_keyword_thumbnail.png?raw=true" alt="SEM keyword monitoring thumbnail">
  </a>
</div>

<hr class="footer-hr">

<p class="footer-note">
  <span>Template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></span>
</p>

<style>
/* Minimalist styling, theme-friendly */
.page-intro{
  margin: 0.2rem 0 1.2rem;
  max-width: 70ch;
  opacity: 0.9;
}

.section-title{
  margin: 1.4rem 0 0.7rem;
  font-size: 0.95rem;
  font-weight: 700;
  letter-spacing: 0.02em;
  opacity: 0.85;
  text-transform: none;
}

/* Cards */
.cards{
  display: grid;
  grid-template-columns: 1fr;
  gap: 14px;
  margin: 0.7rem 0 1.1rem;
}

.card{
  display: block;
  text-decoration: none !important; /* prevent underline on whole card */
  border: 1px solid rgba(0,0,0,0.14);
  border-radius: 12px;
  padding: 14px 14px 12px;
  background: rgba(255,255,255,0.80);
  cursor: pointer;
}

/* Keep card from changing typography on hover (some themes/browsers do this) */
.card:hover,
.card:focus{
  border-color: rgba(0,0,0,0.22);
  text-decoration: none !important;
}

/* Make ONLY the title look like a hyperlink (blue) */
.card-title{
  font-size: 1.05rem;
  font-weight: 700;
  margin: 0 0 0.35rem;
  color: #0969da;              /* GitHub-like link blue */
  text-decoration: underline;  /* hyperlink look */
}

/* On hover, keep title hyperlink feel consistent */
.card:hover .card-title,
.card:focus .card-title{
  color: #0969da;
  text-decoration: underline;
}

/* Desc + meta should be clickable (since inside <a>), but not "link-like" */
.card-desc{
  margin: 0 0 0.55rem;
  opacity: 0.9;
  color: inherit;
  text-decoration: none;
  cursor: default; /* no pointer cursor on desc */
  font-weight: inherit;
  font-size: inherit;
}

.card-meta{
  font-size: 0.88rem;
  opacity: 0.75;
  color: inherit;
  text-decoration: none;
  cursor: default; /* no pointer cursor on meta */
  font-weight: inherit;
}

/* Neutralise any hover/visited styling that could affect desc/meta */
.card:link .card-desc,
.card:visited .card-desc,
.card:hover .card-desc,
.card:active .card-desc,
.card:focus .card-desc,
.card:link .card-meta,
.card:visited .card-meta,
.card:hover .card-meta,
.card:active .card-meta,
.card:focus .card-meta{
  color: inherit !important;
  text-decoration: none !important;
  font-weight: inherit !important;
  font-size: inherit !important;
}

.card-secondary{
  background: rgba(255,255,255,0.65);
}

/* Projects grid */
.projects{
  display: grid;
  grid-template-columns: 1fr;
  gap: 16px;
  margin: 0.8rem 0 1.1rem;
}

.project{
  display: block;
  text-decoration: none !important;
  border: 1px solid rgba(0,0,0,0.12);
  border-radius: 12px;
  padding: 12px;
  background: rgba(255,255,255,0.75);
  cursor: pointer;
}

.project:hover{
  border-color: rgba(0,0,0,0.20);
}

.project-title{
  margin: 0 0 0.6rem;
  font-weight: 700;
  opacity: 0.92;
  color: #0969da;
  text-decoration: underline;
}

.project img{
  width: 100%;
  height: auto;
  border-radius: 10px;
  display: block;
  border: 1px solid rgba(0,0,0,0.06);
}

/* Footer */
.footer-hr{
  border: none;
  height: 1px;
  background: rgba(0,0,0,0.12);
  margin: 1.4rem 0 0.9rem;
}

.footer-note{
  font-size: 10px;
  opacity: 0.75;
  margin: 0 0 0.6rem;
}

/* Wider screens: two-up layout for featured + projects */
@media (min-width: 920px){
  .cards{
    grid-template-columns: 1fr 1fr;
  }
  .projects{
    grid-template-columns: 1fr 1fr;
  }
}
</style>
