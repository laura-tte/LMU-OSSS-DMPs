# Research Data Management (RDM) plans 

This repository contains the slides for the **Research Data Management (RDM) plan session** presented during the **LMU Open Science Summer School**. The slides are created with [Quarto](https://quarto.org/) and published via [GitHub Pages](https://pages.github.com/).

Author: Laura Meier ([0000-0003-1368-2306](https://orcid.org/0000-0003-1368-2306)), University Library of Ludwig-Maximilians-Universität in Munich

---

## Versions

Materials for different editions of the session are organized in year-specific folders (YYYY). Each folder contains the slides and resources for that year's session.

| Year	| Slides	| Summer School Website |
| ----	| ----	| ------------ |
| 2026 |	[View slides](https://laura-tte.github.io/LMU-OSSS-DMPs/2026/) | [LMU Open Science Summer School 2026](https://lmu-osc.github.io/Open-Science-Summer-School-2026/)


## Overview

The presentation covers:
- Key components of a Data Management Plan (DMP)
- Motivation to create a Data Management plan
- Tools and resources for creating effective DMPs

It includes interactive elements and is based on the (self-guided) OSC tutorial for [FAIR Research Data Management](https://lmu-osc.github.io/FAIR-Data-Management/).

## Workshop Goals

By the end of this session, participants will:
- Define what a Data Management Plan (DMP) is and explain its purpose
- Identify the key components typically included in a DMP
- Apply funder requirements when considering their own DMP
- Begin drafting their own DMP using RDMO

## Workshop Timeline

**Total Duration**: 1 hour (60 minutes)

| Time | Duration | Section | Content & Activities | Type |
|------|----------|---------|---------------------|------|
| 00:00 | 5 min | **Introduction** | Connection to [FAIR session](https://github.com/ree-gupta/osss-fair-rdm/tree/main): FAIR checklist, today's topics, introduce Particify  | Presentation |
| 00:05 | 10 min | **Part I: How to plan Data Management?** | DMP intro, components of a DMP | Presentation + Group work (using Particify) |
| 00:15 | 10 min | **Part II: Why bother planning your Data Management?** | Advantages of a DMP, Funder requirements, Improve answer for DFG checklist | Presentation + Group work (using Particify) |
| 00:25 | 30 min | **Part III: Tools that support you in planning** | DMP tools, Introduce RDMO, Create a DMP with RDMO | Presentation + Live Demo + Time to create a DMP|
| 00:55 | 5 min | **Wrap-Up** | University library: RDM services, recommend self-guided tutorial | Presentation |


## Repository Structure

```text
OSS-DMPs/ 
├── 2026/ 
│ ├── slides.qmd # Quarto presentation 
│ ├── images/ # Images used in the presentation 
| └── style.css # Custom CSS 
├── .github/ 
│ └── workflows/ # GitHub Actions workflows for deployment 
├── .gitignore 
├── LICENSE.md # License information 
├── CITATION.cff # Citation metadata 
└── README.md # This file
```

Future editions can be added as additional year-specific folders, for example 2027/, while previous versions remain available.

## How to View the Slides

The slides are published via **GitHub Pages** and can be accessed here:  

[2026](https://laura-tte.github.io/LMU-OSSS-DMPs/2026/)

## How to Build Locally

1. Install [Quarto](https://quarto.org/docs/get-started/) if you haven't already.

2. Clone this repository:

```bash
git clone https://github.com/laura-tte/LMU-OSSS-DMPs.git
cd LMU-OSSS-DMPs
```

3. Render a specific version

For example, to render the 2026 slides:

```bash
quarto render 2026/slides.qmd
```

Alternatively:

```bash
cd 2026
quarto render slides.qmd
```

4. Open the generated HTML file in your browser to view the presentation.

## License

The materials can be used, remixed, adapted and shared according to the [CC BY-SA 4.0 Licence](https://creativecommons.org/licenses/by-sa/4.0/). 

Please see LICENSE.md for details.