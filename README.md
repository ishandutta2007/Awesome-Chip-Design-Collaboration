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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Altium 365](https://www.altium.com/altium-365)**  
  Cloud collaboration platform for PCB and electronics design — shared workspaces, version control, review, and supply-chain data tightly integrated with Altium Designer.

- **[Cadence Cloud](https://www.cadence.com/)**  
  Cloud and collaboration offerings around Cadence EDA tools for design, verification, and team productivity in IC and system design.

- **[Siemens Teamcenter EDA](https://www.siemens.com/)**  
  Design data management and PLM capabilities for electronics and EDA within the broader Siemens Teamcenter ecosystem.

- **[GitLab](https://about.gitlab.com/)**  
  Widely used DevOps platform (SaaS and self-managed) adopted by many hardware teams for RTL, scripts, and infrastructure-as-code collaboration with CI.

- **[Perforce Helix Core](https://www.perforce.com/products/helix-core)**  
  High-performance version control frequently chosen for large binary and design-data assets in semiconductor and complex engineering environments.

- **[Aldec HES-DVM](https://www.aldec.com/)**  
  Hardware emulation and prototyping solutions with collaboration and debug capabilities for SoC verification teams.

- **[DesignSync](https://www.cadence.com/)**  
  Design data management solution (historically associated with Cadence/Methodics lineage) for tracking IC design files and configurations.

- **[Methodics IPLM](https://www.methodics-eda.com/)**  
  IP lifecycle management platform focused on semiconductor IP tracking, reuse, and design data governance.

- **[Cliosoft SOS](https://www.cliosoft.com/)**  
  Design data management and version control system purpose-built for hardware and IC design teams.

- **[OpenLane Cloud / related open-flow hosting](https://github.com/The-OpenROAD-Project)**  
  Cloud or hosted offerings that package open RTL-to-GDS flows (OpenLane/OpenROAD ecosystem) for collaborative tapeout-oriented design.

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
