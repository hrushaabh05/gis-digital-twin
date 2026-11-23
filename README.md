# GIS Digital Twin — 230 kV Design & Fault Simulator

Interactive single-file web app simulating the complete Gas Insulated Substation (GIS)
design, engineering and installation sequence synthesized from seven published papers,
with Kahneman–Tversky bias injection, Popper falsification stress tests, and
fault-clearance procedures.

## Modules
1. **Overview** — paper-to-stage map and project progress
2. **Design Steps** — 11-step sequence (Justification → Lifecycle verification) with live models:
   - XLPE vs GIB interface comparison
   - VFTO calculator (trapped charge, T-junction factor, damping device) with waveform canvas
   - Grounding-model touch-voltage comparison (EMF vs net-current-only)
   - Staged energization ordering exercise (wrong order = simulated blackout)
3. **Fault Simulator** — 7 failure modes on an animated 230 kV single-line diagram,
   each labeled with its cognitive bias / falsified claim, with step-by-step clearance checklists
4. **Exposure Register** — live residual-risk re-scoring

## Sources
- D'Souza et al., IEEE Trans. Industry Applications (2018) — 230 kV AIS→GIS conversion
- Burow et al. — VFTO mitigation (ferrite falsified; nanocrystalline / RF resonator)
- Liu, Dawalibi, Majerowicz (CICED 2012) — EMF grounding study
- Nagarsheth & Singh, EPES (2014) — GIS vs AIS LCC / H-GIS
- Glaubitz et al., CIGRE Green Book Ch. 21 — GIS Earthing
- Ametani et al., EPSR (2018) — VFT / EMC disturbances
- Dodds & Spindle, IEEE PAS (1975) — GIS grounding fundamentals

## Run locally
Open `index.html` in any browser (fully self-contained, no dependencies).

## Live demo
Served via GitHub Pages at:
https://<your-username>.github.io/<repo-name>/
