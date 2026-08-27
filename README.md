# Awesome-Chip-Design-Collaboration

## Top Chip Design Collaboration Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on IC Design Data Management, EDA Collaboration, Version Control for Hardware, IP Lifecycle & RTL-to-GDS Team Workflows*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Chip Design Collaboration**. These systems help semiconductor and electronics teams manage design data, share IP, version hardware projects, review changes, and coordinate multi-site EDA workflows from RTL through physical design.

**Examples** include Altium 365, Cadence Cloud, Siemens Teamcenter EDA, GitLab, Perforce Helix Core, Aldec HES-DVM, DesignSync, Methodics IPLM, Cliosoft SOS, and OpenLane Cloud (the category leaders / relevant platforms).

**Open-source emphasis**: Full enterprise IC design data management (IPLM/DM) is largely commercial. Strong open foundations exist in **Git/GitLab**, **OpenROAD**, **OpenLane / LibreLane**, **FuseSoC**, and the broader open-source silicon ecosystem. This section is expanded with these tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Description / Focus | Starting Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Altium 365](https://www.altium.com/altium-365)** | Cloud collaboration platform for PCB and electronics design — shared workspaces, version control, review, and supply-chain data tightly integrated with Altium Designer. | Starts at **$1,990/year** (Altium Develop tier) / **$3,850/seat/year** (Standard Plan) | **30-day free trial** with full platform access (designs lock to read-only post-trial); perpetual free access to web-based **Altium 365 Viewer** (read/markup only). |
| **[Cadence Cloud](https://www.cadence.com/)** | Cloud EDA environment offering SaaS access to digital/analog design, simulation, and verification tools (OrCAD, Allegro, Clarity, Sigrity). | Starts at **$10/token** via OnCloud (pay-as-you-go packages on 30-day renewal cycles; tool burn rates start at ~0.75 tokens/hr) | **30-day free trial** capped at **8 compute hours** (whichever expires first) for select OnCloud packages. |
| **[Siemens Teamcenter EDA](https://www.siemens.com/)** | Cloud-native PLM and design data management (Teamcenter X) tailored for semiconductor, PCB, and multi-domain engineering collaboration. | Starts at **$165.38/user/month** (Teamcenter X Essentials tier, billed annually) | **30-day free trial** with pre-configured cloud sandbox, guided tutorials, and sample dataset access. |
| **[GitLab](https://about.gitlab.com/)** | DevOps & CI/CD platform widely adopted by hardware teams for RTL versioning, continuous verification pipelines, and IP governance. | Starts at **$29/user/month** (Premium tier, billed annually at $348/year); **$0/month** (Free tier) | **Free forever plan**: Up to 5 users/namespace, 400 CI/CD compute minutes/month, and 5 GiB storage/namespace; **30-day free trial** for Ultimate. |
| **[Perforce Helix Core](https://www.perforce.com/products/helix-core)** | Scalable version control system built for massive binary and IC design repositories (GDSII, OASIS, analog/digital assets). | Starts at **$39/user/month** (P4 Cloud managed SaaS; includes 64 GiB storage); **$0** for self-managed server | **Free forever plan** for up to **5 users and 20 workspaces** (self-hosted / BYO cloud instance); managed P4 Cloud SaaS does not offer a free trial. |
| **[Aldec HES-DVM](https://www.aldec.com/)** | Hardware emulation, prototyping, and verification platform supporting multi-user simulation acceleration and FPGA prototyping workflows. | Starts at **~$1,500/seat/year** for desktop verification tiers (Riviera-PRO/Active-HDL; enterprise emulation quoted per seat/capacity) | **20-day free evaluation trial** (fully functional, node-locked license tied to MAC address); perpetual free **Student Edition** for coursework. |
| **[DesignSync](https://www.3ds.com/)** | Semiconductor design data management (ENOVIA / Dassault Systèmes) integrated with EDA frameworks (Cadence Virtuoso, Synopsys) for multi-site IC vaulting. | Starts at **~$345/user/quarter** (~$115/user/month) for entry 3DEXPERIENCE cloud platform access | **14 to 30-day proof-of-concept (PoC) evaluation** upon vendor qualification (guided technical onboarding; no open self-service trial). |
| **[Methodics IPLM](https://www.perforce.com/products/helix-iplm)** | IP Lifecycle Management platform (Perforce Helix IPLM) delivering IP cataloging, metadata tracking, dependency management, and traceability for SoC teams. | Starts at **~$2,500/user/year** (entry enterprise subscription tier for IP tracking and catalog modules) | **14-day guided proof-of-concept (PoC) trial** with sandbox access upon sales qualification (no public self-serve tier). |
| **[Cliosoft SOS](https://www.keysight.com/)** | Purpose-built IC design data management and hardware version control platform (now Keysight EDM) supporting analog/mixed-signal and digital EDA flows. | Starts at **~$2,000/seat/year** (entry multi-user licensing bundles for IC design teams) | **30-day evaluation trial license** available via Keysight Knowledge Center registration with host ID validation. |
| **[OpenLane Cloud / ChipFoundry](https://chipfoundry.io/)** | Turnkey open-silicon shuttle and cloud-hosted RTL-to-GDS flow hosting (ChipFoundry / Tiny Tapeout / OpenROAD ecosystem) for collaborative chip tapeouts. | Starts at **€70/tile** (~$75/tile via Tiny Tapeout) / **$3,500** for ChipIgnite Mini shuttle; OpenLane engine is **$0 (open-source)** | **Free forever tier**: Unlimited local RTL-to-GDS runs via open-source toolchain; shuttle verification CI and DRC/LVS preview checks are free. |

## Open-Source GitHub Projects
- **[Git + GitLab CE / Gitea / Forgejo](https://gitlab.com/)**  
  Foundational open version control and collaboration platforms used by the vast majority of open hardware and many commercial chip teams for RTL, constraints, and scripts.

- **[OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD)**  
  Leading open-source digital implementation application (placement, routing, optimization) enabling collaborative, scriptable physical design flows.

- **[OpenLane / LibreLane](https://github.com/The-OpenROAD-Project/OpenLane)**  
  Automated open RTL-to-GDSII flows built on OpenROAD, Yosys, Magic, and related tools — widely used for academic and open-silicon collaboration and tapeouts.

- **[Yosys](https://github.com/YosysHQ/yosys)**  
  Open-source synthesis framework central to collaborative open ASIC and FPGA design pipelines.

- **[FuseSoC](https://github.com/olofk/fusesoc)**  
  Package manager and build system for HDL that helps teams share, version, and compose hardware IP cores.

- **[KLayout](https://www.klayout.de/)**  
  Open-source layout viewer and editor heavily used in open and commercial flows for GDS review and collaboration.

- **[Magic VLSI & Netgen](https://github.com/RTimothyEdwards)**  
  Open layout and LVS tools that support collaborative physical verification in open PDK flows (e.g. SkyWater, GF180).

- **[cocotb, Verilator, Icarus Verilog](https://github.com/)**  
  Open simulation and verification frameworks that enable shared testbenches and CI-based regression for hardware teams.

- **[Open PDKs (SkyWater, GF180, IHP, etc.)](https://github.com/)**  
  Open process design kits that make multi-organization collaboration on real silicon feasible without proprietary PDK barriers.

- **[Hardware CI templates and silicon CI projects](https://github.com/)**  
  Community GitHub Actions / GitLab CI templates for lint, simulation, formal, and OpenLane runs on every pull request.

### Additional Strong Open-Source Options
- Using Git LFS or Git-annex for larger design artifacts alongside RTL in Git.
- Chisel/FIRRTL, SpinalHDL, and other generator frameworks for collaborative parameterized design.
- OpenFPGA and related open FPGA toolchains for shared programmable-logic work.
- Jupyter/Python flows wrapping OpenROAD for exploratory collaborative design.
- Public MPW shuttle infrastructure (e.g. historic Efabless/Google, ChipFoundry, and similar) as collaboration venues.

**Frameworks for building custom systems**: Version all RTL, constraints, and scripts in **Git** (GitLab/Gitea), package IP with **FuseSoC**, run **Yosys + OpenROAD + OpenLane/LibreLane** in CI for every change, and review GDS with **KLayout**. This stack supports full open collaborative ASIC flows on open PDKs. Enterprise multi-site IC design data management, proprietary PDK integration, advanced IP cataloging, and vendor-supported EDA tool orchestration remain strengths of commercial platforms (Cliosoft, Methodics, Perforce, Cadence/Siemens/Altium collaboration suites, etc.).

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Chip design involves highly sensitive IP and, often, export-controlled technology. Open-source collaboration tools must be deployed with strict access control, audit logging, and compliance with applicable trade and IP regulations. Open EDA flows are powerful for learning, research, and open silicon but do not replace qualified commercial tool sign-off for many production processes.
- Always verify tool and PDK licensing for your use case.

---
**Made for hardware engineers, silicon teams, and open-source chip designers collaborating on real designs.**
Let's keep chip design collaboration as open and reproducible as the silicon ecosystem allows.
