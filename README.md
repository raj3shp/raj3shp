# Hi, I'm Rajesh 👋

Security engineer with 10+ years of experience across detection engineering, incident response, application security and vulnerability research.

🌐 [rajeshp.com](https://www.rajeshp.com) · 💼 [LinkedIn](https://www.linkedin.com/in/rajesh0/) · 📝 [Posts](https://www.rajeshp.com/posts/) · 🛠️ [Tools](https://www.rajeshp.com/tools/)

---

## 🐞 Vulnerabilities

(discovered and reported by me)

| ID | Product | Vulnerability | Severity |
|----|---------|---------------|----------|
| [CVE-2026-46388](https://github.com/osquery/osquery/security/advisories/GHSA-fg78-9q98-62hh) | [osquery](https://github.com/osquery/osquery) | Arbitrary file read | ![Medium](https://img.shields.io/badge/-Medium-yellow) |
| [GHSA-wq25-fm54-5q3q](https://github.com/aide/aide/security/advisories/GHSA-wq25-fm54-5q3q) | [AIDE](https://github.com/aide/aide) | Detection bypass via invalid UTF-8 file names | ![Medium](https://img.shields.io/badge/-Medium-yellow) |
| [CVE-2025-54409](https://github.com/aide/aide/security/advisories/GHSA-79g7-f8rv-jcxh) | [AIDE](https://github.com/aide/aide) | NULL pointer dereference (local DoS) | ![Medium](https://img.shields.io/badge/-Medium-yellow) |
| [CVE-2025-54389](https://github.com/aide/aide/security/advisories/GHSA-522j-vvx9-gg28) | [AIDE](https://github.com/aide/aide) | Improper output neutralization (detection evasion) | ![Medium](https://img.shields.io/badge/-Medium-yellow) |
| [CVE-2021-42094](https://zammad.com/en/advisories/zaa-2021-18) | [Zammad](https://github.com/zammad/zammad) | Command injection | ![Critical](https://img.shields.io/badge/-Critical-critical) |
| [CVE-2021-42091](https://zammad.com/en/advisories/zaa-2021-08) | [Zammad](https://github.com/zammad/zammad) | Server-side request forgery (SSRF) | ![Critical](https://img.shields.io/badge/-Critical-critical) |
| [CVE-2021-42086](https://zammad.com/en/advisories/zaa-2021-09) | [Zammad](https://github.com/zammad/zammad) | Admin privilege escalation | ![High](https://img.shields.io/badge/-High-orange) |

---

## 🤝 Open Source Contributions

- **[PyCQA/bandit](https://github.com/PyCQA/bandit)** (Python SAST) — plugin: [`logging_config_insecure_listen`](https://github.com/PyCQA/bandit/blob/main/bandit/plugins/logging_config_insecure_listen.py#L1)
- **CIS Benchmark for Linux** — [1.5.3 - Ensure ptrace_scope is restricted](https://workbench.cisecurity.org/sections/1985936/recommendations/3181744)
- **Falco** (runtime security) — [security bug report](https://github.com/falcosecurity/falco/issues/3895)
- **VirusTotal YARA** — [security bug report](https://github.com/VirusTotal/yara/releases/tag/v4.5.3)
- **ClamAV** (anti-virus) — [security bug report](https://github.com/Cisco-Talos/clamav/issues/1517)
- **GTFOBins** — [`pip` abuse](https://github.com/GTFOBins/GTFOBins.github.io/commit/2e2342d4f2084f692b0f42001dd48113479ed666)
- **osquery** — [detection pack improvement](https://github.com/osquery/osquery/pull/7567)
