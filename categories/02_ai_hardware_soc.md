# Category 02 — AI Hardware / SoC / Accelerator Silicon

> AI accelerator SoC · GPU/NPU silicon · IP cores · FPGA prototyping · system bring-up · FC-BGA · HBM/PCIe systems · inference silicon

## Summary

The UK is one of the densest concentrations of AI-silicon design talent outside the US, but it is heavily clustered: **Cambridge** alone hosts >10 chip-design employers; **Bristol** is the second pole (Graphcore, NVIDIA AI Tech Centre, XMOS, Axelera, Codasip, Fractile satellite); a long tail spreads to Edinburgh, Kings Langley, Reading/Bracknell, Manchester, Sheffield, Belfast and the defence axis (Stevenage/Filton/Chelmsford/Edinburgh). Following SoftBank's acquisition of Graphcore (June 2024), NVIDIA's 120k-GPU UK rollout, Apple's Cambridge expansion, Pragmatic's Durham fab, Axelera's UK build-out, and the new wave of UK-domiciled inference startups (**Fractile, Vaire Computing, Oriole Networks, Lumai, Salience Labs**), **2026 is a strong hiring year for HW-systems engineers** — particularly board / SI/PI / power-delivery and FPGA-prototyping skill-sets. Yorkshire/Greater Manchester remain thin for chip-level work; the strongest matches there are Arm Manchester/Sheffield, Siemens EDA emulation, and Blaize Leeds/Kings Langley.

### The AI Inference Accelerator wave (UK + UK-remote)

The post-2023 inference-accelerator boom has produced a fast-growing tier of dedicated companies (distinct from the GPU incumbents). UK-domiciled players are unusually well-funded for a country its size: **Fractile** (London + Bristol, ~£100M, 70 staff with 40-role hiring drive, ex-Intel CEO Pat Gelsinger backing, transformer-attention silicon), **Vaire Computing** (London, reversible-computing AI chips, Intel Ignite cohort), **Oriole Networks** (London, photonic networking for AI clusters, $35M raise, hiring FPGA / optical / silicon-photonics / HW engineers), **Lumai** (Oxford, free-space optical inference, $10M Series A, lens-based optical computer launched 2026), **Salience Labs** (Oxford, photonic switching / TFLN matrix multiply), **Axelera AI** (Bristol QTIC, 220+ staff, Metis AIPU + Metis M.2 Max, RISC-V dataflow + D-IMC), **Graphcore** (Bristol, SoftBank), **Blaize** (Leeds/KL), **Pragmatic** (Cambridge/Durham). Globally there is a much larger cohort of inference players (Tenstorrent, Cerebras, Groq, SambaNova, d-Matrix, Etched, MatX, FuriosaAI, Rebellions, Hailo, Mythic, Lightmatter, Recogni, Esperanto, Brainchip, Kneron, Syntiant, Innatera, GreenWaves) — most are US/Asia-headquartered but a significant fraction hire UK-remote engineers; see [Category 07](07_remote_international.md) for that view.

## Top UK Employers

