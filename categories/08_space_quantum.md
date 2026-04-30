# Category 08 — UK Space / NewSpace & Quantum Computing Hardware

> Smallsat payload electronics · AOCS · EPS power · radiation-hard FPGA · S/X/Ka/optical comms · ion-trap & superconducting & photonic qubits · cryogenic control · pulse-shaping FPGA

## Summary

Two emerging UK HW-heavy clusters that the first seven categories under-cover. Both lean directly on the same skill stack as defence avionics — **VHDL/Verilog on Xilinx UltraScale+/Versal, multiphase DC-DC, RF chains, embedded Linux, mixed-signal PCB** — but with smaller teams, faster cadence, and (especially in quantum) genuine green-field control-electronics problems.

**Geography:** UK space is a **Harwell + Stevenage + Glasgow + Guildford** quadrilateral with smaller satellites at Leicester / Cardiff / Cornwall / Westcott. UK quantum HW is a **Cambridge + Oxford-Harwell + London + Glasgow** square, with **Sheffield (Aegiq)** and **Daresbury (PsiQuantum)** as the two genuinely-northern outposts — Aegiq is ~40 min from Leeds and a serious target.

---

## A. UK Space / NewSpace HW Employers

### Top Employers

| # | Employer | UK HW Locations | What They Build | Apr 2026 hiring | Fit-note |
|---|----------|-----------------|-----------------|-----------------|----------|
| 1 | **SSTL — Surrey Satellite Technology** (Airbus) | **Guildford** (Tycho House) | Smallsat platforms (300 kg class), Galileo nav payloads, imager electronics, OBC, EPS, S/X-band RF | Live: imager electronics, AIT, RF, DH&P engineers — strongly hiring on Galileo 2nd-gen and FORUM | Strong. SSTL Imager Electronics team is FPGA-heavy (Xilinx Kintex/Virtex, rad-tolerant). UK national / clearable required. |
| 2 | **Airbus Defence & Space UK** | **Stevenage** (HQ), Portsmouth (payloads) | Large GEO comms, Mars rovers (Sample Fetch), Skynet, OneWeb-Gen2 (340-bird Airbus contract Jan 2026) | Heavy hiring on OneWeb-Gen2 production line + Skynet 6 | Stevenage has by far the deepest UK satellite hardware bench. Steady FPGA + power + RF reqs. Clearance gated. |
| 3 | **Thales Alenia Space UK** | Bristol, Harwell | Telecom payload RF, Earth-observation, SAR | Modest — RF & systems engineers | Already covered in defence (Cat 03) but TAS-UK is a separate space-side BU. |
| 4 | **Eutelsat OneWeb** | London (HQ, White City) + Hounslow Network Ops | LEO constellation operator; payload spec but builds at Airbus Toulouse/Stevenage | Light on HW; mostly RF systems, ground-segment, FPGA on user terminals | Less HW depth than building a satellite — most HW lives at Airbus. |
| 5 | **Astroscale UK** | **Harwell** ("Zeus" 20,000 sqft facility) | ELSA-d, ELSA-M, COSMIC active debris removal; rendezvous & docking, robotic capture | ~250 UK staff, planning to double; hiring AOCS, GNC, power, AIT | Excellent HW culture, growing Harwell hub, GNC-heavy embedded. Less FPGA than SSTL. |
| 6 | **Open Cosmos** | **Harwell** | "nanoSat-as-a-service" 6U–16U smallsats, OpenConstellation | Live FPGA Engineer role (Feb 2026); systems and AIT | Direct FPGA fit — Xilinx Zynq on OBC/payload. Small team, fast cadence. |
| 7 | **In-Space Missions** (BAE) | **Alton, Hampshire** | Faraday host-payload smallsats; 100 kg class; HMG missions | Multiple AIT, Electronic, Structural roles | BAE-owned but lighter clearance burden than Rochester. Cleanrooms + HW-rich. |
| 8 | **Spire Global** | **Glasgow** (Skypark) | 6U smallsat constellation (RO/AIS/ADS-B); designs, builds, tests, operates in-house | Satellite Ops Engineer; periodic HW eng | Small constellation factory — ideal for embedded/FPGA generalists. UK-remote-friendly for some roles. |
| 9 | **AAC Clyde Space** | **Glasgow** (Skypark) | Smallsat sub-systems: EPS (Starbuck), OBC (Sirius), comms (Pulsar S-band), 1U–16U platforms | Live: experienced electronics engineer, test engineer | **Direct match** — multiphase DC-DC EPS designs, S-band radios, OBC FPGA. Glasgow-only. |
| 10 | **Skyrora** | **Edinburgh** (HQ) + Cumbernauld build site | Skyrora XL 3-stage launcher; HTP/kerosene; bought select Orbex assets Feb 2026 after Orbex collapse | Avionics, GNC, propulsion test | Still pre-orbital, funding-fragile but only viable UK launcher post-Orbex. |
| 11 | **Orbex** | (Forres, Scotland — collapsed Feb 2026) | Prime-vehicle bio-propane micro-launcher | **Defunct** — administration Feb 2026; assets being absorbed by Skyrora | Cross off the list. |
| 12 | **SpaceForge** | **Cardiff** | ForgeStar in-space manufacturing returnable platform; semiconductor crystal growth in microgravity | Hiring across mech, electronics, thermal | Niche but interesting — re-entry HW + payload electronics. Wales ecosystem. |
| 13 | **Oxford Space Systems** | **Harwell** (Zephyr Building) | Deployable structures: AstroTube booms, Wrapped Rib reflector, antenna deployables | Modest HW + structures hiring | Mostly mech, but some deployment-control electronics. |
| 14 | **Magna Parva** | **Leicester** | Composite manufacturing in-space ("Consolidator"), ESA / MoD payloads | Small team (~20–30); MoD-funded growth | HW-light vs. its competitors — mostly mech / process. |
| 15 | **KISPE Space Systems** | **Farnborough** | Smallsat systems engineering, OBC, mission ops; spinout from SSTL alumni | Steady consultancy-style hiring | Smaller, project-services oriented. |
| 16 | **Goonhilly Earth Station** | **Cornwall** (Helston) | Deep-space comms ground antenna, lunar relay, X/Ka uplink, ESA Estrack-adjacent | RF / antenna control / FPGA modem engineers | Cornwall location (remote-living). Strong RF/DSP ground-segment HW. |
| 17 | **STFC RAL Space** | **Harwell** + Chilbolton | National lab — instrument design (ESA/JUICE/Solar Orbiter), space test facilities, ~335 staff | Civil-service style; recurring instrument electronics roles | Research-grade mixed-signal & FPGA. UK national pay scale. |
| 18 | **Nammo UK** (ex-Moog ISP) | **Westcott**, Bucks | Bipropellant/HTP rocket engines, ESA Argonaut RELIANCE engine (6 kN), satellite thrusters | Test & control-electronics engineers | Mostly propulsion mech, but valve drivers / test rigs need HW + embedded. |
| 19 | **Lockheed Martin Space UK** | Ampthill, Harwell | UK Pathfinder launch contract, smallsat support; smaller UK HW footprint | Light UK HW hiring | Lower visibility than US parent. |
| 20 | **D-Orbit UK** | (Harwell-listed; minimal UK eng) | Italian parent: orbital transport / ION carrier | UK presence is sales-heavy, not HW-heavy | Skip. |
| 21 | **Reaction Engines** | (Culham — **defunct Oct 2024**) | SABRE pre-cooler, hypersonic | **In administration**; international entity dissolved Jun 2025 | Cross off. |
| 22 | **ISISpace UK / Rocket Lab UK** | Negligible UK HW eng | — | — | Skip. |
| 23 | **Filtronic** | Sedgefield + Cambridge SP | Already in Cat 02/04 — but space programmes (Lynx-class SDA, BlueBird E-band) are real | Live hiring | **Cross-cutting fit.** Sedgefield is < 2 hr from Leeds. |

