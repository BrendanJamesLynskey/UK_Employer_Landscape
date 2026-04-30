# Category 06 — Embedded Systems · Embedded Linux · Firmware

> C / modern C++ · Linux kernel · U-Boot · Buildroot · Petalinux · Yocto · device drivers · Cortex-A/M · MIPS · MicroBlaze · Zynq UltraScale+

## Summary

The UK has an unusually deep embedded-Linux / device-driver ecosystem for a country its size, anchored by (a) **Arm** and the Cambridge silicon cluster, (b) a **Manchester–Yorkshire corridor** of specialist consultancies and set-top-box engineering (Codethink, Synamedia, Sky), (c) a **defence/aerospace belt** (Bristol-Cheltenham-Stevenage-Edinburgh-Belfast), and (d) a fast-growing **automotive/robotics** tier (JLR, Wayve, Oxbotica, Dyson, Saga Robotics).

For a Staff-level Zynq-UltraScale+ / Petalinux / Buildroot / kernel-driver engineer in Leeds, the strongest "geographic fit + technical fit" combination sits in **Greater Manchester** (Codethink, Arm Manchester, Siemens EDA), **West Yorkshire** (Synamedia Saltaire, Sky Leeds, BJSS), and **remote-friendly consultancies** (Collabora, Foundries.io, Witekio). Live April 2026 listings for "embedded Linux UK" sit in the **600–900** range across LinkedIn / Indeed / CW Jobs, with **~80–150** specifically calling out kernel / driver work.

## Top UK Employers

| # | Employer | UK site(s) | Embedded SW focus |
|---|----------|------------|-------------------|
| 1 | **Codethink** | Manchester (HQ), remote | Upstream Linux kernel, BSPs, Yocto, automotive Linux (AGL), safety-critical Linux, CIP |
| 2 | **Synamedia** (ex-Cisco Video / Pace lineage) | Saltaire (Shipley), Staines | Linux STB middleware, video pipeline, DRM, secure boot on MIPS/ARM SoCs |
| 3 | **Arm Ltd.** | Cambridge HQ, Manchester, Sheffield, Belfast, Warwick | Linux kernel, Trusted Firmware-A/M, OP-TEE, Mbed, Pelion, hypervisors |
| 4 | **Sky / Comcast / NBCU** | Leeds, Osterley, Livingston | Sky Q/Glass Linux STB, RDK, video middleware |
| 5 | **AMD** (ex-Xilinx) | Cambridge, Edinburgh | Versal / Zynq UltraScale+ Petalinux, FSBL, PMU firmware, AXI drivers |
| 6 | **Collabora** | Remote UK (Cambridge nominal) | Upstream kernel, Mesa, GStreamer, Wayland, Panfrost |
| 7 | **Foundries.io** | Cambridge, remote | LmP (Linux microPlatform) for IoT, OTA, Zephyr |
| 8 | **Imagination Technologies** | Kings Langley, Leeds (small) | PowerVR GPU drivers, Mesa, RISC-V Linux, Catapult |
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
| 21 | **Smith+Nephew** | Hull, York, Watford | Surgical robotics, embedded Linux/RTOS |
| 22 | **Siemens EDA / DISW** | Manchester (Didsbury), Cambridge | Embedded SW for industrial, Mentor Embedded Linux legacy |
| 23 | **ByteSnap Design** | Birmingham, remote | Embedded Linux/Yocto consultancy, BSPs |
| 24 | **Witekio (Avnet)** | Reading, remote | Linux/Android BSP consultancy |
| 25 | **2net (Embedded)** | Sheffield | Embedded Linux consultancy, Buildroot/Yocto |

Honourable mentions: **XMOS** (Bristol — voice DSP), **AMS Neve** (Burnley — pro-audio embedded), **BBC R&D** (Salford MediaCity), **Saga Robotics** (York — Thorvald ag-robot Linux), **Cobham Ultra** (Cheltenham), **MBDA** (Stevenage/Bristol), **Nokia / Ericsson** (Bristol/Reading — 5G base-station Linux), **Liberty Global / VMO2** (Bradford, Reading — Connect Box / RDK), **Pulsiv** (Plymouth — power-electronics firmware), **Ubisense** (Cambridge), **Bosch / Five.ai** (Cambridge — AV).

