# CentOS7 CIS Hardening Framework

This repo contains bash scripts which performs tests against your CentOS system to give an indication of whether the running server may compliy with the CIS v2.2.0 Benchmarks for CentOS, this repo also contains bash scripts which performs hardening process to you CentOS systems, hopefully the scripts can make your system may compliy with CIS v2.2.0.

## How to Use

### Auditor / Benchmark Script

#### finalduty Benchmark

```bash
    # escalate script so it can be executed
    chmod 750 auditor/finalduty/cis-audit.sh
    sudo ./auditor/finalduty/cis-audit.sh

    #help
    ./auditor/finalduty/cis-audit.sh --help
```

#### massyn

```bash
    chmod 750 auditor/massyn/run-cis-benchmark.sh
    sudo bash auditor/massyn/run-cis-benchmark.sh
```
### Hardening Script

#### naingyeminn

```bash
    chmod 750 ./hardener/naingyeminn/centos7.sh
    sudo ./hardener/naingyeminn/centos7.sh
```

## Disclaimer

This repo contains submodules from another repository, this repo just a curated place for auditing and hardening your CentOS system to match CIS standard easily.

for more information about the submodules, you should check the README.md of each script listed in the submodules.

- [finalduty](https://github.com/finalduty) / [cis_benchmarks_audit](https://github.com/finalduty/cis_benchmarks_audit) 
- [massyn](https://github.com/massyn)  / [centos-cis-benchmark](https://github.com/massyn/centos-cis-benchmark) 
- [naingyeminn](https://github.com/naingyeminn) / [CentOS7_Lockdown](https://github.com/naingyeminn/CentOS7_Lockdown) 

Don't forget to give thanks & supports to them!
