# 🚨 incident-response-toolkit

A hands-on, scriptable, and documentation-driven incident response toolkit built for SOC analysts, blue teamers, and security engineers. This repo provides templates, playbooks, collection scripts, and checklists to streamline the investigation and containment of security incidents.

## 🎯 Goals

- Standardize how to respond to common incidents
- Speed up triage with scripted tools
- Provide a paper trail for evidence handling and reporting
- Practice IR fundamentals in a repeatable, structured way

## 📁 What's Inside

| Folder              | Purpose                                                       |
|---------------------|---------------------------------------------------------------|
| `playbooks/`         | Step-by-step guides for malware, access abuse, phishing, etc. |
| `triage-scripts/`    | IR collection tools for Linux, Windows, and cross-platform    |
| `timelines/`         | CSV templates and how-tos for timeline building               |
| `evidence-handling/` | Checklists, chain-of-custody docs, volatile capture notes     |
| `containment-guides/`| How to isolate systems, rotate creds, and block connections   |
| `reporting/`         | Templates for exec summaries, incident logs, and retros       |
| `docs/`              | IR process references, frameworks, and tooling links          |

## 🧠 Example Scenarios Covered

- Malware on endpoint (Win/Linux)
- Unauthorized remote access
- Internal phishing compromise
- Suspicious cloud IAM or API use
- Data exfiltration indicators

## 🔧 Example Scripts

- `linux-ir-collection.sh`: Collects running processes, users, netstat, bash history
- `windows-artifact-dump.ps1`: Grabs autoruns, event logs, volatile memory handles
- `suspicious-process-check.py`: Looks for LOLBins and process name mismatches

## 📚 Framework Alignment

This repo follows incident response principles from:

- 🏛️ NIST SP 800-61 (Computer Security Incident Handling Guide)
- 🧩 MITRE ATT&CK (for mapping behaviors and techniques)

See [`docs/NIST-IR-mapping.md`](docs/NIST-IR-mapping.md) for alignment notes.

## ✅ Use Cases

- IR dry runs and simulations
- SOC analyst playbook creation
- Home lab or CTF incident practice
- Template library for internal IR teams

## 🔐 Disclaimer

This repo does not contain real incident data. Scripts and templates are written for educational, simulation, and homelab use only.