## Regional Concentration

| Region | Score (1–10) | Key employers |
|--------|--------------|---------------|
| Cambridge / East Anglia | 10 | Arm, AMD, Collabora, Foundries.io, CMR, Apple, MediaTek |
| **Greater Manchester** | **8** | **Codethink**, Arm Manchester, Siemens EDA Didsbury, BBC R&D Salford, Roke Manchester, JLR SDV, Thales |
| **West Yorkshire** (Leeds/Bradford/Saltaire) | **7** | **Synamedia Saltaire**, **Sky Leeds**, BJSS, Liberty Global Bradford, Imagination (small Leeds) |
| Bristol / Bath | 8 | NVIDIA, Dyson, XMOS, Graphcore (winding down), Leonardo, Nokia, Toshiba |
| London / Thames Valley | 8 | Canonical, Sky Osterley, Wayve, Synamedia Staines, AWS, Witekio Reading |
| Edinburgh / Scotland | 6 | AMD Edinburgh, Leonardo, Sky Livingston, Codeplay (Intel) |
| Belfast / NI | 5 | Arm Belfast, Allstate (less embedded) |
| **South Yorkshire** (Sheffield) | **5** | **2net**, Arm Sheffield, McLaren Applied (close) |
| West Midlands (Birmingham/Coventry) | 7 | ByteSnap, JLR Gaydon/Whitley, Siemens, Aston Martin |
| Cheltenham / Malvern | 6 | QinetiQ, Cobham Ultra, GCHQ-adjacent, Spirent |
| **Hull / York** | **5** | **Smith+Nephew**, **Saga Robotics**, Renishaw York |

## Live job postings (April 2026 snapshot, indicative)

- LinkedIn UK "embedded Linux": **~620** results; "kernel engineer": **~140**; "device driver" UK: **~210**
- Indeed UK "embedded software engineer": **~900**; "firmware engineer": **~480**
- CW Jobs "embedded Linux": **~310**
- Codethink careers page: ~6–8 open SW roles
- Synamedia careers: ~4 Saltaire embedded roles
- AMD UK careers (Versal/Zynq SW): ~10 UK roles tagged Cambridge/Edinburgh
- Arm careers UK kernel/firmware: ~25 roles

## Yorkshire & Greater Manchester focus

This corridor is the **highest-leverage** target set:

- **Codethink (Manchester)** — the UK's flagship upstream-Linux consultancy. Public roles regularly want exactly this stack: kernel, BSP, Yocto/Buildroot, MISRA-C, automotive (CIP, ELISA, AGL). Hybrid Manchester or remote.
- **Synamedia (Saltaire)** — direct corporate descendant of Pace plc; the Saltaire site still does Linux set-top-box work on Broadcom/MediaTek SoCs. Roles for "Senior Embedded SW Engineer" and "Video Software Engineer" recur. ~30 min from Leeds.
- **Sky / Comcast (Leeds)** — Sky Glass / Sky Stream platform team in Leeds Dock; RDK-B, Linux middleware, secure boot.
- **Arm (Manchester & Sheffield)** — Manchester (Hardman Square) does CPU verification but also Mali/SystemReady SW; Sheffield does kernel & firmware.
- **Siemens DISW (Didsbury, Manchester)** — Mentor Embedded Linux legacy, automotive Capital, industrial.
- **2net (Sheffield)** — small but pure embedded-Linux consultancy on the doorstep; worth a direct approach even when no role is listed.
- **BJSS / CDW (Leeds)** — increasingly does embedded/IoT delivery for clients.
- **BBC R&D (Salford MediaCity)** — research-engineer roles around broadcast embedded, ATSC 3.0, AV1 hardware.
- **Smith+Nephew (Hull/York)** — surgical robotics & advanced wound-care embedded.
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
