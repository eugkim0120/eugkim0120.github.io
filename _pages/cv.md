---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Eugene Kim

London, UK · US citizen · [LinkedIn](https://www.linkedin.com/in/ekim2002) · [GitHub](https://github.com/eugkim0120)

Quantitative developer and researcher working across energy markets, dispatch optimisation, machine learning, statistical modelling, and scientific computing.

## Research and education

<div class="institution-heading"><img class="institution-logo" src="/images/logos/oxford.svg" alt="University of Oxford logo"><h3>University of Oxford — Visiting Fellow</h3></div>
*May 2026 – Present*

Researching **AI surrogate modelling for inertial confinement fusion** with Prof. Peter Norreys. The work focuses on building compute-efficient neural operator models that can approximate expensive physics simulations, making it faster to explore high-dimensional fusion design spaces and reason about reaction dynamics without running a full simulation for every candidate scenario.

- Developing surrogate models for PDE-driven fusion simulations, with an emphasis on accuracy, stability, and computational efficiency.
- Exploring neural operators and related scientific ML architectures for learning mappings between physical inputs and simulated plasma / fusion outputs.
- Using surrogate models to accelerate parameter sweeps, sensitivity analysis, and optimisation loops that would otherwise be constrained by expensive first-principles simulation.
- Connecting this research with prior work using Bayesian optimisation to identify regions of interest in nuclear-fusion simulation parameter space.

<div class="institution-heading"><img class="institution-logo" src="/images/logos/oxford.svg" alt="University of Oxford logo"><h3>University of Oxford — MPhys Master of Physics</h3></div>
*Sep 2020 – Jun 2024*

- Upper Second-Class Honours.
- Master's thesis: *Atomic Trapping and Imaging of Ultracold Quantum Dipolar Gases*.
- Implemented Python edge-detection algorithms to classify the quality of circular atomic traps.
- Co-authored a nuclear fusion simulation paper in *Plasma Physics and Controlled Fusion*: *Energy gain of wetted-foam implosions with auxiliary heating for inertial fusion studies* ([DOI: 10.1088/1361-6587/ad15ee](https://doi.org/10.1088/1361-6587/ad15ee)), using Bayesian optimisation to identify regions of interest in PDE-based simulation parameter space.
- Events Director, Oxford Physics Society; outreach at Oxford Energy Society.

## Experience

<div class="institution-heading"><img class="institution-logo" src="/images/logos/ttep.svg" alt="TTEP logo"><h3>TTEP (TotalEnergies & EP) — Quantitative Developer & Researcher</h3></div>
*Feb 2026 – Present*

- Built cross-asset dispatch-optimisation software used to optimise decisions across a roughly **£300m portfolio**, spanning a 3GW CCGT, 400MW Battery Energy Storage System (BESS), and 400MW biomass assets across GB day-ahead, intraday, balancing, and ancillary-services markets.
- Deployed price-forecasting models using XGBoost and LightGBM, plus an NLP gas-price-sentiment signal, into the trading stack.
- Built a MILP-based BESS dispatch optimiser with Bayesian parameter tuning.
- Built internal AI-agent tooling and context layers using MCP-style context, Microsoft Fabric data management, and Git automation for quant development workflows.
- Migrated legacy Excel workflows to Python with FastAPI and Streamlit dashboards; improved core pipeline runtime through caching, Polars, and switching MILP solving from CBC to HiGHS.

<div class="institution-heading"><img class="institution-logo" src="/images/logos/aurora-energy-research.svg" alt="Aurora Energy Research logo"><h3>Aurora Energy Research — Energy Modelling Analyst</h3></div>
*Sep 2024 – Feb 2026*

- Built the company's first BESS backtesting dashboard, automating data pipelines via ENTSO-E and TSO APIs.
- Recalibrated degradation, round-trip efficiency, and dispatch methodology, with P&L attribution for client analysis.
- Built company-wide dashboards visualising fundamentals power-model outputs, including day-ahead KPI backtesting and merit-order curves for aFRR markets.
- Co-designed and deployed an mFRR price model using autoregressive modelling and maximum likelihood estimation with NIV-linked drivers.
- Evaluated competitor flow-based optimisation models and developed a KPI scorecard.

<div class="institution-heading"><img class="institution-logo institution-logo--dark" src="/images/logos/capitox.webp" alt="CapitOx logo" style="background:#222;border-color:rgba(255,255,255,.25);"><h3>Capitox — Carbon Emissions Consultant</h3></div>
*Oct 2022 – Dec 2022*

- Built a Scope 3 carbon-emissions and risk model used in the client's FCA and PSR Net Zero Transition Plan report.

## Projects

### GlassNest — A Glassdoor for rentals

Rental decisions are made in the dark — listings hide their flaws, landlords are never reviewed. GlassNest fixes this by combining continuous property scraping (100+ UK areas, Rightmove + SpareRoom), enrichment from government data sources (EPC, crime, flood, transport, air quality), and structured tenant reviews analysed by a local LLM pipeline.

Built with Python 3.12, FastAPI, async SQLAlchemy, Leaflet maps, Playwright scrapers, and a multi-agent orchestration system. Contribution-based (flock) access model. Deployed at [glass-nest.vercel.app](https://glass-nest.vercel.app).

### "Hinge for M&A" — Winner, Multi-agent Hackathon London

Autonomous multi-agent system that researches M&A acquisition targets: agents browse the web for verified intelligence, populate structured databases in Senso, and surface matches through a Hinge-like swiping interface. Winner of the Multi-agent Hackathon London.

## Technical skills

- **Languages:** Python, GAMS, MATLAB
- **Data engineering:** AWS, Microsoft Fabric, Snowflake, Databricks, SQL
- **ML models:** XGBoost, LightGBM, Lasso/Ridge Regression, reinforcement learning, Bayesian optimisation
- **Statistical methods:** stochastic and scenario optimisation, GARCH, ARIMA, MCMC, MLE
- **Quantitative finance:** derivative pricing, Black-Scholes, Heath-Jarrow-Morton, stochastic calculus
- **Software engineering:** GitHub, Azure DevOps, Linux / Windows virtual machines, FastAPI, Streamlit
- **Certificates:** Columbia University Financial Risk Management; IBM Machine Learning

## Service and leadership

- Events Director, Oxford Physics Society.
- Outreach, Oxford Energy Society.
