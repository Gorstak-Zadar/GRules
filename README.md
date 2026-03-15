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

---

## Disclaimer

**NO WARRANTY.** THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.

**Limitation of Liability.** IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS), EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
