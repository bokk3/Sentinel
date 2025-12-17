# I, Sentinel: Establishing Ethical Foundations for Defensive AI Systems

**Version:** 1.0.0  
**Status:** Final Draft  
**Author:** Boris Truyens et al.

## Project Overview

"I, Sentinel" is a research paper proposing a rigorous, technically implementable ethical framework for the deployment of high-speed autonomous defensive systems (e.g., hypersonic interceptors). It adapts the hierarchical structure of Asimov's Three Laws into a military-grade protocol that prioritizes "Distinction" and "Human Safety" over "Asset Protection" and "Survival."

## Repository Structure

- `paper/`: Contains the LaTeX source files for the final document.
  - `main.tex`: The primary entry point.
  - `sections/`: Individual chapter files (Introduction, Literature Review, Theoretical Framework, Analysis, Comparative Case Studies, Discussion, Conclusion).
  - `references.bib`: Bibliography (APA/Chicago style).
- `drafts/`: Early prose drafts and ruleset iterations.
- `sources/`: Raw research notes, including deep dives on IHL, Just War Theory, and Comparative Systems (Iron Dome, Aegis, Patriot).
- `plans/`: Project management and rigorous context definitions (`PROJECT_CONTEXT.md`).

## Building the Paper

The document is built using standard LaTeX.

### Prerequisites

- `pdflatex`
- `bibtex`
- `natbib` package

### Build Command

```bash
cd paper
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Key Contributions

1.  **The Sentinel Ruleset:** A 5-principle lexicographic hierarchy for autonomous engagement.
2.  **Machine Martyrdom:** The ethical obligation for a defensive system to self-destruct rather than risk collateral damage.
3.  **Fail Open Architecture:** The specific engineering requirement to default to inaction in the face of uncertainty (Distinction > Defense).
4.  **Comparative Analysis:** Detailed stress-testing against historical failures of the Iron Dome, Aegis, and Patriot systems.

## License

Proprietary Research. All Rights Reserved.