### Regional concentration

| Region | Est. HW headcount | Apr 2026 live HW reqs | Anchors |
|--------|-------------------|------------------------|---------|
| **Stevenage / Herts** | 1,800–2,200 | ~80 | Airbus DS UK, MBDA Stevenage |
| **Harwell, Oxfordshire** | 1,400+ (cluster total, ~100 orgs) | ~60 | Astroscale, Open Cosmos, Oxford Space Systems, RAL Space, ESA-ECSAT, Thales Alenia |
| **Guildford / Surrey** | 700 | ~30 | SSTL, Surrey Space Centre, KISPE (Farnborough) |
| **Glasgow** | 600+ | ~35 | Spire, AAC Clyde Space, Alba Orbital, Bird Aerospace |
| **Edinburgh / Scotland** | ~250 | ~15 | Skyrora, Leonardo (overlap), spaceport ground stations |
| **Westcott / Bucks** | 300 | ~12 | Nammo UK propulsion cluster |
| **Leicester / E. Midlands** | 200 | ~8 | Magna Parva, Univ. of Leicester Space Park |
| **Cardiff / Wales** | 80 | ~5 | SpaceForge |
| **Cornwall** | 100 | ~6 | Goonhilly, Spaceport Cornwall (Newquay) |
| **Yorkshire / N. England** | <30 (no anchor) | ~0–2 | Filtronic Sedgefield (RF) is the only meaningful HW-space adjacency near Leeds |

