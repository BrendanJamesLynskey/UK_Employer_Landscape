# UK Employer Landscape — Multidisciplinary Engineer (April 2026)

A research-backed map of UK employers across **six job categories** matching a Staff-level multidisciplinary engineering profile (HW · Power · FPGA · DSP · LLM · Agents · Python). Built around a Leeds base with a stated preference for **Yorkshire / Greater Manchester / UK-remote** roles.

## ▶ [Open the live site](https://brendanjameslynskey.github.io/UK_Employer_Landscape/)

The landing page includes an **interactive UK heatmap** (city dots positioned by lat/lon, sized by employer count, recoloured per category), a TL;DR top-fits table, six category cards, a live-postings bar chart, and a Yorkshire/Greater-Manchester deep-dive.

> Setup: Enable GitHub Pages (Settings → Pages → Deploy from `main` branch, `/ (root)` directory). Otherwise, open `index.html` locally in any browser.

---

## Job categories

| # | Category | Top employers (excerpt) | Writeup |
|---|---|---|---|
| 01 | Agentic AI / LLM Engineering | Anthropic UK · Hugging Face · Mistral · Cohere · DeepMind · Wayve · Peak · AutoTrader · Sky Leeds · Faculty · Quantexa · Arm AI | [`categories/01_agentic_ai_llm.md`](categories/01_agentic_ai_llm.md) |
| 02 | AI Hardware / SoC / Accelerator Silicon | Arm · AMD · NVIDIA · Apple Cambridge · Graphcore · Axelera · Blaize · Imagination · Pragmatic · Codasip · Cadence Livingston | [`categories/02_ai_hardware_soc.md`](categories/02_ai_hardware_soc.md) |
| 03 | FPGA / RTL / Digital Design | Arm · AMD · MBDA Bolton · Thales Cheadle · Raytheon Manchester · BBC R&D Salford · Synamedia Saltaire · Leonardo · BAE · Riverlane · Picocom | [`categories/03_fpga_rtl.md`](categories/03_fpga_rtl.md) |
| 04 | High-Performance HW · PI · SI · Power | Arm · AMD · Graphcore · NVIDIA · Apple · Blaize · Pragmatic · Renishaw · Dyson · Keysight · MBDA Stevenage · Cambridge Consultants · TTP · PA | [`categories/04_pi_si_pcb_power.md`](categories/04_pi_si_pcb_power.md) |
| 05 | DSP · Audio · Broadcast · Comms PHY | Synamedia Saltaire · BBC R&D Salford · AMS Neve · Sky Leeds · Sagentia · Cambridge Consultants · TTP · Cirrus Logic · XMOS · AccelerComm · Smith+Nephew | [`categories/05_dsp_audio_broadcast.md`](categories/05_dsp_audio_broadcast.md) |
| 06 | Embedded Systems · Linux · Firmware | Codethink · Synamedia · Sky Leeds · Arm · AMD Versal · Collabora · Foundries.io · Canonical · 2net Sheffield · ByteSnap · CMR Surgical · JLR SDV · Renishaw York | [`categories/06_embedded_linux.md`](categories/06_embedded_linux.md) |

---

## Repo structure

```
UK_Employer_Landscape/
├── index.html                          ← landing page + interactive heatmap
├── README.md
├── .nojekyll
└── categories/
    ├── 01_agentic_ai_llm.md
    ├── 02_ai_hardware_soc.md
    ├── 03_fpga_rtl.md
    ├── 04_pi_si_pcb_power.md
    ├── 05_dsp_audio_broadcast.md
    └── 06_embedded_linux.md
```

Each category writeup contains: summary · top-employers table (15–30 rows with locations) · regional concentration table · Yorkshire & Greater Manchester focus · live job-posting estimates · notes & caveats · sources (URLs).

---

## Methodology

- **Source pipeline:** WebSearch + WebFetch against company careers pages, LinkedIn Jobs (UK filter), Indeed UK, CW Jobs, semiconductor-jobs.co.uk, UKESF directory, plus 2024–26 industry reporting (Tech Nation, Dealroom, Beauhurst, eeNews Europe, EE Times Europe).
- **Heatmap scoring:** subjective 0–10 ratings per (region × category), combining (a) employer count, (b) typical role volume in April 2026, (c) seniority/match. *Not* raw employer counts.
- **Posting volumes:** order-of-magnitude estimates; many roles cross-syndicate between job boards.
- **Clearance gating:** defence employers (BAE / Leonardo / MBDA / Thales / Roke / QinetiQ / Cobham Ultra / AWE) almost always require SC or DV clearance and UK nationality / 5–10 yr UK residency.
- **Excluded:** generic Big-4 consultancy "AI" roles without engineering depth; recruiter agencies; companies with no UK engineering presence.

---

## Snapshot of the strongest fits

(Distilled from all six writeups, weighted by Leeds location preference.)

- **S-tier:** Synamedia (Saltaire) · Codethink (Manchester) · Sky Leeds · Arm Manchester/Sheffield · Blaize (current)
- **A-tier:** BBC R&D Salford · Peak · AutoTrader · AMD ex-Xilinx (Cambridge/Edinburgh) · MBDA Bolton · Thales Cheadle Heath · Smith+Nephew (Hull/York) · Saga Robotics (York) · AMS Neve (Burnley)
- **B-tier (UK-remote):** Hugging Face · Anthropic · Mistral · Cohere · Faculty AI · Quantexa · Cambridge Consultants / TTP / Sagentia / Plextek / PA · Renishaw (York) · 2net (Sheffield) · ByteSnap (Birmingham) · Witekio · Foundries.io · Collabora · Canonical · Diodes Zetex (Oldham)

---

*Built April 2026.  All numbers are estimates as of late April 2026 and fluctuate weekly.  Cross-check live postings before acting on any single data point.*
