# Category 03 — FPGA / RTL / Digital Design

> Xilinx UltraScale+ · Vivado · AWS EC2 F1 · VHDL · Verilog · SystemVerilog · AXI/AHB/APB

## Summary

The UK FPGA/RTL/digital-design landscape in April 2026 is dominated by three pillars: **defence & aerospace** (the largest single demand source — driven by sustained MoD spend, Tempest/GCAP, and DragonFire), **semiconductor IP & SoC** (Arm, Imagination, AMD, NVIDIA — heavily Cambridge-centric but with growing Manchester and Sheffield satellites), and **comms / test & measurement** (5G PHY, network test, radar). Quantum computing has emerged as a meaningful new employer cluster (Riverlane, OQC, Quantum Motion) needing control-electronics RTL skills. For a Staff-level VHDL/Verilog/SV engineer with UltraScale+ and AWS F1 credentials, the strongest geographic matches are **Manchester (Arm, Raytheon, MBDA Bolton, BBC R&D Salford)**, **Sheffield (Arm)**, and **UK-remote roles via defence primes and IP houses**.

## Top UK Employers

| # | Employer | UK FPGA Locations | What They Design |
|---|----------|-------------------|------------------|
| 1 | **BAE Systems** (Digital Intel. / Air / Maritime) | Rochester, Chelmsford, Edinburgh, Glasgow, Frimley | Radar DSP, EW, secure comms, Typhoon/Tempest mission systems |
| 2 | **Leonardo UK** | Edinburgh (Crewe Toll), Luton, Basildon, Bristol, Lincoln, Newcastle | AESA radar (Captor-E), DRFM EW, IRST, helicopter avionics |
| 3 | **MBDA UK** | Stevenage, Bristol, **Bolton** | Missile seekers, datalinks, RF FPGA |
| 4 | **Thales UK** | Crawley, Glasgow, Reading, Templecombe, Cheadle Heath | Sonar, optronics, comms, IFF |
| 5 | **Roke Manor Research** | Romsey, Gloucester, Manchester | SIGINT, EW, secure comms, AI accel |
| 6 | **QinetiQ** | Malvern, Farnborough, Portsmouth | Sensor R&D, EW, autonomy |
| 7 | **Raytheon UK** | Harlow, **Manchester**, Glenrothes, Gloucester | EW, radar, secure comms |
| 8 | **Northrop Grumman UK** | New Malden, Cheltenham, Fareham | C4ISR, mission systems |
| 9 | **General Dynamics UK / Mission Systems** | Hastings, Oakdale, Bristol | Bowman, Morpheus tactical comms |
| 10 | **Cobham Ultra / TP Group** | Greenford, Cheltenham, Loudwater, Weymouth | Sonobuoys, crypto, ASW |
| 11 | **Arm** | Cambridge, **Manchester**, **Sheffield**, Belfast | CPU/GPU/NPU RTL, verification |
| 12 | **Imagination Technologies** | Kings Langley HQ, Cambridge (no Leeds office &mdash; common misconception) | GPU, AI accel, RISC-V SoC |
| 13 | **AMD (Xilinx)** | Cambridge, Edinburgh, Belfast | Adaptive SoC, Versal, EPYC verif |
| 14 | **NVIDIA UK** (Mellanox / Bright) | Bristol, Cambridge | DPU/SmartNIC, AI infra RTL |
| 15 | **Nokia / Nokia Bell Labs** | Cambridge, Bristol | 5G/6G PHY, optical |
| 16 | **Picocom** | Bath, Cambridge | 5G O-RAN small-cell PHY ASIC/FPGA |
| 17 | **AccelerComm** | Southampton | 5G channel coding IP |
| 18 | **Keysight Technologies** | South Queensferry, Stevenage, Winnersh | VNA, oscilloscope, BERT FPGA |
| 19 | **Spirent Communications** | Crawley, Honiton, Paignton | Network test, GNSS sim |
| 20 | **Riverlane** | Cambridge | Quantum error-decoder FPGA (Deltaflow) |
| 21 | **Oxford Quantum Circuits / Quantum Motion** | Reading, London | Qubit control electronics |
| 22 | **BBC R&D** | **Salford (MediaCity)**, London | UHD/IP video, AI broadcast |
| 23 | **CommScope** (ex-Pace via Arris) | **Salts Mill, Saltaire** | Set-top boxes, cable modems, Wi-Fi gateways &mdash; the actual current occupant at the old Pace site. Some FPGA work remains on home-networking platforms. |
| 23b | **Synamedia** (ex-Cisco Video / NDS) | Staines-upon-Thames (no Yorkshire site) | Video headend, encoders &mdash; a *separate* company from CommScope/Pace, often confused. |
| 23c | **Calrec Audio** (Audiotonix) | **Hebden Bridge** (Nutclough Mill) | Live-broadcast audio mixing console FPGA / DSP &mdash; Argo, Type R, ImPulse1 ST2110. |
| 23d | **Curvalux** | **Sheffield** (Electric Works, Sheaf St) + planned £20M factory near **AMRC Rotherham** | Software-defined, multi-beam phased-array antenna FPGA for solar-efficient fixed-wireless-access broadband (sub-7 GHz Wi-Fi 6E, moving to mmWave). FPGA-heavy. ~17 staff April 2026, growing on £8M SCR R&amp;D grant. Direct FPGA + RF + DSP fit, ~40 min from Leeds. [curvalux.com/careers](https://curvalux.com/careers/) |
| 24 | **Sony Europe B2B / Professional Solutions** | Basingstoke, Pencoed | Broadcast cameras, IP video |
| 25 | **XMOS** | Bristol | xcore audio/AIoT SoC |
| 26 | **Cambridge Consultants / TTP / Sagentia / Plextek / PA** | Cambridge cluster | Consultancy — medical, IoT, industrial FPGA |

## Regional Concentration

| Region | Est. FPGA Headcount | Live Reqs Apr 2026 | Key Anchors |
|--------|---------------------|--------------------|-----------|
| **Cambridge & East** | 2,500+ | ~120 | Arm, AMD, Imagination, Nokia, Riverlane, CCL, TTP |
| **Bristol & SW** | 800–1,000 | ~55 | MBDA, Leonardo, NVIDIA, XMOS, Picocom, Graphcore |
| **Stevenage / Herts / Beds** | 700 | ~45 | MBDA, Airbus DS, Keysight, Anritsu, Leonardo Luton |
| **Edinburgh / Glasgow / Fife** | 900 | ~50 | Leonardo (Crewe Toll), BAE, Thales Glasgow, Keysight Queensferry, Raytheon Glenrothes |
| **Crawley / Sussex** | 500 | ~30 | Thales UK HQ, Spirent, Lockheed Martin |
| **Cheltenham / Malvern / Worcs** | 600 | ~35 | QinetiQ, Northrop, Raytheon, GCHQ-adjacent SMEs |
| **Greater Manchester** | 350–450 | ~25 | BAE Warton-adjacent, MBDA Bolton, Raytheon Manchester, Arm Manchester, Thales Cheadle, Roke MCR, BBC R&D Salford |
| **Sheffield / S. Yorks** | 80–120 | ~6–8 | Arm Sheffield, AESSEAL/specialist SMEs |
| **Leeds / W. Yorks** | 100–150 | ~8–10 | Blaize Leeds, **CommScope (ex-Pace) Saltaire**, **Calrec Audio (Hebden Bridge)**, Rockley/medical, defence SMEs |
| **Sheffield / S. Yorks** (revised) | 120–180 | ~10–14 | Arm Sheffield, **EnSilica Sheffield**, **Curvalux (Electric Works + AMRC Rotherham)**, AESSEAL, specialist SMEs |
| **Reading / Thames Valley** | 500 | ~30 | Thales, Cisco, Microsoft, Rohde & Schwarz |
| **Hampshire** (Romsey/Soton) | 400 | ~25 | Roke, AccelerComm, IBM Hursley |
| **Rochester / Kent / Essex** | 500 | ~30 | BAE Rochester, Leonardo Basildon |

## Yorkshire & Greater Manchester focus

- **Arm Manchester** (Citylabs / Spinningfields) — CPU verification, ~80–120 engineers, frequent SV/UVM reqs.
- **Arm Sheffield** — smaller (~30–50), CPU design verification, opened 2021 satellite, growing.
- **MBDA Bolton** — missile electronics, expanding under DragonFire and CAMM-MR; FPGA roles posted regularly. Direct M62 commute from Leeds (~90 min).
- **Raytheon UK Manchester** (Broughton St) — EW & radar signal processing; consistent VHDL/Verilog hiring.
- **Thales Cheadle Heath** (Stockport) — IFF and secure comms; FPGA/RTL roles 2–4 open at any time.
- **Roke Manchester** (Spinningfields) — newer SIGINT satellite, ~30 engineers, mix of FPGA + AI.
- **BBC R&D Salford** — 25–30 R&D engineers; occasional FPGA roles for live IP video / UHD; very high cultural fit given Pace/broadcast background.
- **CommScope at Salts Mill, Saltaire** — the actual successor to Pace plc (Pace &rarr; Arris &rarr; CommScope); intermittent FPGA hiring for video pipeline / home-networking work. *Synamedia is a separate company at Staines and has no Yorkshire site.*
- **Calrec Audio, Hebden Bridge** — live-broadcast audio mixing consoles; FPGA / DSP work on the Argo / Type R / ImPulse1 platforms.
- **Curvalux, Sheffield (Electric Works) + AMRC Rotherham** — solar-efficient fixed-wireless-access broadband; software-defined multi-beam phased-array antennas, FPGA-heavy, moving from Wi-Fi 6E into mmWave. £8M SCR Mayoral Combined Authority R&D grant; £20M Rotherham factory planned. Small (~17) but growing. Excellent FPGA + RF + DSP + power fit.

Realistic verdict: **8–12 live FPGA roles** across Yorkshire+GM at any moment. The pragmatic strategy is **UK-remote southern primes** (BAE, Leonardo, MBDA Stevenage, AMD, Picocom, AccelerComm) plus the Bolton/Cheadle/Manchester cluster.

## Notes & Caveats

- Most defence roles require **SC** or **DV clearance** (UK national, 5–10 yr residency). Profile qualifies.
- **AWS F1** experience is rare in UK and a differentiator for AMD, NVIDIA, Picocom, Riverlane, AccelerComm.
- Broadcast-video FPGA demand has shrunk since 2018 (IP-over-Ethernet displaced custom SDI hardware) — Pace/Synamedia/Sony hiring is thin.
- Quantum-control RTL is a fast-growing niche; fewer than 200 UK roles total but doubling YoY.
- Recruiters worth a direct call: **IC Resources**, **Vivid Resourcing**, **ECM Selection**, **EmbeddedJobs**, **Real Staffing**, **Coreco**.

## Sources

- <https://www.baesystems.com/en/careers>
- <https://uk.leonardo.com/en/careers>
- <https://www.mbdacareers.co.uk/>
- <https://www.thalesgroup.com/en/countries/europe/united-kingdom/careers>
- <https://www.roke.co.uk/careers>
- <https://careers.qinetiq.com/>
- <https://careers.rtx.com/global/en/raytheon>
- <https://www.arm.com/company/careers>
- <https://careers.amd.com/>
- <https://www.nvidia.com/en-us/about-nvidia/careers/>
- <https://www.imaginationtech.com/careers/>
- <https://picocom.com/careers/>
- <https://www.accelercomm.com/careers>
- <https://www.riverlane.com/careers>
- <https://www.bbc.co.uk/rd/jobs>
- <https://careers.commscope.com/location/saltaire-jobs/8610/2635167-6269131-2638652/4>
- <https://calrec.com/careers/>
- <https://www.synamedia.com/careers/>
- <https://careers.keysight.com/>
- <https://careers.spirent.com/>
- <https://www.linkedin.com/jobs/search/?keywords=FPGA&location=United%20Kingdom>
- <https://www.icresources.com/>
- <https://www.vividresourcing.com/>
