# SUEWS Community Hackathon — Submission Template

Template repository for the **SUEWS Community Hackathon** (24 June 2026, UCL East), part of the UCL RDR Annual Conference.

> **Skeleton / work in progress.** The structure is in place; the city dataset and the heat-to-risk bridge function are added at kickoff on 24 June. See the participant Task Brief for the full guide.

## What this is

Each participant or team creates their own repository **from this template** — use the green **"Use this template"** button, or:

```bash
gh repo create UMEP-dev/<your-name> --template UMEP-dev/suews-hackathon-template --public --clone
```

Your repository is what we judge.

## The task in one line

Use the **suews-agent** to produce a heat-hazard layer for the focus city, translate it into a socio-economic heat-risk indicator, and say plainly where the science holds and where it breaks.

## Repository layout

- `data/` — the city dataset (land cover, building form, population, anthropogenic heat, forcing). Loaded at kickoff.
- `bridge/heat-to-risk.md` — the documented heat-to-risk bridge function. Provided on the day.
- `analysis/` — your suews-agent runs, configuration, and outputs.
- `transcripts/` — your exported AI session transcripts (judged evidence — save as you go).
- `docs/` — your public **GitHub Pages** showcase site (judged; must be public).

## Get started

1. Create your repo from this template.
2. Install the suews-agent and your AI coding tool (see the onboarding pack).
3. Run a practice submission before the day.

## Links

- suews-agent: https://github.com/UMEP-dev/suews-agent
- SUEWS docs: https://docs.suews.io/
- GitHub Pages docs: https://docs.github.com/pages

## Citing SUEWS

Your submission must cite SUEWS (part of the Scientific soundness criterion):

- Järvi, L., Grimmond, C.S.B. & Christen, A. (2011). The Surface Urban Energy and Water Balance Scheme (SUEWS): Evaluation in Los Angeles and Vancouver. *Journal of Hydrology*, 411(3–4), 219–237. https://doi.org/10.1016/j.jhydrol.2011.10.001
- Ward, H.C., Kotthaus, S., Järvi, L. & Grimmond, C.S.B. (2016). Surface Urban Energy and Water Balance Scheme (SUEWS): Development and evaluation at two UK sites. *Urban Climate*, 18, 1–32. https://doi.org/10.1016/j.uclim.2016.05.001

For the version you run, follow the up-to-date [How to cite SUEWS](https://docs.suews.io/stable/#how-to-cite-suews).

## Acknowledgements

Part of **SUEWS-Next**, supported by the ERC Synergy Grant **urbisphere** (855505).
