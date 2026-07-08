# Opti-Copilot

**An AI-assisted Design of Experiments (DOE) advisor for bioprocess and fermentation optimisation.**

---

## Overview

Opti-Copilot is a decision-support concept built to guide experimental scientists through structured, evidence-informed process optimisation — from deciding which parameters are worth testing, to selecting an appropriate experimental design, to knowing when and how to scale up.

It is not intended to replace scientific judgement. Instead, every recommendation Opti-Copilot produces is paired with a stated rationale, so decisions can be reviewed, challenged, and adjusted by the scientist running the work.

## The problem it addresses

Bioprocess optimisation projects commonly lose time to a handful of recurring issues:

- Uncertainty about which parameters genuinely warrant experimental attention
- Literature review that is slow, inconsistent, or skipped under deadline pressure
- Experimental designs chosen by habit rather than by a clear, repeatable rationale
- No structured process for deciding when to scale up versus continue optimising at bench scale
- Optimisation efforts that stall after a single round, with no defined next step

## How Opti-Copilot approaches this

The tool is structured as a guided, six-stage workflow:

1. **Define the problem** — specify the target outcome and candidate parameters
2. **Capture system context** — record the organism, strain, and process details that give later steps meaning
3. **Audit parameters** — an evidence-informed review of which parameters are worth testing
4. **Screening** — determine whether a preliminary screening study is needed, and assess results if one already exists
5. **Scale decision** — recommend an experimental scale appropriate to the current stage of the work
6. **Design & model selection** — recommend a suitable experimental design method and generate a corresponding experiment plan

The workflow is iterative: results from one optimisation cycle inform the scope and direction of the next.

## Status

This repository hosts a **reference dashboard** describing Opti-Copilot's workflow and decision structure. It is documentation of the system's design and reasoning approach — not a running application — and it does not process, store, or display any experimental data.

## Viewing the dashboard

Open `index.html` directly in any browser, or view it live via GitHub Pages once enabled for this repository (**Settings → Pages**).

## Contact

For questions about this project, please reach out directly.
