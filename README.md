<!-- Header -->
<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   █▀▄ ▄▀█ ▀█ █▄░█   •   Security Engineering               ║
║   █▄▀ █▀█ █▄ █░▀█   •   Detection & Response                ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=500&lines=Bhuvanesh+Hingal;Security+Engineer+%40+DAZN;Detection+%7C+Response+%7C+Protect" alt="Typing SVG" />
</div>

---

<div align="justify">

```kusto
// threat_hunter.kql
SecurityAlert
| where TimeGenerated > ago(24h)
| where Engineer == "Bhuvanesh.Hingal"
| summarize ThreatsMitigated=count() by Category
| order by ThreatsMitigated desc
```

</div>

---

### `> cat role.json`

```json
{
  "team": "Security Operations",
  "organisation": "DAZN",
  "brands_protected": ["DAZN", "Foxtel"],
  "mission": "Protect the platforms that millions of fans depend on.",
  "scope": [
    "Insider Risk Investigations",
    "Detection Engineering",
    "Threat Hunting",
    "Incident Response",
    "Data Loss Prevention",
    "Cloud & Application Security"
  ]
}
```

---

### `> ls capabilities/`

<div align="center">

| Domain | Focus |
|--------|-------|
| 🔍 **Threat Hunting** | Proactive sweeps across endpoint, identity, cloud & SaaS telemetry |
| 🛡️ **Detection Engineering** | KQL analytics rules, custom detections, MITRE ATT&CK mapping |
| 🚨 **Incident Response** | Phishing, malware, compromise, cloud & data protection incidents |
| 🕵️ **Insider Risk** | Behavioural analysis, anomaly detection, end-to-end investigations |
| 🔐 **DLP** | Policy enforcement, violation investigations, business impact assessment |
| ☁️ **Cloud Security** | WAF administration, exposure management, risk remediation |
| 🌐 **Network Analysis** | JA4 fingerprinting, traffic pattern investigation, C2 detection |
| 📋 **Governance** | ISO 27001 aligned controls, playbooks, runbooks, automation |

</div>

---

### `> echo $TOOLKIT`

<div align="center">

![KQL](https://img.shields.io/badge/KQL-0078D4?style=flat-square&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/Sentinel-0078D4?style=flat-square&logoColor=white)
![Microsoft Defender](https://img.shields.io/badge/Defender-0078D4?style=flat-square&logoColor=white)
![Microsoft Purview](https://img.shields.io/badge/Purview-0078D4?style=flat-square&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

### `> cat /var/log/recent_focus.log`

```
[ACTIVE] Insider Risk detection engineering & investigation automation
[ACTIVE] JA4 fingerprint analysis for anomalous network behaviour
[ACTIVE] Security playbook & runbook development for SOC consistency
[ACTIVE] Cloud security posture assessment & remediation prioritisation
[ACTIVE] WAF policy engineering & web application protection
```
---

### `> git log --oneline contributions/`

<div align="center">
  <img src="https://raw.githubusercontent.com/Bhuvanesh-DAZN/Bhuvanesh-DAZN/output/profile-night-green.svg" width="90%" />
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Bhuvanesh-DAZN&style=flat-square&color=0078D4&labelColor=0d1117&label=views" />
</div>

---

<div align="center">

```
$ logout
Connection to dazn-secops closed.
Session logged. Alerts monitored. Threats hunted.
```

</div>


---