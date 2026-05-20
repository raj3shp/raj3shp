### Vulnerability Findings

|CVE ID|Project|Description|
|------|-------|-----------|
|[CVE-2025-54409](https://github.com/aide/aide/security/advisories/GHSA-79g7-f8rv-jcxh)|[AIDE](https://github.com/aide)|NULL pointer dereference leading to DoS|
|[CVE-2025-54389](https://github.com/aide/aide/security/advisories/GHSA-522j-vvx9-gg28)|[AIDE](https://github.com/aide)|Improper output neutralization (detection bypass)|
|[CVE-2021-42086](https://zammad.com/en/advisories/zaa-2021-09)|[Zammad](https://github.com/zammad/zammad)|Privilege Escalation to admin|
|[CVE-2021-42094](https://zammad.com/en/advisories/zaa-2021-18)|[Zammad](https://github.com/zammad/zammad)|Command Injection via Package installation|
|[CVE-2021-42091](https://zammad.com/en/advisories/zaa-2021-08)|[Zammad](https://github.com/zammad/zammad)|Server side request forgery|


---

### Tools
|Name|Description|
|----|-----------|
|[persisthunt](https://github.com/raj3shp/persisthunt)|A lightweight Linux persistence hunting & artifact collection script|
|[bpfdoorpoc](https://github.com/raj3shp/bpfdoorpoc)|PoC for bpfdoor rootkit's eBPF technique and effective detection|
|[termspy](https://github.com/raj3shp/termspy)|PoC terminal keylogger using ptrace|
|[dns2proc](https://github.com/raj3shp/dns2proc)|Bash script to correlate DNS queries with the processes that made them |
|[ptrace_code_injection](https://github.com/raj3shp/ptrace_code_injection)| PoC for injecting code into existing process with ptrace|
--- 

### Open Source Contributions

- PyCQA/bandit (Python SAST) plugin: [logging_config_insecure_listen](https://github.com/PyCQA/bandit/blob/main/bandit/plugins/logging_config_insecure_listen.py#L1)
- CIS Benchmark for Linux: [1.5.3 - Ensure ptrace_scope is restricted](https://workbench.cisecurity.org/sections/1985936/recommendations/3181744)
- Minor improvements
   - VirusTotal YARA: [security bug report](https://github.com/VirusTotal/yara/releases/tag/v4.5.3)
   - Clam Anti-Virus: [security bug report](https://github.com/Cisco-Talos/clamav/issues/1517)
   - GTFOBins : [pip abuse](https://github.com/GTFOBins/GTFOBins.github.io/commit/2e2342d4f2084f692b0f42001dd48113479ed666)
   - Osquery: [detection pack improvement](https://github.com/osquery/osquery/pull/7567)

---
