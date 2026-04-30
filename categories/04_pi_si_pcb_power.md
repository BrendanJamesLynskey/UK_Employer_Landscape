# Category 04 — High-Performance HW · PI · SI · Power Delivery · HDI PCB

> Multiphase DCDC · PI/SI · Cadence Sigrity / PowerSI / PowerDC · LTspice · SIMetrix/SIMPLIS · HDI · FC-BGA · DDR/PCIe/USB/MIPI/LPDDR4

## Summary

The UK has a real but geographically dispersed high-performance hardware ecosystem. Genuine PI/SI/multi-phase DCDC roles cluster in **Cambridge** (silicon SoC bring-up boards, AI accelerators, networking), **Bristol** (Graphcore, defence comms, Dyson satellite offices), **Edinburgh/Livingston** (AMD ex-Xilinx, Cirrus Logic, Leonardo), the **M4 corridor** (Wokingham/Reading/Newbury — Arm, Broadcom, Sondrel), and **defence belts** (Stevenage MBDA, Cheltenham/Malvern, Filton). Yorkshire and Greater Manchester are thinner but not empty: **Blaize Leeds**, **Diodes Zetex Oldham**, **Thales Cheadle Heath**, **Pragmatic Durham/Sedgefield** within reach, plus broadcast/audio in Saltaire and Halifax.

April 2026 hiring is moderate — strongest at **Arm, AMD, Graphcore, BAE/MBDA/Leonardo, Renishaw, Dyson, and Keysight** — with order-of-magnitude **~150–250 live UK postings** matching the SI/PI/multiphase-power/HDI keyword set across LinkedIn/Indeed/company sites. This profile (Sigrity/PowerSI, multiphase DCDC, FC-BGA, AI-accelerator boundary work) is unusually well matched to the **silicon-bring-up board** niche; strongest fits are Arm, AMD, Graphcore, Blaize, Pragmatic, Apple Cambridge, Renishaw and Dyson. Remote-only roles remain rare — most require 2–3 days on-site near a lab.

## Top UK Employers