**Verdict for Leeds base:** UK space is geographically southern. Realistic options are **(i) UK-remote at SSTL/Airbus/Open Cosmos for systems-level work**, **(ii) relocation to Harwell or Glasgow**, or **(iii) Filtronic Sedgefield** for space-RF as a commutable proxy.

---

## B. UK Quantum Computing HW Employers

### Top Employers

| # | Employer | UK Locations | Modality / What They Build | Apr 2026 hiring | Fit-note for FPGA + RF + power + embedded |
|---|----------|--------------|----------------------------|------------------|--------------------------------------------|
| 1 | **Riverlane** | **Cambridge** | QEC decoder ASIC/FPGA stack — *Deltaflow* (Xilinx FPGA-heavy); Deltaflow 3 streaming-logic late 2026 | Live FPGA Design Engineer + SoC team roles | **Best-in-class match.** Real-time QEC decoder is *the* UK FPGA quantum job. Sub-µs decode latency. |
| 2 | **Quantinuum** | **Cambridge** (Science Park) + Broomfield CO | Trapped-ion (H-series); merger of CQ + Honeywell Quantum | Active Lever board; FPGA + control electronics + decoder roles | Very strong — RF AWG, microwave, FPGA pulse-shaping, mixed-signal. |
| 3 | **Oxford Quantum Circuits (OQC)** | **Reading** (Shinfield) | Superconducting (dual-rail "Dimon"); Genesis 2026 KiloQuOp, 16 logical qubits | ~21 active roles, ~13 engineers; cryo + embedded + QEC | Deep cryo control electronics, FPGA, embedded firmware — strong fit. |
| 4 | **Quantum Motion** | **London** (UCL spinout) + Cambridge PhD scheme | Silicon spin qubits in CMOS — cryo-CMOS at mK | Hiring Senior Quantum Engineers (microwave qubit control & readout electronics) | **Excellent fit** — ultra-low-power microwave control = analog/mixed-signal + FPGA + cryo board design. |
| 5 | **ORCA Computing** | **London** (HQ) + Toronto | Photonic quantum (room-temp, photon-number-resolving); PT-3 in 2026 | Steadily hiring; FPGA + fast DAC/ADC + ps-timing engineers | Direct match — high-speed optical control = fast-FPGA + precision timing + power-clean PCB. |
| 6 | **Universal Quantum** | **Brighton / Haywards Heath** | Trapped-ion using silicon microchip traps + global magnetic field | Hiring Hardware Team Lead + Electronics Engineers | Strong — building a control-electronics team from scratch; FPGA + power + RF. |
| 7 | **Oxford Ionics** | **Oxford** (Begbroke) | Trapped-ion using electronic (not laser) qubit control; CMOS-integrated traps | Live: Embedded SW Eng, EM Sim Eng, Integrated Optics, Quantum Scientist | Engineering-led; embedded firmware + EM sim are direct fits. |
| 8 | **Infleqtion (UK)** (ex-ColdQuanta) | **Oxford / Kidlington / NQCC Harwell** | Neutral-atom (rubidium); operates UK system at NQCC | Quantum Lab Eng, Software Dev, Quantum SW Eng | Lab integration + mixed-signal. UK is more lab-ops than core HW R&D. |
| 9 | **PsiQuantum** | **Daresbury** (STFC) | Photonic quantum; UK arm focuses on **high-power cryogenic systems** (100 W @ 4 K target) | UK team is small but specialised: cryo, vacuum, power, controls | Cryogenic + multi-kW power + control electronics. Genuinely north-of-Birmingham. |
| 10 | **Aegiq** | **Sheffield** (Sheffield Tech Park, mins from station) | **Photonic quantum** — InAs QD single-photon sources, Si3N4 PIC, SNSPD detectors, 4–6 qubits | Periodic photonics, software, FPGA roles via Workable | **Most-local serious quantum HW employer to Leeds (~40 min)**. Photonic stack means high-speed FPGA, optical switching control, low-noise PSU — strong match. Watch this carefully. |
| 11 | **M Squared Lasers** | **Glasgow** (W. of Scotland Sci. Park) + London + Surrey | Ultra-narrow-linewidth & ultrashort lasers for cold-atom / quantum sensors | Steady careers@m2lasers.com; expanding | More photonics/laser than digital, but laser-control electronics + FPGA timing roles exist. |
| 12 | **Phasecraft** | London + Bristol | Quantum **algorithms / software** (UCL+Bristol spinout) | Software-heavy hiring | **Not HW** — ignore for FPGA/RF profile. Listed for completeness. |
| 13 | **Quantum Dice** | **Oxford** | QRNG (quantum random-number generators) for crypto | Crypto cert + summer interns; small team | Mixed-signal + photonic + embedded; smaller-scale than the qubit players. |
| 14 | **Quantum Base** | **Lancaster** | UQID anti-counterfeit / security (atomic-scale), not gate-model QC | Small | Adjacent only — not an FPGA employer. |
| 15 | **NQCC — National Quantum Computing Centre** | **Harwell** | National facility hosting multiple testbeds (incl. Infleqtion, OQC, Rigetti UK collab) | Civil-service style; controls / integration / RF engineers | Excellent for a generalist who wants exposure to all modalities. UKRI pay scale. |

