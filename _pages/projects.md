---
permalink: /projects/
title: "Projects"
author_profile: true
---

## GlassNest — Transparent Rental Intelligence
*A Glassdoor for the rental market*

Rental decisions are made in the dark: listings hide their flaws, landlords are rarely reviewed, and tenants often sign contracts knowing less about a £20,000+ commitment than they would about a small online purchase. GlassNest is designed to fix that information asymmetry.

GlassNest continuously scrapes 100+ UK areas across Rightmove and SpareRoom, enriches each property with EPC ratings, crime data, flood risk, transport access, and air quality from government APIs, then overlays tenant-submitted structured reviews. A local LLM pipeline extracts insights, computes landlord scores, and generates area-level intelligence.

**Flock access model:** contribute a review to unlock all reviews — a fair-exchange model rather than a paywall, designed to solve the cold-start problem while keeping the product useful for renters.

**Tech:** Python 3.12, FastAPI async, SQLAlchemy async, SQLite/PostgreSQL, Jinja2, Leaflet UI, Playwright scraping, async enrichment workers, LLM analysis pipeline, and multi-agent development workflows coordinated through an Obsidian context layer.

[glass-nest.vercel.app](https://glass-nest.vercel.app)

---

## “Hinge for M&A” — Winner, Multi-agent Hackathon London

A multi-agent system for researching acquisition targets for M&A firms. Agents autonomously browse the web to gather verified information about target companies, populate structured databases in Senso, and surface the most promising matches through a Hinge-like swiping interface — combining M&A research depth with consumer-grade UX.

The project won the Multi-agent Hackathon London.
