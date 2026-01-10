---
layout: default
title: Strategy Comparison Under Uncertainty — Norovirus Model
permalink: /norovirus-model/
---

<style>
/* Align with MSc + Thesis pages (single-column, minimal theme-friendly) */
.page-hero { margin: 1.2rem 0 1.8rem; }
.page-hero h1 { margin-bottom: 0.35rem; }
.page-hero .meta { margin: 0.55rem 0 1.05rem; font-size: 0.98rem; line-height: 1.4; color: rgba(0,0,0,0.78); }
.page-hero p { margin: 0.4rem 0 0.65rem; }
.page-hero .lead { padding-top: 0.85rem; border-top: 1px solid rgba(0,0,0,0.12); }

.badges { display:flex; flex-wrap:wrap; gap:0.45rem; margin:0.7rem 0 0.35rem; }
.badge {
  border: 1px solid rgba(0,0,0,0.15);
  border-radius: 999px;
  padding: 0.15rem 0.6rem;
  font-size: 0.85rem;
  opacity: 0.92;
}

.toc {
  border: 1px solid rgba(0,0,0,0.12);
  border-radius: 12px;
  padding: 12px 14px;
  background: rgba(255,255,255,0.7);
  margin-top: 12px;
}
.toc strong { display:block; margin-bottom: 6px; }
.toc a { text-decoration: none; }
.toc ul { margin: 0.35rem 0 0.2rem 1.05rem; }
.toc li { margin: 0.2rem 0; }

.grid { display:grid; grid-template-columns: 1fr; gap: 16px; margin: 18px 0 22px; }
.grid h3 { margin: 1.6rem 0 0.6rem; font-size: 1rem; font-weight: 600; opacity: 0.82; }

.card {
  border: 1px solid rgba(0,0,0,0.15);
  border-radius: 12px;
  padding: 16px 16px 14px;
  background: rgba(255,255,255,0.8);
}
.card h2 { margin: 0 0 0.45rem; font-size: 1.15rem; }
.card p { margin: 0.4rem 0 0.6rem; }
.card ul { margin: 0.35rem 0 0.2rem 1.1rem; }
.card li { margin: 0.25rem 0; }

.callout {
  border-left: 4px solid rgba(0,0,0,0.18);
  padding: 0.25rem 0 0.25rem 0.9rem;
  margin: 0.7rem 0 0.2rem;
  opacity: 0.98;
}

.note { font-size: 0.95rem; opacity: 0.88; }

.figure {
  border: 1px solid rgba(0,0,0,0.12);
  border-radius: 12px;
  background: rgba(255,255,255,0.7);
  padding: 12px;
}
.figure img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  display: block;
}
.figure figcaption {
  margin-top: 10px;
  font-size: 0.95rem;
  line-height: 1.45;
}
.figure figcaption strong { display:block; margin-bottom: 4px; }
.small { font-size: 0.92rem; opacity: 0.9; }

hr.divider {
  border: 0;
  height: 1px;
  background: rgba(0,0,0,0.12);
  margin: 12px 0 6px;
}
</style>

<div class="page-hero">
  <h1>Strategy Comparison Under Uncertainty: A Quantitative Decision Model</h1>

  <div class="meta">
    Excel-based model · Data visualisation + workflow automation · Strategy comparison for prioritisation decisions
  </div>

  <p class="lead">
    This project applies quantitative modelling and data visualisation to compare alternative intervention strategies under uncertainty.
    Rather than optimising price, the model is designed to support <strong>strategy and feature prioritisation</strong> by evaluating trade-offs, dominance, and robustness across competing options.
    Although developed in a public health context, the decision logic maps to digital health platform challenges: selecting among alternative designs, rollout strategies, or investments under constrained resources.
  </p>

  <div class="badges">
    <span class="badge">Strategy comparison</span>
    <span class="badge">Decision framing</span>
    <span class="badge">Scenario analysis</span>
    <span class="badge">Sensitivity analysis</span>
    <span class="badge">Excel dashboards</span>
    <span class="badge">VBA automation</span>
  </div>

  <p class="note">
    <strong>What this demonstrates:</strong> structured decision framing, comparable option evaluation, scenario-based robustness testing, and reproducible analytics workflows that translate quantitative outputs into decision-ready insights.
  </p>

  <div class="toc">
    <strong>On this page</strong>
    <ul>
      <li><a href="#framing">Executive framing</a></li>
      <li><a href="#capabilities">Capabilities showcased</a></li>
      <li><a href="#visuals">Decision visuals (screenshots)</a></li>
      <li><a href="#transfer">How this applies to digital health platforms</a></li>
    </ul>
  </div>
</div>

