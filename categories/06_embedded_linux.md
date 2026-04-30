# Category 06 — Embedded Systems · Embedded Linux · Firmware

> C / modern C++ · Linux kernel · U-Boot · Buildroot · Petalinux · Yocto · device drivers · Cortex-A/M · MIPS · MicroBlaze · Zynq UltraScale+

## Summary

The UK has an unusually deep embedded-Linux / device-driver ecosystem for a country its size, anchored by (a) **Arm** and the Cambridge silicon cluster, (b) a **Manchester–Yorkshire corridor** of specialist consultancies and set-top-box engineering (Codethink, **CommScope ex-Pace at Saltaire**, Sky Leeds), (c) a **defence/aerospace belt** (Bristol-Cheltenham-Stevenage-Edinburgh-Belfast), and (d) a fast-growing **automotive/robotics** tier (JLR, Wayve, Oxbotica, Dyson, Saga Robotics).

For a Staff-level Zynq-UltraScale+ / Petalinux / Buildroot / kernel-driver engineer in Leeds, the strongest "geographic fit + technical fit" combination sits in **Greater Manchester** (Codethink, Arm Manchester, Siemens EDA), **West Yorkshire** (CommScope Saltaire, Sky Leeds, Calrec Audio Hebden Bridge, BJSS), and **remote-friendly consultancies** (Collabora, Foundries.io, Witekio). Live April 2026 listings for "embedded Linux UK" sit in the **600–900** range across LinkedIn / Indeed / CW Jobs, with **~80–150** specifically calling out kernel / driver work.

## Top UK Employers

