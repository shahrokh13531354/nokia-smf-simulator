# nokia-smf-simulator
# Nokia CMG — SMF CLI Simulator v2

An interactive, browser-based CLI simulator for the Nokia Cloud Mobile Gateway 
(CMG) Session Management Function (SMF), built from Nokia's official 
technical documentation (Release 24.7.R1).

**Live Demo:** https://YOUR_USERNAME.github.io/nokia-smf-simulator/

## Features

- **Full MD-CLI terminal** with command history and realistic Nokia output
- **SMF Integration MOP** — 21-step walkthrough (ssh → commit → verify)
- **ISSU / Upgrade MOP** — inter-CNF, intra-CNF, and cmg-operator procedures
- **Canary Testing MOP** — full canary lifecycle with kubectl/helm commands
- **SBI Flows tab** — Nsmf_PDUSession, NRF registration, PFCP N4 flows
- **Live Stats dashboard** — SMF, PFCP, NRF, DB sync, call flow metrics
- **Verification Checklist** — pre-integration through post-ISSU
- **60+ CLI commands** simulated with authentic Nokia output format

## Commands Covered

- SMF instance, NRF registration, PFCP association, Sx/N4
- PDU session, call-flow-stats, pdn-context, DNN overload control
- PFCP load/overload control, DB sync (cdbx), PFCP-u sessions
- System, card states, multi-chassis redundancy (ICR)
- ISSU: kubectl, helm, cmg-operator CR, DB-ISSU, LOAM/LMG upgrade
- Canary testing: resource pools, canary groups, session drain
- Call trace, PCAP, PCMD, log analysis

## Documentation Sources

| Document | Description |
|---|---|
| DN1000133964 | CMG Service-Based Interfaces Guide |
| DN1000167910 | 7750 SR MG and CMG Software Upgrade Guide |
| DN1000134064 | CP and User Plane Configuration Guide |
| DN1000159890 | MD-CLI User Guide |
| DN1000133953 | CMG-a Installation and System Management Guide |
| DN1000134053 | CMG Configuration Guide |

## Technologies

Pure HTML/CSS/JavaScript — no dependencies, no build step, runs entirely 
in the browser.

## Author

**Shahrokh Omalie** — Senior Telecom Consultant (Nokia CMG, EPC, IMS, 5G Core)  
[LinkedIn](https://linkedin.com/in/YOUR_PROFILE) | 
[GitHub](https://github.com/YOUR_USERNAME)
