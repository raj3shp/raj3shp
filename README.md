### Open Source Contributions

- PyCQA/bandit (Python SAST) plugin: [logging_config_insecure_listen](https://github.com/PyCQA/bandit/blob/main/bandit/plugins/logging_config_insecure_listen.py#L1)
- CIS Benchmark for Linux: [1.5.3 - Ensure ptrace_scope is restricted](https://workbench.cisecurity.org/sections/1985936/recommendations/3181744)

---

### CVEs

- [Zammad](https://zammad.com/en)
  - [CVE-2021-42086: Admin Privilege Escalation](https://zammad.com/en/advisories/zaa-2021-09)
  - [CVE-2021-42094: Command Injection](https://zammad.com/en/advisories/zaa-2021-18)
  - [CVE-2021-42091: SSRF](https://zammad.com/en/advisories/zaa-2021-08)

---

### Tools

- [bpfdoorpoc](https://github.com/raj3shp/bpfdoorpoc): PoC for bpfdoor rootkit's eBPF technique and effective detection
- [termspy](https://github.com/raj3shp/termspy): PoC terminal keylogger using ptrace
- [dns2proc](https://github.com/raj3shp/dns2proc): Script (for Linux) that correlates DNS queries with the processes that made them (wihtout eBPF)
- [ptrace_code_injection](https://github.com/raj3shp/ptrace_code_injection): PoC for injecting code into existing process with ptrace
- [python-logging.config-exploit](https://github.com/raj3shp/python-logging.config-exploit): PoC for Python's security consideration "logging: Logging configuration uses eval()"
- [chkproc.py](https://github.com/raj3shp/chkproc): PoC script to detect processes hidden by rootkits
- [vscode_trusted_rce](https://github.com/raj3shp/vscode_trusted_rce): PoC for code execution from loading a trusted project in VSCode
