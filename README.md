<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0078D4,100:0f2027&height=120&text=Defender%20for%20Cloud&fontSize=44&fontColor=ffffff&desc=Cloud%20Security%20Posture%20Dashboard&descAlignY=78&descSize=16&fontAlignY=42" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Microsoft%20Defender%20for%20Cloud-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20Storage%20Account-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/area-Information%20Security-555?style=flat-square" />
  <img src="https://img.shields.io/badge/audience-Security%20leadership-555?style=flat-square" />
</p>

<p align="center"><img src="img/02.png" width="85%" alt="Security posture and controls" /></p>

## 🛡️ Overview

Built to help **Information Security leadership** make strategic decisions with **reliable, up-to-date data about cloud security**.

> 🔒 For confidentiality and information governance, some information in the report was intentionally blurred to avoid any risk of exposing sensitive data.

## 🏗️ How it works

```mermaid
flowchart LR
    A[Microsoft Defender<br/>for Cloud] --> B[(JSON file<br/>Azure Storage Account)]
    B -->|refreshed daily| C[Power BI model]
    C --> D[Security posture<br/>& controls dashboard]
    D --> E[Leadership decisions]
```

A **JSON** file stored in an **Azure Storage Account** is updated **daily** with new security data, so the dashboard refreshes automatically with the latest information — turning technical security data into strategic insights for leadership.

## 🚀 Results

| | |
|---|---|
| 🩹 **−40%** | vulnerabilities, after surfacing the high volume of required fixes |
| 🔥 **−30%** | high-severity risks after targeted remediation |
| 📈 **+20%** | overall Secure Score, adding resilience to cloud workloads |

## 📸 Dashboard gallery

<table>
  <tr>
    <td width="33%" align="center"><img src="img/01.png" /><br/><sub><b>Home</b></sub></td>
    <td width="33%" align="center"><img src="img/02.png" /><br/><sub><b>Security posture & controls</b></sub></td>
    <td width="33%" align="center"><img src="img/03.png" /><br/><sub><b>Dashboard page</b></sub></td>
  </tr>
</table>

---

<sub>🔒 Corporate project: sensitive data was blurred and this repository documents the solution only.  
👤 Part of <a href="https://github.com/MatheusFelipePereira">Matheus Felipe Pereira's portfolio</a> · <a href="https://www.linkedin.com/in/matheus-felipe-p/">LinkedIn</a> · <a href="https://matheusfp300.wixsite.com/dataanalyst">Portfolio site</a></sub>