<div class="grid">

  <h3 id="framing">Executive framing</h3>
  <div class="card">
    <h2>What the model is used for</h2>
    <p>
      This model is built to support structured comparison of strategy options when outcomes are uncertain and resources are constrained.
      It enables prioritisation by showing which options are consistently favourable, which are dominated, and which remain sensitive to key assumptions.
    </p>

    <div class="callout">
      <p><strong>Important boundary:</strong> This is not positioned as a pricing tool. It is a strategy comparison framework that can be translated into product / feature prioritisation decisions.</p>
    </div>

    <ul>
      <li><strong>Decision question:</strong> Which strategy is the most defensible choice under uncertainty, and what conditions change that conclusion?</li>
      <li><strong>Decision output:</strong> a small set of “recommendation-ready” comparisons, plus a transparent view of uncertainty drivers</li>
      <li><strong>Primary value:</strong> decision clarity and robustness, not parameter precision</li>
    </ul>
  </div>

  <h3 id="capabilities">Capabilities showcased</h3>
  <div class="card">
    <h2>Quantitative and analytical workflow</h2>
    <ul>
      <li><strong>Strategy comparison:</strong> structured evaluation of alternative options, including dominance and trade-off interpretation</li>
      <li><strong>Robustness testing:</strong> scenario and sensitivity analysis to understand how results shift under plausible conditions</li>
      <li><strong>Decision communication:</strong> visual outputs designed as decision artefacts, not academic tables</li>
    </ul>
    <p class="note">
      In platform terms: this mirrors comparing feature bundles, rollout strategies, or partnership models under uncertain adoption and constrained development capacity.
    </p>
  </div>

  <div class="card">
    <h2>Data visualisation and automation (Excel + VBA)</h2>
    <ul>
      <li><strong>Visual storytelling:</strong> dashboards and charts built to make comparisons legible to non-technical stakeholders</li>
      <li><strong>Reproducibility:</strong> VBA used to standardise repeated scenario runs and update visuals consistently</li>
      <li><strong>Efficiency:</strong> reduced manual handling for multi-visual outputs, improving consistency and auditability</li>
    </ul>
    <p class="note">
      VBA is used for workflow automation (e.g., repeated copy/paste and visual refresh across scenarios), not for complex statistical computation.
    </p>
  </div>

  <h3 id="visuals">Decision visuals (screenshots)</h3>

  <div class="card">
    <h2>How to read the visuals</h2>
    <p>
      The following outputs are presented as <strong>decision artefacts</strong>.
      Each view supports comparison, prioritisation, and robustness assessment—core tasks in platform strategy, product development, and resource allocation.
    </p>
  </div>

  <!-- Replace image paths with your actual screenshot locations -->
  <figure class="figure">
    <img src="/assets/img/norovirus/strategy-comparison.png" alt="Strategy comparison overview (placeholder)">
    <figcaption>
      <strong>Strategy comparison overview</strong>
      Side-by-side comparison of alternative strategies across cost and outcome dimensions, enabling prioritisation decisions by identifying dominated options and high-value trade-offs under uncertainty.
      <div class="small">Signals: structured comparison, decision framing, prioritisation logic.</div>
    </figcaption>
  </figure>

  <figure class="figure">
    <img src="/assets/img/norovirus/ce-plane.png" alt="Cost-effectiveness plane (placeholder)">
    <figcaption>
      <strong>Strategy dominance and trade-off mapping</strong>
      Visual mapping of competing strategies showing relative trade-offs between incremental impact and incremental resource use. This view highlights dominated strategies and identifies options that offer favourable impact–cost balance.
      <div class="small">Platform analogy: feature impact versus development effort trade-offs.</div>
    </figcaption>
  </figure>

  <figure class="figure">
    <img src="/assets/img/norovirus/ceac.png" alt="Cost-effectiveness acceptability curve (placeholder)">
    <figcaption>
      <strong>Robustness of strategy under uncertainty</strong>
      Probability that each strategy remains favourable as assumptions change, supporting robust decision-making rather than reliance on single-point estimates.
      <div class="small">Signals: uncertainty thinking, scenario planning, defensible decision logic.</div>
    </figcaption>
  </figure>

  <figure class="figure">
    <img src="/assets/img/norovirus/dsa.png" alt="Sensitivity analysis (placeholder)">
    <figcaption>
      <strong>Sensitivity of outcomes to key assumptions</strong>
      Sensitivity analysis highlighting which assumptions most influence outcomes, helping decision-makers understand risk drivers and prioritise further investigation or mitigation.
      <div class="small">Signals: risk drivers, diagnostic thinking, prioritisation of what to validate.</div>
    </figcaption>
  </figure>

  <h3 id="transfer">How this applies to digital health platforms</h3>
  <div class="card">
    <h2>Translation to platform strategy and prioritisation</h2>
    <p>
      While the domain context here is vaccination strategy, the decision logic generalises to platform decision-making where you must choose among competing initiatives under uncertainty.
      The value is in structuring trade-offs and making uncertainty explicit.
    </p>

    <hr class="divider"/>

    <ul>
      <li><strong>Prioritisation:</strong> compare initiatives by expected impact, resource requirements, and robustness across plausible assumptions</li>
      <li><strong>Strategy iteration:</strong> use scenarios to stress-test decisions against adoption variability, operational constraints, or shifting user conditions</li>
      <li><strong>Decision transparency:</strong> present outputs that make “why this option” and “what would change it” easy to communicate</li>
      <li><strong>Measurement mindset:</strong> identify which inputs are decision-sensitive and should be measured or monitored more rigorously</li>
    </ul>
  </div>

  <div class="card">
    <h2>Related pages</h2>
    <ul>
      <li><a href="/msc-health/">MSc overview (platform analysis framing) →</a></li>
      <li><a href="/thesis/">Master’s thesis (evidence synthesis and implications) →</a></li>
    </ul>
    <p class="note">
      If you want to share the model itself, you can also add a link to a hosted PDF summary or a downloadable file (optional).
    </p>
  </div>

</div>
