# Wavelet & MESA — Spectral Analysis for Predictive Maintenance
## PMLG Talk · May 2026

This repository contains all materials for the PMLG talk on using **Maximum Entropy Spectral Analysis (MESA)** and **Wavelet Transforms** for predictive maintenance of rotating machinery.

## Contents

| File | Description |
|------|-------------|
| `Wavelet_MESA_PdM_PMLG.ipynb` | Main Jupyter notebook with full analysis, code, and visualizations |
| `pmlg_talk_slides.html` | Reveal.js HTML presentation (view in browser) |
| `pmlg_talk_slides.pptx` | PowerPoint version of the presentation |
| `extract_data.ipynb` | Data extraction and preprocessing notebook |
| `download.mp4` | MESA spectrum animation across bearing run-to-failure |
| `PoC_PdM_steel_mill.pdf` | Proof of Concept: Predictive Maintenance for Steel Mills |

## Outline

1. **The Problem** — Why spectral analysis matters in predictive maintenance
2. **MESA** — Maximum Entropy Spectral Analysis: theory, intuition, implementation
3. **Wavelet Transform** — Time-frequency analysis beyond Fourier
4. **Application** — Bearing vibration data (NASA IMS Dataset)
5. **Animation** — Watching degradation unfold in the frequency domain
6. **Real-World Use Case** — Predictive maintenance at a steel pipe factory
7. **Summary & References**

## Dependencies

- Python 3.10+
- `numpy`, `scipy`, `matplotlib`
- `memspectrum` (MESA implementation)
- `pycwt` (Continuous Wavelet Transform)
- `jupyter` (for notebooks)

## References

- Burg (1967). Maximum Entropy Spectral Analysis
- Torrence & Compo (1998). A Practical Guide to Wavelet Analysis
- [NASA IMS Bearing Dataset](https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/)
- [mill-crack-localprocessing](https://github.com/deep-science-ai/mill-crack-localprocessing) — Related PdM work for steel mill crack detection