| # | Employer | UK HW site(s) | What they build (HW relevance) |
|---|---|---|---|
| 1 | **Arm** | Cambridge, Manchester, Sheffield, Belfast | SoC bring-up boards, FPGA emulation rigs, reference platforms (Neoverse, Cortex) |
| 2 | **AMD** (incl. ex-Xilinx) | Cambridge, Edinburgh, Bristol | Versal/Alveo accelerator boards, FPGA cards, 112G SerDes test boards |
| 3 | **Graphcore** | Bristol (Cambridge HQ shrunk) | IPU accelerator boards, IPU-POD systems, HBM/CoWoS substrate |
| 4 | **NVIDIA** (incl. Mellanox) | Cambridge, Bristol, Bracknell | ConnectX/BlueField NIC boards, DGX-adjacent HW |
| 5 | **Apple** | Cambridge (small), London | Custom silicon bring-up; secretive |
| 6 | **Blaize** | **Leeds** | Edge-AI accelerator SoMs/boards |
| 7 | **Pragmatic Semiconductor** | Cambridge + **Sedgefield (Durham)** | Flexible IC test/eval boards, fab-side instrumentation |
| 8 | **Imagination Tech** | Kings Langley | GPU IP eval boards, FPGA prototypes |
| 9 | **Salience Labs / Lumai / Oriole** | Oxford / London | Photonic + silicon AI accelerators (early stage) |
| 10 | **Cisco / Arista** | Reading / Edinburgh (small) | Switch line cards (mostly designed in US) |
| 11 | **Nokia Bell Labs / Networks** | Cambridge, Bristol | Optical line cards, ReefShark |
| 12 | **Keysight Technologies** | **South Queensferry**, Winnersh | VNAs, BERTs, 110 GHz instruments — top-tier SI/PI work |
| 13 | **Spirent / Viavi** | Crawley / Stevenage | Test platforms |
| 14 | **BAE Systems** | Filton, Rochester, Cowes, Preston | Radar, EW, avionics PCBs, multiphase rails |
| 15 | **MBDA** | **Stevenage**, Bristol | Missile electronics, RF/digital boards |
| 16 | **Leonardo UK** | **Edinburgh**, Luton, Basildon, Lincoln | Radar, EW, defensive aids — heavy SI/PI |
| 17 | **Thales UK** | **Cheadle Heath (Stockport)**, Crawley, Reading, Glasgow | Sonar, comms, avionics boards |
| 18 | **Roke Manor** | Romsey | SIGINT, defence R&D HW |
| 19 | **QinetiQ** | Malvern, Farnborough | Defence electronics R&D |
| 20 | **Renishaw** | **Wotton-under-Edge**, Stonehouse, **Miskin** | Metrology, encoder ASIC boards, additive-mfg controllers |
| 21 | **Oxford Instruments / Andor** | Abingdon, Tubney, Belfast | Cryo, NMR, scientific instrument HW |
| 22 | **Dyson** | **Malmesbury**, Hullavington, Bristol | BLDC drive electronics, robotics, battery — heavy multiphase + EMC |
| 23 | **JLR** | Gaydon, Whitley | ADAS/ECU HW |
| 24 | **McLaren Applied / Williams AE** | Woking / Grove | Motorsport ECUs, KERS, telemetry |
| 25 | **Diodes Zetex** | **Oldham** | Discrete power, LED drivers, MOSFETs |
| 26 | **Vishay** | **Newport (Wales)**, Ebbw Vale | Discretes, wafer fab |
| 27 | **Power Integrations** | Cambridge | AC-DC controller eval boards |
| 28 | **Cambridge Consultants / TTP / Sagentia / Plextek** | Cambridge / Melbourn / Hertford | Project-based HW (medical, IoT, defence) |
| 29 | **PA Consulting** | Cambridge (Melbourn Tech Centre) | Cross-sector HW prototyping |
| 30 | **Focusrite / SSL / dCS / KEF / B&W** | High Wycombe / Begbroke / Cambridge / Maidstone / Worthing | Pro audio, DACs, mixed-signal HW |
| 31 | **CommScope** (ex-Pace via Arris) | **Salts Mill, Saltaire** | Set-top boxes, cable modems, Wi-Fi gateways &mdash; the actual current occupant at the old Pace plc site (Pace &rarr; Arris 2016 &rarr; CommScope 2019). Some board-level HW work on home-networking equipment. [careers.commscope.com](https://careers.commscope.com/location/saltaire-jobs/8610/2635167-6269131-2638652/4) |
| 31a | **EnSilica** | **Sheffield** + Cambridge Science Park (new 2026) + Bristol + Abingdon | Mixed-signal ASIC + mmWave/RF up to 175 GHz; UK Space Agency C-LEO funded. Sheffield is local to Leeds (~40 min). Direct fit for analogue/digital boundary, RF/mmWave HW work. [ensilica.com](https://www.ensilica.com/) |
| 31b | **Filtronic** | **Cambridge Science Park** + **Sedgefield (NE England)** | RF/mmWave components and subsystems for Space, Defence, Telecom; transceivers, PAs, filters K-band&ndash;W-band up to 175 GHz. SI/PI-heavy work. [filtronic.com](https://www.filtronic.com/) |
| 31c | **Curvalux** | **Sheffield (Electric Works, Sheaf St)** + planned £20M factory near **AMRC Rotherham** | Solar-efficient fixed-wireless-access broadband; software-defined multi-beam phased-array antenna systems, RF/PCB/power-efficiency-heavy. Sub-7 GHz Wi-Fi 6E products plus mmWave next-gen. £8M SCR Mayoral Combined Authority R&D grant. ~17 staff, scaling. Direct local fit (~40 min from Leeds) for analogue/RF/PCB/multiphase-power background. [curvalux.com](https://curvalux.com/) |
| 32 | **Calrec Audio** (Audiotonix) | **Hebden Bridge** (Nutclough Mill) | Live-broadcast audio mixing consoles &mdash; Argo, Type R, Brio, Summa, ImPulse1 ST2110 IP audio engine. Some PCB / DSP-board hardware design alongside heavy DSP work. [calrec.com/careers](https://calrec.com/careers/) |
| 33 | **Synamedia** (ex-Cisco Video / NDS) | **Staines-upon-Thames** + global | Often confused with Pace's Saltaire site, but Synamedia is a separate company &mdash; Cisco's Video Software Solutions sold to Permira (2018). HQ Staines, no Yorkshire HW office. [synamedia.com/careers](https://www.synamedia.com/careers/) |
| 34 | **Reach plc** (publisher) | One Canada Square (London) + regional titles incl. Telegraph &amp; Argus Bradford | Listed for completeness only &mdash; *not* an SI/PI engineering employer. Reach is the UK national/regional newspaper publisher (Daily Mirror, Express, Telegraph &amp; Argus). Earlier draft confused them with the Pace successor at Saltaire; the real occupant is CommScope. [reachplc.com](https://www.reachplc.com/) |

## Regional Concentration

| Region | Estimated HW/SI/PI HC | Key sites |
|---|---|---|
| **Cambridge / Cambs** | **3,000–4,500** | Arm, AMD, NVIDIA, Apple, Nokia, Graphcore (residual), Pragmatic, PI, Consultancies, Power Integrations |
| **Bristol / Filton** | 1,500–2,200 | Graphcore, BAE, Dyson, Nokia, AMD, Toshiba |
| **Edinburgh / Livingston / S. Queensferry** | 800–1,200 | AMD (Xilinx), Leonardo, Cirrus Logic, Keysight |
| **M4** (Reading/Wokingham/Newbury) | 700–1,000 | Arm, Broadcom, Cisco, Sondrel |
| **Stevenage / Hertfordshire** | 500–800 | MBDA, Airbus DS, Imagination |
| **Cheltenham / Malvern** | 300–500 | QinetiQ, GCHQ-adjacent, Endace |
| **Hampshire/Surrey** (Romsey/Crawley/Basingstoke) | 500–800 | Roke, Thales, Spirent |
| **Oxford / Abingdon / Malmesbury** | 600–900 | Oxford Instruments, Dyson, Salience, Lumai |
| **Greater Manchester** | **300–500** | Thales Cheadle, Diodes Zetex Oldham, Arm Manchester, BAE Radway Green |
| **Yorkshire** | **150–300** | Blaize Leeds, Arm Sheffield, **CommScope (ex-Pace) Salts Mill / Saltaire**, **Calrec Audio (Hebden Bridge)** |
| **North-East** | 200–400 | Pragmatic Sedgefield, Nissan Sunderland, Filtronic Sedgefield |
| **Wales** (Newport/Cardiff) | 200–400 | Vishay Newport, IQE, Spirent Cwmbran |
| **Derby / Midlands** | 300–600 | Rolls-Royce, JLR Gaydon, Aptiv Leamington |

## Live job postings (April 2026, order-of-magnitude)

| Search | LinkedIn UK | Indeed UK |
|---|---|---|
| "Signal Integrity" | 60–90 | 40–70 |
| "Power Integrity" | 20–40 | 10–25 |
| "Hardware Engineer" (PCB+SoC filter) | 400–700 | 600–1,000 |
| "Sigrity" | 15–30 | 10–20 |
| "Cadence Allegro" | 40–70 | 30–60 |
| "PCB Designer" | 200–350 | 250–400 |
| "Multiphase DCDC" / "Power Electronics Engineer" | 150–250 | 200–350 |

Net usable Staff-level matches per week: **~10–25 genuinely well-matched**.

## Yorkshire & Greater Manchester focus

Honest picture:

- **Leeds itself**: Blaize is the standout — small (~30 UK HW/SW), edge-AI accelerator boards, intermittent posting. Otherwise scientific/medical SMEs (Tracerco, Pivotal Labs) and university spin-outs. Real PI/SI vacancies usually 0–3.
- **Sheffield / Rotherham**: Arm has a Manchester/Sheffield CPU verification + small HW group. **EnSilica Sheffield** is the under-rated find — mixed-signal IC design centre; analogue/digital boundary, RF/mmWave; ~40 min commute. **Curvalux** at Electric Works (Sheaf Street, Sheffield) plus a planned £20M factory near the **AMRC** in Rotherham — software-defined phased-array antenna RF/PCB/power, scaling on £8M SCR Mayoral Combined Authority grant. AESSEAL, Gripple — limited board design. Sheffield Uni AMRC adjacent.
- **Bradford / Saltaire**: the Pace plc lineage at Salts Mill is now **CommScope** (Pace &rarr; Arris 2016 &rarr; CommScope 2019). Set-top / gateway / cable-modem engineering, mostly SW but with some board-level HW. *Synamedia* is a separate company at Staines &mdash; not at Saltaire, despite a common confusion. *Reach plc* (the newspaper publisher) is unrelated to the Pace site, listed here only because the original research confused the names.
- **Greater Manchester**: **Thales Cheadle Heath** (avionics/RF HW — real PI/SI work, 2–5 roles typical), **Diodes Zetex Oldham** (analogue/power IC + eval boards), **BAE Radway Green** (defence munitions electronics), **Arm Manchester** (CPU). Siemens Manchester (industrial drives), Bruntwood-cluster startups.
- **Realistic commuter radius from Leeds**: Manchester/Cheadle/Oldham (~1h), Sheffield (40 min), Sedgefield/Pragmatic (~1h45), Saltaire (~25 min). Hybrid 2–3 days on-site is workable.

## Notes & Caveats

- **Clearance gating**: BAE/MBDA/Leonardo/Roke/QinetiQ require SC or DV; processing 6–12 weeks.
- **Graphcore** has had multiple rounds of restructuring 2024–2025; Bristol HW team is leaner than headcount suggests on LinkedIn.
- **Apple Cambridge** rarely posts HW roles publicly — usually via referral/recruiter.
- **AMD Edinburgh** (ex-Xilinx) is the single best concentration of FPGA-board PI/SI work outside Cambridge.
- **Diodes Zetex Oldham** is geographically perfect but mostly IC-level, not board-level — fit needs validation.
- The Saltaire site (Salts Mill) is **CommScope**, not Synamedia and not Reach plc. CommScope is mostly software now — set HW-engineering expectations low.

## Sources

- <https://www.arm.com/careers>
- <https://careers.amd.com/>
- <https://www.graphcore.ai/careers>
- <https://www.nvidia.com/en-us/about-nvidia/careers/>
- <https://www.blaize.com/company/careers/>
- <https://www.pragmaticsemi.com/careers>
- <https://www.imaginationtech.com/careers/>
- <https://careers.keysight.com/>
- <https://www.baesystems.com/en/careers>
- <https://www.mbdacareers.co.uk/>
- <https://uk.leonardo.com/en/careers>
- <https://www.thalesgroup.com/en/countries/europe/united-kingdom/careers>
- <https://www.roke.co.uk/careers>
- <https://careers.qinetiq.com/>
- <https://www.renishaw.com/en/careers--1029>
- <https://careers.oxinst.com/>
- <https://careers.dyson.com/>
- <https://www.diodes.com/about/careers/>
- <https://www.power.com/company/careers>
- <https://www.cambridgeconsultants.com/careers>
- <https://www.ttp.com/careers>
- <https://www.paconsulting.com/careers>
- <https://www.synamedia.com/careers/>
- <https://www.linkedin.com/jobs/search/?keywords=signal%20integrity&location=United%20Kingdom>
- <https://www.ukesf.org/>

---

## Wave-5 additions — Yorkshire / NE power-electronics, hydrogen, defence-adjacent, scientific instruments (April 2026)

A follow-up sweep surfaced several high-fit power-electronics / multiphase-DCDC employers within ~1 h of Leeds, plus the UK's national-instruments tier.

### Yorkshire / North-East power & RF
- **ITM Power** — Sheffield (~40 min); kV-scale multiphase DCDC for hydrogen electrolysers; ~80 engineers across Power Electronics, Controls, Embedded SW; growing rapidly. **The strongest local multiphase-power fit identified to date.**
- **Faradion** (Reliance) — Sheffield; sodium-ion BMS + cell engineering; ~200-hire growth plan.
- **Rolls-Royce SMR** — Sheffield; reactor C&I, safety-grade power & control electronics.
- **Drax** — Selby (~30 min east of Leeds); generation control, BESS integration, C&I engineer roles.
- **CSA Catapult** — Sedgefield NETPark (~1 h 45); compound-semiconductor RF + power-electronics applications centre, GaN/SiC inverters and PA work.
- **Filtronic** — Sedgefield + Cambridge SP (already listed) — *now also* with confirmed PA/RF hardware-engineering openings April 2026.
- **AMETEK Land** — Dronfield (~30 mi); high-temp IR pyrometry, mixed-signal HW, integrated FPGA + analogue-front-end design.
- **Tracerco** — Billingham; industrial radiometric instrumentation, mixed-signal HW.
- **Forsberg Services** — Heysham; GNSS/INS hardware, RF + multiphase aux rails.
- **Northern Powergrid** — Yorkshire/NE; grid-scale protection electronics, less classical-board-design but power-system relevant.

### Scientific instruments tier (national-grade SI/PI/Power roles)
- **Diamond Light Source** — Harwell (Oxon); accelerator/beamline control electronics, multiphase rails, FPGA + analogue. Multiple hardware roles open April 2026.
- **STFC (Daresbury + RAL)** — Daresbury (~70 mi from Leeds, ~1 h 30 M62) and Harwell; instrumentation electronics.
- **NPL** — Teddington + Huddersfield outpost; atomic-clock / quantum-control electronics.
- **Gooch & Housego** — Ilminster + Torquay; photonics, acousto-optic & electro-optic modulators — RF + analogue HW.
- **Servomex** — Crowborough; gas-analysis instruments; live *V&V Engineer* role April 2026.
- **Pickering Interfaces** — Clacton-on-Sea; PXI / LXI switching HW, FPGA + analogue.
- **AimTTi** — Huntingdon; lab power supplies, function generators, source-meters — direct multiphase-DCDC fit.
- **Bruker UK** — Coventry / Banner Lane; analytical instruments.
- **Coherent UK** — Glasgow; lasers, photonics drives.
- **HBK / Brüel & Kjær** — Cambridge area; vibration/acoustic measurement HW.

### Motorsport HPP power electronics (see Cat 09 for full writeup)
- **McLaren Applied** (Woking), **Mercedes HPP** (Brixworth), **Red Bull Powertrains** (Milton Keynes), **WAE / Fortescue** (Grove), **YASA / Mercedes** (Yarnton), **Cosworth Electronics** (Cambridge), **Bentley** (Crewe — closest to Leeds, ~80 mi), **Drive System Design** (Leamington), **Mahle Powertrain** (Northampton).

ITM Power Sheffield, AMETEK Land Dronfield, and Hitachi Rail Newton Aycliffe are the three strongest *new* in-region power-electronics employers from this sweep. Diamond Light Source, AimTTi, and Pickering Interfaces are the strongest national instruments-tier finds.
