# Coherence Notebook

An interactive notebook for comparing simplified coherence scenarios across superconducting, trapped-ion, neutral-atom, photonic and topological device profiles.

## What it demonstrates

- Reproducible scenario paths controlled by an explicit random seed.
- Device comparison using Q-volume-style indices, drift and dispersion.
- Specialist views for T1/T2 decay, Bloch-vector evolution and circuit-depth budgets.
- Accessible controls and text alternatives for generated figures.

Every device profile and time series is synthetic. The notebook is an interface and modelling exercise, not a hardware benchmark or statement about vendor performance.

## Run locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. The published version is available through GitHub Pages.

## Engineering note

The deterministic scenario kernel is shared with four sibling studies. This repository contains the quantum-device adapter and the coherence-specific explanatory views.
