# eo2cube-origin ![live](https://img.shields.io/badge/status-live-brightgreen?style=flat&logo=github)

![eo2cube - redesigned](img/github_hero.png)

A static rebuild and redesign of [eo2cube.org](https://eo2cube.org/) — the Earth Observation Data Cube platform of the Earth Observation Research Cluster (EORC), University of Würzburg.

---

## Background

Between 2020 and 2021, I worked at the EORC and built the original eo2cube website from scratch. The visual identity is my own work. The site content belongs to the EORC.

After my time there, the site was left without dedicated maintenance. It occasionally breaks and drifts further from the original design intent. Rather than watch something I put considerable effort into slowly deteriorate, I decided to preserve it properly.

The live site runs on WordPress with the Divi page builder. A combination that, in my view, is a significant reason for its sluggishness and fragility. Divi generates heavy, bloated markup, loads large JavaScript bundles regardless of whether they are needed, and makes long-term maintenance difficult without constant hands-on attention. The result is a site that feels slow, breaks under neglect, and is harder to keep consistent than it should be.

What started as a straightforward archival exercise turned into something more - a full redesign. 
Pure HTML and CSS, no frameworks, no dependencies - Pages load instantly. It is faithful to the original design language while taking it further than the WordPress/Divi stack ever could.

I am happy with the result.

---

## Design Credit

Visual design was created by **Pawel Kluter**.  
Institutional content belongs to the Department of Remote Sensing, University of Würzburg.

---

## Versions

| Version | Stack | Description | Link |
|---|---|---|---|
| Original | WordPress + Divi | Live production site, built 2020–2021 | [eo2cube.org](https://eo2cube.org) |
| This repo | HTML5 + CSS3 | Static rebuild and redesign, hosted on GitHub Pages | [GitHub Pages](https://kluter.github.io/eo2cube-origin/) |