---
permalink: /
title: "Eugene Kim"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm a quantitative developer and researcher based in London. I'm a US citizen, working at the intersection of energy markets, optimisation, machine learning, and physics-informed modelling.

I currently work as a **Quantitative Developer & Researcher at TTEP (TotalEnergies & EP)**, building tools for live trading and research across GB power markets. My recent work includes dispatch optimisation for large-scale generation and storage portfolios, price forecasting models, NLP market signals, and internal AI-agent tooling for quant development workflows.

## Research and education

<div class="institution-heading"><img class="institution-logo" src="/images/logos/oxford.svg" alt="University of Oxford logo"><h3>University of Oxford — Visiting Fellow</h3></div>
*May 2026 – Present*

I'm researching **AI surrogate modelling for inertial confinement fusion** with Prof. Peter Norreys. The work focuses on compute-efficient neural operator models that approximate expensive physics simulations, enabling faster exploration of high-dimensional fusion design spaces, parameter sweeps, and optimisation workflows.

<div class="institution-heading"><img class="institution-logo" src="/images/logos/oxford.svg" alt="University of Oxford logo"><h3>University of Oxford — MPhys Master of Physics</h3></div>
*Sep 2020 – Jun 2024*

Upper Second-Class Honours. Thesis: *Atomic Trapping and Imaging of Ultracold Quantum Dipolar Gases*, including Python-based edge detection algorithms for classifying circular atomic traps.

Co-authored a nuclear fusion simulation paper: *Energy gain of wetted-foam implosions with auxiliary heating for inertial fusion studies*, published in *Plasma Physics and Controlled Fusion* (Vol. 66, 025005, 2024). The study used Bayesian optimisation to identify regions of interest in PDE-based simulation parameter space.

## Selected experience

<div class="institution-heading"><img class="institution-logo" src="/images/logos/ttep.svg" alt="TTEP logo"><h3>TTEP (TotalEnergies & EP) — Quantitative Developer & Researcher</h3></div>
*Feb 2026 – Present*

I build production trading and research software for a portfolio spanning a 3GW CCGT, 400MW Battery Energy Storage System (BESS), and 400MW biomass asset base. Recent work includes live dispatch-optimisation tooling, deployed forecasting models, NLP gas-price sentiment signals, and Python/FastAPI/Streamlit replacements for legacy Excel workflows.

<div class="institution-heading"><img class="institution-logo" src="/images/logos/aurora-energy-research.svg" alt="Aurora Energy Research logo"><h3>Aurora Energy Research — Energy Modelling Analyst</h3></div>
*Sep 2024 – Feb 2026*

I built BESS backtesting and market-modelling dashboards, automated data pipelines using ENTSO-E and TSO APIs, developed KPI backtesting and merit-order visualisations, and co-designed mFRR price modelling using AR and MLE methods.

<div class="institution-heading"><img class="institution-logo institution-logo--dark" src="/images/logos/capitox.webp" alt="CapitOx logo" style="background:#222;border-color:rgba(255,255,255,.25);"><h3>Capitox — Carbon Emissions Consultant</h3></div>
*Oct 2022 – Dec 2022*

Built a Scope 3 carbon-emissions and risk model used in the client's FCA and PSR Net Zero Transition Plan report.

## Focus areas

- **Energy trading and optimisation:** cross-asset dispatch optimisation across CCGT, BESS, biomass, day-ahead, intraday, balancing, and ancillary-services markets.
- **Machine learning and forecasting:** XGBoost, LightGBM, NLP sentiment signals, Bayesian optimisation, and statistical price models.
- **Quantitative modelling:** stochastic and scenario optimisation, time-series methods, MLE, MCMC, and quantitative finance foundations.
- **Physics and scientific computing:** Oxford MPhys background, ultracold atom imaging, nuclear fusion simulation, and neural operator models for inertial confinement fusion.
- **AI developer tooling:** context layers, MCP-style workflows, data management, and Git automation for safer and faster technical work.

## Projects

**GlassNest — Transparent Rental Intelligence**
*A Glassdoor for the rental market*

Rental decisions are made in the dark — listings hide their flaws, landlords are never reviewed, and tenants sign contracts knowing less about a £20,000+ commitment than they would about a £20 Amazon purchase. GlassNest fixes this.

The platform continuously scrapes 100+ UK areas across Rightmove and SpareRoom, enriches every property with EPC ratings, crime data, flood risk, transport access, and air quality from government APIs, then overlays tenant-submitted structured reviews. A local LLM pipeline extracts insights, computes landlord scores, and generates area-level intelligence.

**Flock access model** — contribute a review to unlock all reviews. Fair exchange rather than a paywall, designed to solve the cold-start problem without charging users.

Tech: Python 3.12, FastAPI (async), SQLAlchemy async, SQLite/PostgreSQL, Jinja2 + Leaflet UI, LLM analysis pipeline, Playwright-based scraper, async enrichment workers. Multi-agent architecture with Claude Code agents coordinating through an Obsidian vault for task orchestration.

[glass-nest.vercel.app](https://glass-nest.vercel.app)

---

**"Hinge for M&A" — Winner, Multi-agent Hackathon London**

A multi-agent system that researches acquisition targets for M&A firms. Agents autonomously browse the web to gather verified information about target companies, populate structured databases in Senso, and surface the most promising matches through a Hinge-like swiping interface — combining M&A research depth with consumer-grade UX. Winner of the Multi-agent Hackathon London.

## Technical toolkit

- **Languages:** Python, GAMS, MATLAB
- **Data engineering:** AWS, Microsoft Fabric, Snowflake, Databricks, SQL
- **ML / modelling:** XGBoost, LightGBM, Lasso/Ridge, reinforcement learning, Bayesian optimisation
- **Statistics:** stochastic optimisation, scenario optimisation, GARCH, ARIMA, MCMC, MLE
- **Software:** FastAPI, Streamlit, GitHub, Azure DevOps, Linux / Windows VMs

For a fuller summary, see my [CV](/cv/).
