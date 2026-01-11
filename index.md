## Portfolio

<p class="page-intro"> 
I translate health-domain evidence and quantitative analysis into decision support for digital health platforms —
with a focus on adoption constraints, systems context, and prioritisation.
</p>

<div class="section-title">Featured: Academic work applied to platform analysis</div>

<div class="cards">
  <div class="card">
    <a class="card-hit" href="/msc-health/" aria-label="MSc → Platform Strategy Lens"></a>
    <div class="card-title">MSc → Platform Strategy Lens</div>
    <div class="card-desc">
      How health economics, systems thinking, and research methods translate into platform and business analysis
      for healthcare decisions.
    </div>
    <div class="card-meta">University of Groningen · Distinction</div>
  </div>

  <div class="card">
    <a class="card-hit" href="/thesis/" aria-label="Master’s Thesis → Evidence for Platform Decisions"></a>
    <div class="card-title">Master’s Thesis → Qualitative Evidence for Platform Decisions</div>
    <div class="card-desc">
      Evidence synthesis on why digital health interventions succeed or fail across contexts —
      and what this implies for adoption, implementation, and scaling.
    </div>
    <div class="card-meta">Systematic literature review · Decision-oriented framing</div>
  </div>
</div>

<div class="section-title">Secondary: Quantitative decision-support and modelling</div>

<div class="card card-secondary">
  <a class="card-hit" href="/norovirus-model/" aria-label="Norovirus Modelling → Strategy Comparison"></a>
  <div class="card-title">Norovirus Modelling → Strategy Comparison</div>
  <div class="card-desc">
    Excel-based quantitative analysis with visual outputs to compare strategies and support prioritisation
    decisions under uncertainty.
  </div>
  <div class="card-meta">Excel · Visualisation · VBA automation</div>
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
.card{
  position: relative;
  display: block;
  border: 1px solid rgba(0,0,0,0.14);
  border-radius: 12px;
  padding: 14px 14px 12px;
  background: rgba(255,255,255,0.80);
}

/* Invisible link that makes the whole card clickable */
.card-hit{
  position: absolute;
  inset: 0;
  border-radius: 12px;
  text-decoration: none;
  z-index: 1;
}

/* Ensure content sits above the overlay link */
.card-title,
.card-desc,
.card-meta{
  position: relative;
  z-index: 2;
}

/* Cursor behavior: pointer on card, normal on text */
.card{ cursor: pointer; }
.card-title, .card-desc, .card-meta{ cursor: default; }

/* Remove any default link styling */
.card-hit:link,
.card-hit:visited,
.card-hit:hover,
.card-hit:active{
  color: inherit;
  text-decoration: none;
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
}

.project:hover{
  border-color: rgba(0,0,0,0.20);
}

.project-title{
  margin: 0 0 0.6rem;
  font-weight: 700;
  opacity: 0.92;
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
  .cards .card-secondary{
    grid-column: span 1;
  }
  .projects{
    grid-template-columns: 1fr 1fr;
  }
}
</style>