*(Quantum Machines, SciTec — limited UK HW presence found; skip.)*

### Regional concentration

| Region | Est. HW headcount | Apr 2026 live HW reqs | Anchors |
|--------|-------------------|------------------------|---------|
| **Cambridge** | 350–450 | ~30 | Riverlane, Quantinuum, Phasecraft (sw) |
| **Oxford / Harwell** | 300–400 | ~25 | Oxford Ionics, OQC (Reading), Infleqtion, NQCC, Quantum Dice |
| **London** | 200 | ~15 | Quantum Motion (UCL), ORCA, Phasecraft (sw) |
| **Glasgow** | 100 | ~6 | M Squared Lasers |
| **Brighton / Sussex** | 80 | ~6 | Universal Quantum |
| **Sheffield** | ~30–50 | ~2–4 | **Aegiq** |
| **Daresbury (Cheshire)** | ~30 | ~3 | PsiQuantum UK cryogenic R&D |
| **Lancaster** | <20 | ~1 | Quantum Base |

**Verdict for Leeds base:** Quantum HW is more accessible from Yorkshire than space because (i) **Aegiq Sheffield** is genuinely commutable, (ii) **PsiQuantum Daresbury** is ~75 min by car, (iii) **Riverlane / OQC / Quantum Motion** all hire UK-remote for FPGA + control-electronics roles where the work is bench-able offsite during design phases. Aegiq + Riverlane + Quantum Motion is the realistic shortlist.

---

## Notes & Caveats

- **Clearance:** SSTL, Airbus DS UK, In-Space Missions (BAE), RAL Space (HMG), and most defence-adjacent space work require SC/DV. Quantum is mostly *not* clearance-gated except DSTL collaborations and selected NQCC programmes.
- **Funding fragility:** UK launch sector is tiny and brittle (Orbex collapsed Feb 2026; Reaction Engines Oct 2024). Treat pre-orbital launchers as high-risk employment bets.
- **AWS F1 / Versal AI Edge / Ultrascale+ KU/VU** experience is the right FPGA stack for quantum control electronics (Riverlane, OQC, Quantum Motion) and rad-tolerant smallsat OBC (SSTL, Open Cosmos).
- **Cryo-CMOS / mK electronics** is an emerging niche (Quantum Motion, OQC, PsiQuantum) — power-electronics + low-noise mixed-signal background is highly transferable.

