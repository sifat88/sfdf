# SFDF — The Strategic Financing Decision Framework

> A directional decision-support tool for early-stage tech founders choosing between bootstrapping and equity financing.

[![License: CC BY 4.0](https://img.shields.io/badge/Content-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![License: MIT](https://img.shields.io/badge/Code-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0-success)](https://github.com/sifat/sfdf/releases)

**🔗 Live tool:** [sifat.github.io/sfdf](https://sifat.github.io/sfdf)

---

## What it is

The SFDF is a structured reasoning aid for one of the hardest decisions an early-stage tech founder faces: should I bootstrap, or should I raise equity?

Most founders answer this by pattern-matching to recent stories or copying peers. The Framework replaces that habit with a directional reading on **fifteen contextual factors** organised across four dimensions, weighted by their evidentiary strength in the literature, and mapped to one of five recommendation zones from Strong Bootstrap to Strong Equity.

It is a *directional* tool, not a prescriptive algorithm. The output is a recommended zone, not a verdict.

## How it works

1. **Score** — Score each of 15 factors 1–5 based on your situation.
2. **Centre & sign** — Each score is centred (raw − 3) and signed by direction (Equity-favourable +, Bootstrap-favourable −).
3. **Aggregate** — Within each dimension, factor contributions are averaged. Dimension averages are weighted (Founder 0.25, Venture 0.30, Market 0.20, Strategic 0.25) to produce the Net Score.
4. **Read the zone** — Net Score maps to one of five zones along a −2.0 to +2.0 spectrum.

The full method is explained in [the three-page artifact](SFDF_Framework_3pages.pdf).

## What's in this repository

| File | What it is |
|---|---|
| `index.html` | The interactive web tool. Open in a browser, score 15 factors, get a live reading. No backend, no data collection — everything runs locally. |
| `SFDF_Framework_3pages.pdf` | The polished three-page artifact: Compass, Canvas, Method. |
| `SFDF_Scorer_v1.xlsx` | An Excel version of the scorer for offline use. |
| `SFDF_Decision_Brief_Handout.docx` | A printable handout for in-person use (e.g. with founders or in workshops). |
| `LICENSE-CONTENT.txt` | CC BY 4.0 — applies to the framework, the artifact, and all written content. |
| `LICENSE-CODE.txt` | MIT — applies to the source code (`index.html`, future scripts). |
| `CITATION.cff` | Citation metadata for academic use. |

## Theoretical foundations

The Framework rests on six anchors from the systematic literature review:

- **Agency Theory** — Jensen & Meckling (1976)
- **Resource Dependence Theory** — Pfeffer & Salancik (1978)
- **Financial Bootstrapping** — Winborg & Landström (2001)
- **Founder Choice** — Wasserman (2017)
- **VC Contracting** — Kaplan & Strömberg (2003)
- **Value-Add Beyond Capital** — Hellmann & Puri (2002)

Methodologically, the Framework was developed using Design Science Research (Hevner et al., 2004; Peffers et al., 2007) and is evaluated under the FEDS framework (Venable et al., 2016).

## Status & roadmap

- [x] **v1.0** — Initial release. Three-page artifact, Excel scorer, web tool.
- [ ] **v1.1** — Validation revisions following expert evaluation at the SIM Conference (Porto, May 2026).
- [ ] **v2.0** — Post-defense release with full evaluation findings.

## How to cite

If you use this framework in academic work or in advising founders, please cite:

```bibtex
@misc{sfdf2026,
  author       = {Rakibul Islam (Sifat)},
  title        = {SFDF — The Strategic Financing Decision Framework},
  year         = {2026},
  institution  = {Faculty of Engineering and Faculty of Economics, University of Porto (FEUP/FEP)},
  howpublished = {\url{https://github.com/sifat/sfdf}},
  note         = {MIETE Master's Dissertation. Version 1.0.}
}
```

A `CITATION.cff` file is also provided for tools that read structured citation metadata (Zotero, GitHub's "Cite this repository" feature, etc.).

## Contributing

This is an academic artifact released for the wider community. Contributions are welcome:

- **Substantive feedback on the framework itself** — open an issue tagged `framework`. If your venture, sector, or experience suggests a missing factor, a mis-categorised factor, or a wrong weight, please describe the case in detail.
- **Bug reports for the web tool** — open an issue tagged `bug`.
- **Translations** — open an issue tagged `translation`.
- **Pull requests** — fork the repo and submit a PR.

## A note on the limits of this tool

The SFDF is *directional*. Its output is a zone, not a verdict. Two founders with similar Net Scores may rationally arrive at different decisions because of context the framework cannot see. Final decisions belong with the founder and their advisors.

## License

- The **framework, the three-page artifact, and all written content** are released under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). You may share and adapt the work for any purpose, including commercially, provided you give appropriate credit.
- The **source code** (`index.html`, future scripts) is released under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

Developed as part of a master's dissertation in MIETE (Master's in Innovation and Technological Entrepreneurship) at FEUP/FEP, University of Porto.

Supervisor: Prof. José Miguel Oliveira.

The author is grateful to the founders and investors of the Porto startup ecosystem who participated in expert validation, and to the SIM Conference (Startup Investment Matching) for hosting the validation sessions.

---

*The Compass replaces pattern-matching with structured reasoning. What it gives you is a directional reading. What you do with that reading is still entirely yours.*
