
**Name:** Dhruv Setty
**Role:** Security Engineer (DevSecOps / AppSec)

```mermaid
flowchart TD
    A[Security Engineering System] --> B[SIRA Programme]
    A --> C[IĀTŌ Programme]
    A --> D[Validation Artefacts]
    A --> E[Governance and Delivery]
    B --> D
    C --> D
    E --> B
    E --> C
```

---

## System Overview

```mermaid
flowchart TD
    L0[Security Engineering Portfolio System]

    L0 --> L1[SIRA: Risk Architecture Function]
    L0 --> L2[IĀTŌ: Trust Control Function]
    L0 --> L3[Validation Artefacts Layer]
    L0 --> L4[Governance / Delivery Layer]

    L3 --> V1[CVE-2021-22986: Research Execution]
    L3 --> V2[Canonical-Extension-CVE-2021-22986: Control Validation Function]

    L4 --> G1[Practice Framework Registry]
    L4 --> G2[Delivery Pipeline]
    L4 --> G3[Commercial Specification Registry]
```

---

## Programmes

### SIRA — Stochastic-Invalidation-Risk-Architecture

- **Purpose:** Maps risk governance controls to auditable validation boundaries.

```mermaid
flowchart LR
    S1[Control Crosswalk Engine] --> S2[Risk Governance Artefacts]
    S2 --> S3[Evidence Gap Register]
    S3 --> S4[Remediation Obligation Set]
```

- **Linked repositories:**
  - [`Stochastic-Invalidation-Risk-Architecture`](https://github.com/whatheheckisthis/Stochastic-Invalidation-Risk-Architecture)
- **Control frameworks referenced:**
  - ISM Application Control
  - ASD Essential Eight ML3
  - SOC 2 CC7.2
  - ISO/IEC 27001

### IĀTŌ — Intent-to-Auditable-Trust-Object

- **Purpose:** Enforces privileged-access elimination and auditable container execution semantics.

```mermaid
flowchart LR
    I1[Rootless Isolation Control] --> I2[Enumerated Command Harness]
    I2 --> I3[MCP Audit Record Stream]
    I3 --> I4[Append-only Session Evidence]
```

- **Linked repositories:**
  - [`Intent-to-Auditable-Trust-Object-Index`](https://github.com/whatheheckisthis/Intent-to-Auditable-Trust-Object-Index)
- **Control frameworks referenced:**
  - ISM Application Control
  - ASD Essential Eight ML3
  - SOC 2 CC7.2
  - ISO/IEC 27001

---

## Validation Artefacts 

### CVE Validation Subsystem

```mermaid
flowchart LR
    VA[Validation Artefacts Layer]
    VA --> CVE1[CVE-2021-22986\ncontrol validation function]
    VA --> CVE2[Canonical-Extension-CVE-2021-22986\ncontrol validation function]
```

- [`CVE-2021-22986`](https://github.com/whatheheckisthis/CVE-2021-22986)
- [`Canonical-Extension-CVE-2021-22986`](https://github.com/whatheheckisthis/Canonical-Extension-CVE-2021-22986)

```mermaid
flowchart LR
    SIRA[SIRA] --> IATO[IĀTŌ]
    IATO --> CVE[CVE Validation Systems]
    CVE --> EVIDENCE[Validation Artefact Evidence]
```

---

## Practice Framework

| Registry Item | Source | Governance Mapping |
|---|---|---|
| ETHOS.md | [`docs/ETHOS.md`](https://github.com/whatheheckisthis/Stochastic-Invalidation-Risk-Architecture/blob/main/docs/ETHOS.md) | Architecture philosophy and stack governance |
| DELIVERY.md | [`docs/DELIVERY.md`](https://github.com/whatheheckisthis/Stochastic-Invalidation-Risk-Architecture/blob/main/docs/DELIVERY.md) | Engagement execution model and GRC control mapping |

---

## Delivery Model 

```mermaid
flowchart LR
    D1[Discovery] --> D2[Control Mapping] --> D3[Gap Register] --> D4[Implementation] --> D5[Evidence] --> D6[Handover]
```

---

## Controls Taxonomy 

```mermaid
classDiagram
    class Auditability {
        CTRL-AUD-01
        CTRL-AUD-02
        CTRL-AUD-03
    }
    class Observability {
        CTRL-OBS-01
        CTRL-OBS-02
        CTRL-OBS-03
    }
    class Continuous_Monitoring {
        CTRL-CON-01
        CTRL-CON-02
        CTRL-CON-03
    }
    class Governance {
        CTRL-GOV-01
        CTRL-GOV-02
        CTRL-GOV-03
    }
```

| Control Group | Control IDs | Mapping Context |
|---|---|---|
| Auditability | CTRL-AUD-01 · CTRL-AUD-02 · CTRL-AUD-03 | ISM · SOC 2 · ASD Essential Eight ML3 |
| Observability | CTRL-OBS-01 · CTRL-OBS-02 · CTRL-OBS-03 | ISM · SOC 2 · ASD Essential Eight ML3 |
| Continuous Monitoring | CTRL-CON-01 · CTRL-CON-02 · CTRL-CON-03 | ISM · SOC 2 · ASD Essential Eight ML3 |
| Governance | CTRL-GOV-01 · CTRL-GOV-02 · CTRL-GOV-03 | ISM · SOC 2 · ASD Essential Eight ML3 |

---

## Commercial Model

| Parameter | Specification |
|---|---|
| Day rate | Market-aligned contractor rate (DevSecOps / GRC uplift scope) |
| Engagement model | Fixed-term DevSecOps uplift (typically 100–120 days) |
| Delivery cadence | Capacity-based engagements (~2 per annum) |
| Billing terms | Milestone-based or fortnightly · Net 14 |
| Engagement channels | Specialist recruiters · direct referrals · GitHub |

---

`E8 ML3` · `ISM` · `IRAP` · `DISP` · `APRA CPS 220`

**Engagement enquiries:** Direct recruiter engagement preferred.

```text
itsdhruvsetty@gmail.com
```