| # | Company | Primary UK silicon/HW sites | What they do |
|---|---|---|---|
| 1 | **Arm** | Cambridge HQ, Manchester, Sheffield, Belfast | CPU/GPU/NPU IP; new in-house "AGI CPU" silicon (Mar 2026) — first own product silicon, lead customer Meta |
| 2 | **Graphcore (SoftBank)** | Bristol HQ, Cambridge, London | IPU AI training accelerators; SoftBank's European AI-compute R&D hub |
| 3 | **NVIDIA** | Cambridge, Bristol (AI Tech Centre), London | DGX/Grace-Hopper deployments, Isambard-AI; 120k Blackwell-Ultra UK rollout by EOY 2026 |
| 4 | **AMD (incl. ex-Xilinx)** | Cambridge, Reading, Edinburgh | Versal/Alveo FPGA-AI; Instinct GPU systems; Pensando NIC |
| 5 | **Apple** | Cambridge (new 7-storey site), London Battersea | Custom GPU, NPU, AI/ML silicon; Cambridge is silicon hub |
| 6 | **Imagination Technologies** | Kings Langley HQ, Cambridge, Bristol, Manchester | GPU IP, AI accelerator IP, Catapult RISC-V |
| 7 | **Qualcomm** | Cambridge, Farnborough | SoC architecture; audio SoCs; automotive AI/ML; GPU formal verif |
| 8 | **Synopsys** | Edinburgh (George St), Reading, Cambridge, Sheffield | EDA + silicon IP; SoC engineering services |
| 9 | **Cadence** | Livingston (Scotland), Bracknell, Manchester | EDA, Sigrity/PowerSI/PowerDC tools, Protium FPGA prototyping |
| 10 | **Siemens EDA (Mentor)** | Newbury, Manchester | Veloce emulation HW, HyperLynx SI/PI, Calibre |
| 11 | **Intel** | Swindon (Customer Engineering), London | Customer platform HW/SW, Habana Gaudi support |
| 12 | **Blaize** *(current)* | Kings Langley, Leeds | Edge AI SoC (GSP); SoC + board design |
| 13 | **Axelera AI** | Bristol (QTIC, Univ. of Bristol Temple Quarter Enterprise Campus), plus EU | Edge AI inference accelerator (Metis AIPU, Metis M.2 Max); RISC-V + dataflow + digital in-memory computing (D-IMC). 220+ staff incl. 49+ PhDs. April 2026 open Bristol roles: Verification Engineer, Processor Verification Engineer, Backend Compiler Engineer, Senior/Staff Applications Engineer (Embedded AI), Director of Engineering (AI Integrated Systems), Tech Sales DR EMEA. [axelera.ai/careers](https://axelera.ai/careers) |
| 13a | **Fractile** | **London (HQ) + Bristol (new)** | UK-domiciled inference startup (memory-fused compute, transformer attention, claims 100x faster + 10x cheaper + 20x perf/W vs H100). £100M planned UK investment over 3 years. Bristol site for chip assembly + SW testing. Hiring **40 of 110** roles in 2026 across HW eng / silicon design / SW. Backed by Oxford Science Enterprises, Kindred Capital, NATO Innovation Fund, Pat Gelsinger. [fractile.ai](https://www.fractile.ai/) |
| 13b | **Vaire Computing** | **London** | Reversible-computing AI chip moonshot — claims ~50% energy reduction. Intel Ignite cohort + UK ChipStart incubator. ~$9.5M raised. Small team, very early but high-impact if it works. [vaire.co](https://vaire.co/) |
| 13c | **Oriole Networks** | **London** | Photonic networking for AI/ML clusters — light-only data movement, drastically lower energy. $35M raise. **Actively recruiting**: FPGA Network Engineers, Optical Engineers, Silicon Photonics Engineers, Systems & Network Architects, Hardware Engineers, Lab Technicians. Direct match for HW + FPGA + DSP. [careers.oriolenetworks.com](https://careers.oriolenetworks.com/) |
| 14 | **XMOS** | Bristol | Generative SoCs (xcore); voice/audio + edge AI |
| 15 | **Codasip** | Bristol, Cambridge | RISC-V cores incl. AI-extensions |
| 16 | **Pragmatic Semiconductor** | Cambridge HQ, Durham (300mm flexible IC fab) | Flexible TFT ICs; FlexIC Gen3 mixed-signal for AI-IoT |
| 17 | **Lumai** | **Oxford** | 3D free-space optical AI inference (Iris Nova / Iris server, lens-based, launched 2026). Claims up to **50&times; AI performance, 90% less power** vs. silicon. Test-cluster rollout EOY 2026. [lumai.ai](https://lumai.ai/) |
| 18 | **Salience Labs** | **Oxford** | Photonic PCIe / switching accelerator (TFLN matrix multiply); spun out of Oxford + Münster. Hiring openly. [careers.saliencelabs.ai](https://careers.saliencelabs.ai/) |
| 19 | **Optalysys** | Leeds-area / Cambridge | Optical / FHE accelerator |
| 20 | **Achronix** | Small UK FAE/sales | eFPGA + Speedster7t AI FPGA |
| 21 | **Sondrel / Aion Silicon** | Reading/Theale | ASIC turnkey services (incl. AI ASICs) |
| 22 | **Renesas** | Bourne End | Automotive / IoT MCU + AI-MCU |
| 23 | **MediaTek** | Cambridge (Kingfisher Ho), Kent | Modem, Wi-Fi, AI SoC blocks |
| 24 | **BAE / MBDA / Leonardo** | Filton, Stevenage, Chelmsford, Edinburgh, Rochester, Luton | FPGA/ASIC for radar, EW, missile seekers, Tempest avionics |
| 25 | **Meta UK** | London (Kings Cross), Cambridge | MTIA chip programme (next-gen 2026/27); Arm AGI CPU lead customer |

## Regional Concentration

| City / Area | Approx. AI-silicon employer count | Notable names | Live HW-systems / SI-PI / FPGA-proto postings |
|---|---|---|---|
| **Cambridge** | 12–15 | Arm HQ, AMD, Apple, NVIDIA, Qualcomm, Imagination, MediaTek, Pragmatic, Graphcore (sat.), Codasip, Synopsys, Renesas | 200+ HW/SoC; ~50 systems/board/PI |
| **Bristol** | 7–9 | Graphcore HQ, NVIDIA AI Tech Centre, Axelera UK, XMOS, Imagination, Codasip | ~80–120; ~25 HW-systems |
| **London** | 4–6 | Apple Battersea, NVIDIA, Meta, Graphcore (sat.), Arm sat., Flux Computing | ~40–60 |
| **Edinburgh / Livingston** | 3–4 | Cadence Livingston, Synopsys Edinburgh, AMD Pensando, Codasip remote | ~30 |
| **Reading / Bracknell / Newbury** | 4–5 | AMD Reading, Cadence Bracknell, Siemens EDA Newbury, Sondrel/Aion | ~25 |
| **Kings Langley / Hertfordshire** | 2–3 | Imagination HQ, Blaize KL | ~15 |
| **Manchester** | 3–4 | Arm Manchester, Siemens EDA, Imagination sat., AMD apprenticeships | ~15–20 |
| **Sheffield** | 1–2 | Arm Sheffield (CPU verif & systems), Synopsys (small) | ~5–10 |
| **Leeds / Yorkshire** | 1–2 | Blaize Leeds, Optalysys (peripherally) | ~5 |
| **Belfast** | 1 | Arm Belfast | <5 |
| **Oxford** | 2–3 | Lumai, Salience Labs, plus academic spinouts | ~10 |
| **Durham / NE** | 1 | Pragmatic Park 300mm fab | ~10 process/test |
| **Defence axis** (Stevenage / Filton / Chelmsford / Rochester / Luton / Edinburgh) | 4–5 corporates | BAE, MBDA, Leonardo, Thales UK, QinetiQ | ~50+ FPGA/ASIC/HDI (clearance-gated) |
| **Swindon** | 1 | Intel Customer Engineering | ~20 |

## Yorkshire & Greater Manchester focus

Yorkshire is thin for chip-level AI work. Headline employers:

- **Blaize Leeds** — current employer; the only true AI-SoC design site in Yorkshire.
- **Arm Sheffield** — small but growing CPU-verification/systems site.
- **Optalysys** (Leeds-area roots) — optical-FHE accelerator; small team.

Greater Manchester is moderately better:

- **Arm Manchester** — Senior Verification Engineer (ISP) and other CPU/Central Engineering roles open; Embedded Electronic Systems Design Engineer apprenticeship lead site.
- **Siemens EDA Manchester** — Calibre/HyperLynx engineering; complements Newbury's Veloce HW team.
- **Imagination satellite** — small Manchester presence.
- **AMD apprentice/grad pipeline** runs through Manchester.

For a Staff-level board / SI-PI / FPGA-proto profile, neither region offers a wide field — the realistic Yorkshire/GM strategy is (a) stay at Blaize Leeds, (b) Arm Manchester/Sheffield CPU-systems, or (c) UK-remote at Bristol/Cambridge employers (Graphcore, Axelera, AMD, NVIDIA, Cadence Livingston are all hybrid-friendly).

## Global AI inference players (mostly UK-remote)

Beyond the UK-domiciled list, the broader AI inference / accelerator landscape contains a long tail of well-funded specialist silicon companies. Most have no UK office, but many hire UK-remote senior IC engineers; see **[Category 07: Pure Remote / International](07_remote_international.md)** for the route-in detail.

| Company | HQ | What they build | UK presence | UK-remote? |
|---|---|---|---|---|
| **Tenstorrent** | Toronto | RISC-V + Tensix AI accelerators (Wormhole, Blackhole, Quasar); open-source SW stack | None | Yes — actively hires UK-remote senior IC |
| **Cerebras** | Sunnyvale | Wafer-scale (CS-2/CS-3) inference + training; recent $1B raise at $23B valuation, refiling for IPO | None confirmed | Yes — UK-remote senior IC |
| **Groq** | Mountain View | LPU deterministic inference; recently subject of NVIDIA acquisition activity | None | Yes — UK-remote senior IC |
| **SambaNova** | Palo Alto | RDU (reconfigurable dataflow unit); SambaNova Suite Cloud | Minimal | Selective UK-remote |
| **d-Matrix** | Santa Clara | Corsair inference accelerator (digital in-memory) | None | Selective UK-remote |
| **Etched** | San Francisco | Sohu — transformer-only ASIC; bet-the-architecture on attention | None | Selective UK-remote |
| **MatX** | San Francisco | Inference silicon for frontier transformers | None | Selective UK-remote |
| **Lightmatter** | Boston / Mountain View | Photonic interconnect (Passage) + photonic compute | None | Selective UK-remote |
| **Recogni** | Mountain View | Auto + edge inference accelerator | None | Selective |
| **Esperanto** | Mountain View | RISC-V many-core AI inference (ET-SoC-1) | None | Selective |
| **NextSilicon** | Israel / NYC | Reconfigurable HPC + AI compute | None | Selective |
| **FuriosaAI** | Seoul | RNGD NPU (mass production from Jan 2026) | None | Selective |
| **Rebellions** | Seoul | NPU for LLM serving (Atom, Rebel) | None | Selective |
| **Hailo** | Tel Aviv | Hailo-8 / Hailo-10H edge AI accelerator (Raspberry Pi AI Kit) | London sales/FAE | Yes — engineering UK-remote |
| **Mythic** | Austin / Texas | Analog in-memory inference (post-restructure) | None | Selective |
| **Brainchip** | Sydney / Laguna Hills | Akida neuromorphic NPU | None | Selective |
| **Innatera** | Delft (NL) | Neuromorphic spiking sensor processor | EU-remote | EU-friendly |
| **GreenWaves Tech** | Grenoble | GAP9 RISC-V + NE16 NPU for ULP edge AI | EU-remote | EU-friendly |
| **Kneron** | San Diego / Taipei | Kneo edge NPU SoCs | None | Selective |
| **Syntiant** | Irvine | Always-on voice + sensor NPU | None | Selective |
| **Quadric** | Burlingame | Chimera GPNPU IP | None | Selective |
| **Expedera** | Santa Clara | Origin Evolution edge NPU IP (2026 Edge AI Vision award) | None | Selective UK-remote |

> **Untether AI** (Toronto) wound down operations in 2024 after financial difficulty — listed for historical completeness only.

For Brendan: the unusual breadth of HW + FPGA + Power + DSP + agentic-AI background travels well into both **UK-resident inference startups** (Fractile / Vaire / Oriole / Lumai / Salience / Axelera / Blaize / Graphcore — strong direct route) and **US-remote senior IC roles** at HW-systems-level inference cos like Tenstorrent / Cerebras / Groq, where senior power-delivery / SI-PI / FPGA-prototyping / system-bring-up hires routinely come in via remote. The transformer-attention / memory-fused / photonic players are particularly receptive to candidates who can credibly bridge analog physics → digital accelerator → ML systems.

## Notes & Caveats

- Headcounts and posting counts are LinkedIn/Glassdoor scrapes from late April 2026 and fluctuate weekly.
- Tenstorrent has no confirmed UK design office in 2026; only ad-hoc presence via remote contractors.
- SambaNova / Untether AI have no significant UK silicon HW office.
- Five (autonomy SoC) was acquired by Bosch (Stuttgart-led) — UK silicon presence diminished.
- Audio Analytic was acquired by Meta (2022) — Cambridge audio-AI team folded into Meta UK.
- Many "AI hardware" UK roles are actually data-centre fitting / GPU-systems integration (NVIDIA, Nscale, CoreWeave) rather than chip design — relevant for PI/PDN/thermal skills but distinct from accelerator SoC.

## Sources

- <https://www.fractile.ai/>
- <https://www.computerweekly.com/news/366638933/Fractile-expansion-demonstrates-UK-growth-opportunity>
- <https://techfundingnews.com/fractile-100m-uk-ai-chip-investment-bristol/>
- <https://tech.eu/2025/05/06/we-are-sprinting-towards-implementation-of-our-first-chip-says-uk-startup-in-ai-inference-race/>
- <https://vaire.co/>
- <https://fortune.com/2025/05/20/uk-startup-vaire-reversible-computing-chip-gpu-alternative-energy-savings-ai/>
- <https://www.datacenterdynamics.com/en/analysis/vaire-computing-reversible-computing-semiconductor-chip/>
- <https://oriolenetworks.com/>
- <https://careers.oriolenetworks.com/>
- <https://lumai.ai/>
- <https://careers.saliencelabs.ai/>
- <https://axelera.ai/careers>
- <https://jobs.ashbyhq.com/axelera>
- <https://www.bristol.ac.uk/temple-quarter-enterprise-campus/research-and-innovation/qtic/news/2023/axelera-joins-qtic.html>
- <https://tenstorrent.com/careers>
- <https://www.cerebras.ai/>
- <https://groq.com/careers/>
- <https://hailo.ai/>
- <https://furiosa.ai/>
- <https://rebellions.ai/>
- <https://www.graphcore.ai/posts/graphcore-begins-hiring-drive-with-75-new-jobs>
- <https://www.graphcore.ai/posts/graphcore-joins-softbank-group-to-build-next-generation-of-ai-compute>
- <https://careers.arm.com/search-jobs>
- <https://newsroom.arm.com/news/arm-agi-cpu-launch>
- <https://jobs.apple.com/en-gb/search?location=cambridge-CMA>
- <https://nvidianews.nvidia.com/news/nvidia-and-united-kingdom-build-nations-ai-infrastructure-and-ecosystem-to-fuel-innovation-economic-growth-and-jobs>
- <https://www.imaginationtech.com/careers/>
- <https://careers.qualcomm.com/careers/*/cambridge_united_kingdom>
- <https://careers.synopsys.com/location/united-kingdom-jobs/>
- <https://www.eenewseurope.com/en/codasip-looks-to-hire-100-risc-v-engineers-in-bristol-cambridge/>
- <https://www.theregister.com/2024/03/27/pragmatic_opens_300mm_fab/>
- <https://www.cambridgenetwork.co.uk/news/pragmatic-semiconductor-launches-next-generation-platform-mixed-signal-flexible-asic-design>
- <https://axelera.ai/careers>
- <https://www.blaize.com/careers/>
- <https://jobs.intel.com/en/employment/swindon-england-united-kingdom>
- <https://www.sondrel.com/careers/>
- <https://uk.leonardo.com/en/fcas/team-tempest>
- <https://newsroom.mbda-systems.com/mbda-stepping-up-to-a-new-strategic-dimension-21416/?lang=en>
- <https://semiconductorjobs.co.uk/career-advice/new-semiconductor-employers-to-watch-in-2026-uk-and-international-companies-transforming-chip-careers>
- <https://uk.linkedin.com/jobs/semiconductor-jobs>
- <https://kitalent.com/article-bristol-deep-tech-semiconductor-hiring>