## Sources

- [SSTL careers](https://jobs.sstl.co.uk/jobs) · [SSTL about](https://www.sstl.co.uk/about-us)
- [Airbus / Eutelsat 340-sat OneWeb-Gen2 contract Jan 2026](https://www.airbus.com/en/newsroom/press-releases/2026-01-airbus-awarded-eutelsat-contract-for-further-340-low-earth-orbit)
- [Astroscale UK COSMIC mission](https://www.astroscale.com/en/news/astroscale-on-course-for-first-uk-national-mission-to-remove-space-debris) · [Astroscale Harwell facility](https://www.harwellcampus.com/astroscale/)
- [Open Cosmos FPGA Engineer role](https://careers.open-cosmos.com/jobs/7231075-fpga-engineer)
- [In-Space Missions careers](https://apply.workable.com/in-space/) · [In-Space @ BAE](https://spacecareers.uk/employers/17817c21-211e-4faa-81f9-6bb9fe69244c)
- [Spire Global careers](https://spire.com/careers/job-openings/) · [AAC Clyde Space careers](https://www.aac-clyde.space/careers)
- [Skyrora launch licence + Orbex collapse Feb 2026](https://www.electronicsweekly.com/news/business/skyrora-to-buy-select-assets-of-orbex-2026-02/) · [Orbex collapse coverage](https://www.nasaspaceflight.com/2026/02/orbex-collapse-progress-uk-domestic-capability/)
- [SpaceForge careers](https://www.spaceforge.com/careers) · [Oxford Space Systems recruitment](https://oxford.space/Recruitment/) · [Magna Parva](https://magnaparva.com/) · [KISPE](https://www.kispe.co.uk/space-systems/)
- [Goonhilly Earth Station](https://www.harwellcampus.com/space-cluster/) · [RAL Space careers](https://www.ralspace.stfc.ac.uk/Pages/Careers.aspx)
- [Nammo UK Westcott](https://www.nammo.com/location/westcott/) · [Nammo Argonaut RELIANCE engine](https://www.aero-mag.com/nammo-uk-to-supply-engine-for-esa-argonaut-lunar-lander)
- [Reaction Engines administration](https://www.theregister.com/2024/11/01/reaction_engines_administration/)
- [Riverlane jobs](https://www.riverlane.com/jobs) · [Riverlane Deltaflow](https://www.riverlane.com/deltaflow) · [Riverlane QEC roadmap Mar 2026](https://www.riverlane.com/press-release/riverlane-publishes-qec-technology-roadmap)
- [Quantinuum careers](https://jobs.eu.lever.co/quantinuum)
- [OQC company](https://oqc.tech/company/) · [OQC tech-stack 2026 / Genesis](https://echoloc.ai/company/oqc/)
- [Quantum Motion careers](https://quantummotion.com/careers/)
- [ORCA Computing careers](https://orcacomputing.com/careers/) · [ORCA 2026 PT-3](https://www.techjournal.uk/p/orca-computing-targets-quantum-advantage)
- [Universal Quantum jobs](https://www.adzuna.co.uk/jobs/company/universal-quantum)
- [Oxford Ionics careers](https://www.oxionics.com/careers/) · [Quantum Dice](https://www.advancedoxford.com/meet-quantum-dice/)
- [Infleqtion UK / NQCC](https://infleqtion.com/careers/) · [PsiQuantum Daresbury](https://thequantuminsider.com/2023/03/21/psiquantum-opens-uk-rd-quantum-computing-facility/)
- [Aegiq careers](https://apply.workable.com/aegiq) · [Aegiq EE Times feature](https://www.eetimes.com/u-k-startup-scaling-quantum-computing-with-photonics/)
- [M Squared Lasers careers](https://m2lasers.com/careers.html)
- [UK space cluster overview](https://www.gov.uk/government/news/3000-jobs-created-in-one-year-by-resilient-uk-space-sector) · [Harwell Space Cluster](https://www.harwellcampus.com/space-cluster/)
