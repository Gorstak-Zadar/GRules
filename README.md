# 📋 GRules

> PowerShell **security rules manager** — downloads and applies YARA, Sigma, Snort rules; enforces ASR (Attack Surface Reduction) rules.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🧬 **YARA** | Yara-Rules, YaraForge |
| 📊 **Sigma** | SigmaHQ detection rules |
| 🔥 **Snort** | Emerging Threats, Snort Community |
| 🛡️ **ASR** | Applies Windows Defender ASR rules from Sigma patterns |
| 📝 **Logging** | Logs to `%TEMP%\security_rules\logs` |
| ⚙️ **Config** | JSON config at `%USERPROFILE%\GRules_config.json` |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Network** | Internet for rule downloads |
| **Snort Oinkcode** | Optional for Snort Community rules |

---

## 🚀 Usage

```powershell
# Default run
.\GRules.ps1

# Start monitoring
.\GRules.ps1 -Start

# With Snort Oinkcode
.\GRules.ps1 -SnortOinkcode "your-oinkcode"

# Remove monitoring
.\GRules.ps1 -NoMonitor
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Tooling</sub>
</p>
