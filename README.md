# 🛡️ Windows DISA STIG Remediation

![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-blue)
![DISA STIG](https://img.shields.io/badge/DISA-STIG%20Compliant-green)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20%7C%20Server-lightgrey)

Welcome! 👋  
This repository contains **PowerShell scripts** designed to **remediate Windows virtual machines** to meet **DISA STIG compliance** requirements.

---

## 🎯 Purpose
- Automate **STIG remediation**
- Reduce **manual hardening errors**
- Support **auditing & compliance validation**
- Designed for **Windows VMs** (Azure / on-prem / lab environments)

---

## 📂 What You’ll Find
- ✅ Individual STIG remediation scripts
- 🧪 Easy verification steps
- 📘 STIG IDs referenced in each script

---

## ⚠️ Important Notes
- Run scripts **as Administrator**
- Always **test in a non-production environment**
- Review STIG applicability before deployment

---

## 📊 PowerShell Scripts

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Compliance](https://img.shields.io/badge/Compliance-DISA%20STIG-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%2011-lightgrey)

### 🛡️ Implemented STIGs
| STIG ID        | Title                                      | Severity | Status |
|---------------|--------------------------------------------|----------|--------|
| [WN11-AU-000500](https://github.com/marcopsd-dev/policy_complaince/blob/main/STIGS/WN11-AU-000500) | Application Event Log Size                 | Medium   | ✅ Implemented |
| [WN11-CC-000110](https://github.com/marcopsd-dev/policy_complaince/blob/main/STIGS/WN11-CC-000110) | Printing over HTTP must be prevented       | Medium   | ✅ Implemented |
| [WN11-CC-000252](https://github.com/marcopsd-dev/policy_complaince/blob/main/STIGS/WN11-CC-000252) | Disables Windows Game Recording and Broadcasting.| Low   | ✅ Implemented |
| [WN11-CC-000280](https://github.com/marcopsd-dev/policy_complaince/blob/main/STIGS/WN11-CC-000280) |Remote Desktop Services prompt passwords upon connection.| Medium   | ✅ Implemented |
| [WN11-CC-000310](https://github.com/marcopsd-dev/policy_complaince/blob/main/STIGS/WN11-CC-000310) | Prevents users from changing Windows Installer installation options.       | Medium   | ✅ Implemented |
| [WN11-CC-000315](https://github.com/marcopsd-dev/policy_complaince/blob/main/STIGS/WN11-CC-000315) | The Windows Installer feature elevated privileges must be disabled.| HIGH   | ✅ Implemented |