| # | Employer | UK site(s) | Embedded SW focus |
|---|----------|------------|-------------------|
| 1 | **Codethink** | Manchester (HQ), remote | Upstream Linux kernel, BSPs, Yocto, automotive Linux (AGL), safety-critical Linux, CIP |
| 2 | **CommScope** (ex-Pace via Arris) | **Salts Mill, Saltaire** (Shipley) | The actual successor to Pace plc at the Saltaire site (Pace &rarr; Arris 2016 &rarr; CommScope 2019). Linux STB / cable-modem / Wi-Fi-gateway middleware, RDK, secure boot on Broadcom/MediaTek SoCs. *Note: Synamedia is a separate company at Staines &mdash; NOT at Saltaire.* [careers.commscope.com](https://careers.commscope.com/location/saltaire-jobs/8610/2635167-6269131-2638652/4) |
| 2b | **Synamedia** (ex-Cisco Video / NDS) | Staines-upon-Thames + global | Video headend, anti-piracy, OTT delivery. Embedded Linux work primarily at Staines. *Different company* from CommScope/Pace. |
| 3 | **Arm Ltd.** | Cambridge HQ, Manchester, Sheffield, Belfast, Warwick | Linux kernel, Trusted Firmware-A/M, OP-TEE, Mbed, Pelion, hypervisors |
| 4 | **Sky / Comcast / NBCU** | Leeds, Osterley, Livingston | Sky Q/Glass Linux STB, RDK, video middleware |
| 5 | **AMD** (ex-Xilinx) | Cambridge, Edinburgh | Versal / Zynq UltraScale+ Petalinux, FSBL, PMU firmware, AXI drivers |
| 6 | **Collabora** | Remote UK (Cambridge nominal) | Upstream kernel, Mesa, GStreamer, Wayland, Panfrost |
| 7 | **Foundries.io** | Cambridge, remote | LmP (Linux microPlatform) for IoT, OTA, Zephyr |
| 8 | **Imagination Technologies** | Kings Langley HQ, Cambridge (no Leeds office &mdash; common misconception) | PowerVR GPU drivers, Mesa, RISC-V Linux, Catapult |
| 9 | **NVIDIA** | Bristol, Cambridge | Jetson / DRIVE Linux BSPs, Tegra kernel |
| 10 | **Canonical** | Fully remote UK (London nominal) | Ubuntu Core, snapd, IoT, Optee integration |
| 11 | **CMR Surgical** | Cambridge | Versius robot — Linux on Zynq, RT control, safety |
| 12 | **JLR** | Gaydon, Whitley, Manchester (SDV hub) | IVI Linux, AGL, Yocto, secure boot, ECU firmware |
| 13 | **Wayve** | London, Oxford | AV stack on automotive Linux, sensor drivers |
| 14 | **Dyson** | Malmesbury, Bristol | Robot vacuum & appliance Linux, RTOS, motor drivers |
| 15 | **BAE Systems / Digital Intel.** | Guildford, Gloucester, Manchester, Lancashire | Secure embedded Linux, crypto, radar/EW firmware |
| 16 | **Leonardo UK** | Edinburgh, Luton, Lincoln, Bristol | Avionics Linux, RT, FPGA-attached SW |
| 17 | **Thales UK** | Reading, Crawley, Glasgow, Manchester | Defence Linux, transport (signalling), comms |
| 18 | **Roke Manor** | Romsey, Manchester | Defence/comms embedded, SDR, Yocto BSPs |
| 19 | **QinetiQ** | Malvern, Farnborough | Embedded R&D, sensor systems |
| 20 | **Renishaw** | Wotton-under-Edge, York | Metrology embedded, Linux on Zynq |
| 21 | **Smith+Nephew** | **Hull** + new Melton facility ($100M+, under construction); Watford | Advanced Wound Management R&D Centre of Excellence — signal processing, imaging, chemistry, embedded Linux. *York site closed 2016.* |
| 22 | **Siemens EDA / DISW** | Manchester (Didsbury), Cambridge | Embedded SW for industrial, Mentor Embedded Linux legacy |
| 23 | **ByteSnap Design** | Birmingham, remote | Embedded Linux/Yocto consultancy, BSPs |
| 24 | **Witekio (Avnet)** | Reading, remote | Linux/Android BSP consultancy |
| 25 | **2net (Embedded)** | Sheffield | Embedded Linux consultancy, Buildroot/Yocto |
| 26 | **Curvalux** | **Sheffield (Electric Works) + planned AMRC Rotherham factory** | Embedded Linux on phased-array fixed-wireless edge nodes; FPGA + ARM SoC + RTOS / kernel work. ~17 staff April 2026, scaling on £8M SCR grant. Direct local fit (~40 min from Leeds). [curvalux.com](https://curvalux.com/) |

Honourable mentions: **XMOS** (Bristol — voice DSP), **AMS Neve** (Burnley — pro-audio embedded), **BBC R&D** (Salford MediaCity), **Saga Robotics** (York — Thorvald ag-robot Linux), **Cobham Ultra** (Cheltenham), **MBDA** (Stevenage/Bristol), **Nokia / Ericsson** (Bristol/Reading — 5G base-station Linux), **Liberty Global / VMO2** (Bradford, Reading — Connect Box / RDK), **Pulsiv** (Plymouth — power-electronics firmware), **Ubisense** (Cambridge), **Bosch / Five.ai** (Cambridge — AV).

## Regional Concentration

| Region | Score (1–10) | Key employers |
|--------|--------------|---------------|
| Cambridge / East Anglia | 10 | Arm, AMD, Collabora, Foundries.io, CMR, Apple, MediaTek |
| **Greater Manchester** | **8** | **Codethink**, Arm Manchester, Siemens EDA Didsbury, BBC R&D Salford, Roke Manchester, JLR SDV, Thales |
| **West Yorkshire** (Leeds/Bradford/Saltaire/Hebden Bridge) | **7** | **CommScope (Salts Mill, Saltaire)**, **Sky Leeds**, **Calrec Audio (Hebden Bridge)**, BJSS, Liberty Global Bradford |
| Bristol / Bath | 8 | NVIDIA, Dyson, XMOS, Graphcore (winding down), Leonardo, Nokia, Toshiba |
| London / Thames Valley | 8 | Canonical, Sky Osterley, Wayve, Synamedia Staines, AWS, Witekio Reading |
| Edinburgh / Scotland | 6 | AMD Edinburgh, Leonardo, Sky Livingston, Codeplay (Intel) |
| Belfast / NI | 5 | Arm Belfast, Allstate (less embedded) |
| **South Yorkshire** (Sheffield / Rotherham) | **6** | **2net**, Arm Sheffield, **Curvalux (Electric Works + AMRC Rotherham)**, **EnSilica Sheffield**, McLaren Applied (close) |
| West Midlands (Birmingham/Coventry) | 7 | ByteSnap, JLR Gaydon/Whitley, Siemens, Aston Martin |
| Cheltenham / Malvern | 6 | QinetiQ, Cobham Ultra, GCHQ-adjacent, Spirent |
| **Hull / York** | **5** | **Smith+Nephew (Hull)**, **Saga Robotics (York)**, **Renishaw York** |

## Live job postings (April 2026 snapshot, indicative)

- LinkedIn UK "embedded Linux": **~620** results; "kernel engineer": **~140**; "device driver" UK: **~210**
- Indeed UK "embedded software engineer": **~900**; "firmware engineer": **~480**
- CW Jobs "embedded Linux": **~310**
- Codethink careers page: ~6–8 open SW roles
- CommScope careers (Saltaire): ~3–6 embedded SW / video / Wi-Fi gateway roles at any time
- AMD UK careers (Versal/Zynq SW): ~10 UK roles tagged Cambridge/Edinburgh
- Arm careers UK kernel/firmware: ~25 roles

## Yorkshire & Greater Manchester focus

This corridor is the **highest-leverage** target set:

- **Codethink (Manchester)** — the UK's flagship upstream-Linux consultancy. Public roles regularly want exactly this stack: kernel, BSP, Yocto/Buildroot, MISRA-C, automotive (CIP, ELISA, AGL). Hybrid Manchester or remote.
- **CommScope (Salts Mill, Saltaire)** — the actual corporate descendant of Pace plc (Pace &rarr; Arris 2016 &rarr; CommScope 2019); the Saltaire site still does Linux set-top-box / cable-modem / gateway work on Broadcom/MediaTek SoCs. Roles for "Senior Embedded SW Engineer" and "Video Software Engineer" recur. ~30 min from Leeds. *Synamedia is a different company in Staines &mdash; common confusion.*
- **Calrec Audio (Hebden Bridge)** — pro-broadcast audio mixing consoles; firmware / embedded Linux / DSP roles at Nutclough Mill. ~40 min from Leeds.
- **Sky / Comcast (Leeds)** — Sky Glass / Sky Stream platform team in Leeds Dock; RDK-B, Linux middleware, secure boot.
- **Arm (Manchester & Sheffield)** — Manchester (Hardman Square) does CPU verification but also Mali/SystemReady SW; Sheffield does kernel & firmware.
- **Siemens DISW (Didsbury, Manchester)** — Mentor Embedded Linux legacy, automotive Capital, industrial.
- **2net (Sheffield)** — small but pure embedded-Linux consultancy on the doorstep; worth a direct approach even when no role is listed.
- **BJSS / CDW (Leeds)** — increasingly does embedded/IoT delivery for clients.
- **BBC R&D (Salford MediaCity)** — research-engineer roles around broadcast embedded, ATSC 3.0, AV1 hardware.
- **Smith+Nephew (Hull)** — Advanced Wound Management R&D Centre of Excellence; signal processing, embedded Linux. New $100M+ Melton (near Hull) facility under construction. *York site closed 2016 &mdash; previous drafts wrongly listed it as still active.*
- **Saga Robotics (York)** — Thorvald agricultural robot, ROS on Linux, Zynq-class control.
- **Renishaw (York)** — metrology, lots of Zynq-on-Linux opportunities.
- **JLR Manchester SDV hub** (announced 2024, ramping 2025–26) — software-defined-vehicle Linux platform team.

## Notes & Caveats

- **Defence employers** (BAE, Leonardo, Thales, Roke, MBDA, QinetiQ, AWE, Cobham Ultra) almost always require **SC clearance**, often **DV**; British nationality usually mandatory.
- **Hyperscaler embedded** (AWS Greengrass, Microsoft Azure Sphere) is now thin in the UK — Azure Sphere has been deprecated; AWS IoT embedded teams are mostly in Seattle/Dublin.
- **Graphcore** has scaled back hardware SW hiring after 2024 restructuring.
- **Five.ai** was acquired by Bosch in 2022 — UK AV embedded work continues under Bosch Cambridge.
- **Pelion** was sold by Arm to Izuma Networks (2023) — much-reduced UK footprint.
- The **Manchester SDV hub at JLR** and **Codethink's automotive practice** are likely to be the fastest-growing UK embedded-Linux hiring centres through 2026–27.

## Sources

- <https://www.codethink.co.uk/jobs/>
- <https://careers.commscope.com/location/saltaire-jobs/8610/2635167-6269131-2638652/4>
- <https://calrec.com/careers/>
- <https://www.synamedia.com/careers/>
- <https://careers.arm.com>
- <https://careers.sky.com>
- <https://careers.amd.com>
- <https://www.collabora.com/careers.html>
- <https://www.foundries.io/company/careers/>
- <https://canonical.com/careers>
- <https://www.imaginationtech.com/careers/>
- <https://www.nvidia.com/en-gb/about-nvidia/careers/>
- <https://cmrsurgical.com/careers>
- <https://www.jaguarlandrovercareers.com>
- <https://wayve.ai/careers/>
- <https://careers.dyson.com>
- <https://www.baesystems.com/en/careers>
- <https://uk.leonardo.com/en/careers>
- <https://www.thalesgroup.com/en/countries/europe/united-kingdom/careers>
- <https://www.roke.co.uk/careers>
- <https://www.qinetiq.com/en/careers>
- <https://www.renishaw.com/en/careers>
- <https://www.smith-nephew.com/careers/>
- <https://jobs.siemens.com>
- <https://www.bytesnap.com/careers/>
- <https://witekio.com/careers/>
- <https://www.2net.co.uk>
- <https://www.bbc.co.uk/rd/jobs>
- <https://www.sagarobotics.com/careers>
- <https://uk.linkedin.com/jobs>
- <https://www.indeed.co.uk>
- <https://www.cwjobs.co.uk>
