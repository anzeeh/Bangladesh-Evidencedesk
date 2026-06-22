# Bangladesh Evidence Desk

An interactive dashboard of impact evaluations and systematic reviews on Bangladesh, sourced from the [International Initiative for Impact Evaluation (3ie)](https://www.3ieimpact.org/evidence-hub/publications/impact-evaluations) repository.

Built and maintained to support evidence-informed programming and donor coordination.

---

## What it contains

V1: 
**212 studies** published between 2022 and 2026, covering:

- 154 impact evaluations and 58 systematic reviews
- 87 randomised controlled trials (RCTs), plus quasi-experimental designs, DiD, PSM, IV, and RDD studies
- 15 thematic areas including nutrition, WASH, agriculture, climate, financial inclusion, labour, women's empowerment, and early childhood development
- Direct links to original sources (DOI / publisher pages)

---

## How to use it

Open `index.html` in any modern browser — no server, installation, or internet connection required after the initial load (fonts load from Google Fonts on first open).

**Filtering:** Use the left rail to filter by theme, study type, method, year, or publication status. Filters can be combined. Click any theme tag on a card to filter to that theme directly.

**Landscape view:** The summary panel at the top of results shows the composition of whatever you have filtered to — themes, methods, and year spread update live.

**Source access:** Every card has an **Open source ↗** link to the original publication, plus an expandable abstract.

---

## Thematic classification

Themes and methods are assigned automatically from titles and abstracts using keyword scoring. Each study receives one **primary theme** and up to three secondary themes. These are analytical aids for navigation — they are not official 3ie classifications.

| Theme | Studies |
|-------|---------|
| Nutrition & Diet | 48 |
| Agriculture & Food Security | 35 |
| WASH | 22 |
| Climate, Energy & Environment | 19 |
| Health Systems & Disease Control | 17 |
| Financial Inclusion & Cash | 16 |
| Maternal & Child Health | 12 |
| Labour, Jobs & Garment Sector | 12 |
| Child Marriage & Social Norms | 7 |
| Women's Empowerment & Gender | 7 |
| Education & Skills | 6 |
| Early Childhood Development | 5 |
| Social Protection & Safety Nets | 4 |
| Governance & Service Delivery | 1 |
| Trade & Macroeconomy | 1 |

---

## Updating the dashboard

3ie updates its repository periodically. To refresh this dashboard:

1. Go to [3ie's evidence hub](https://www.3ieimpact.org/evidence-hub/publications/impact-evaluations), run the Bangladesh search, and export a new Excel file and then refresh the dashboard

---

## Data sources and caveats

- **Source:** [3ie Impact Evaluation Repository](https://www.3ieimpact.org/evidence-hub/publications/impact-evaluations), Bangladesh search, exported June 2025
- **Coverage:** Studies published 2022–2026 that 3ie has indexed; the repository does not capture all Bangladesh evaluations published in this period
- **IATI / donor tagging:** Not included — this dashboard covers academic and grey literature evaluations, not project-level donor activity data
- **Classification accuracy:** Keyword-based theme and method tagging is approximate. Studies with limited or no abstract may be miscategorised

---

## Technical notes

The dashboard is a single self-contained HTML file with all data embedded. It uses React 18 (via CDN) and Babel Standalone for in-browser JSX compilation. No build step, no dependencies to install, no backend.

The "Ask the evidence" AI feature visible in the Claude.ai version of this tool is not included here, as it requires Anthropic API authentication that cannot be safely embedded in a public file.

---

*Classification and synthesis are analytical aids, not official 3ie labels*

This is a test mock-up to help use evidence that exists out there, the idea is to add more to the repository from other sources
