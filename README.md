### Open Source Contributions

- PyCQA/bandit (Python SAST) plugin: [logging_config_insecure_listen](https://github.com/PyCQA/bandit/blob/main/bandit/plugins/logging_config_insecure_listen.py#L1)
- CIS Benchmark for Linux: [1.5.3 - Ensure ptrace_scope is restricted](https://workbench.cisecurity.org/sections/1985936/recommendations/3181744)

---

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

- [bpfdoorpoc](https://github.com/raj3shp/bpfdoorpoc): PoC for bpfdoor rootkit's eBPF technique and effective detection
- [termspy](https://github.com/raj3shp/termspy): PoC terminal keylogger using ptrace
- [dns2proc](https://github.com/raj3shp/dns2proc): Script (for Linux) that correlates DNS queries with the processes that made them (without eBPF)
- [ptrace_code_injection](https://github.com/raj3shp/ptrace_code_injection): PoC for injecting code into existing process with ptrace
- [python-logging.config-exploit](https://github.com/raj3shp/python-logging.config-exploit): PoC for Python's security consideration "logging: Logging configuration uses eval()"
- [vscode_trusted_rce](https://github.com/raj3shp/vscode_trusted_rce): PoC for code execution from loading a trusted project in VSCode
- Pace Calculator and Planner for Runners: https://pacecalculator.net/
