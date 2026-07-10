# SHawn Ecosystem Profile

<p align="center">
  <img src="./shawn-ecosystem-hero.svg" alt="SHawn Ecosystem Premium Banner" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Mode-Public%20Open-0f172a?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-Research%20Ops%20%26%20Automation-0ea5e9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Design-Premium%20Dark%20System-7c3aed?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/L-SHawn91?style=flat-square&label=Followers" />
  <img src="https://img.shields.io/github/stars/L-SHawn91?style=flat-square&label=Stars" />
  <img src="https://img.shields.io/github/repo-size/L-SHawn91/L-SHawn91?style=flat-square" />
</p>

<p align="center">
  <i>공개 가능한 레포만 보여주는 SHawn 생태계 아키텍처 카드</i>
</p>

---

## 01. 시스템 맵

```mermaid
flowchart TB
    A["SHawn Ecosystem\nUmbrella"]

    A --> B["SH\nPersonal Operations"]
    A --> C["SHio\nResearch"]
    A --> D["SHide\nContent Growth"]

    B --> B1["Public interface to private ops"]
    B --> B2["Personal workflow policy"]

    C --> C1["paper-assist"]
    C --> C2["paper-mapping"]
    C --> C3["academic-research"]

    D --> D1["SHide-IG"]
    D --> D2["SHide-YT"]
    D --> D3["SHide-BLOG"]

    A --> O["Public OSS Surface"]
    O --> O1["SHawn-EvidenceMap"]
    O --> O2["SHawn-hwp"]
    O --> O3["SHawn-WEB"]
    O --> O4["newbrain-router"]
    O --> O5["shawn-docx-qa"]
    O --> O6["paper-map-lite"]
    O --> O7["shawn-sync-lite"]
    O --> O8["shawn-bio-search-lite"]

    classDef core fill:#0f172a,stroke:#60a5fa,color:#f8fafc,stroke-width:2.5px;
    classDef layer fill:#111827,stroke:#34d399,color:#e2e8f0,stroke-width:1.6px;
    classDef public fill:#111827,stroke:#fde047,color:#fef3c7,stroke-width:1.4px;

    class A core
    class B,C,D layer
    class B1,B2,C1,C2,C3,D1,D2,D3,O,O1,O2,O3,O4,O5,O6,O7,O8 public
```

---

## 02. 공개 레포

### Research / Knowledge Infrastructure
- [SHawn-EvidenceMap](https://github.com/L-SHawn91/SHawn-EvidenceMap)
- [paper-map-lite](https://github.com/L-SHawn91/paper-map-lite)
- [shawn-bio-search-lite](https://github.com/L-SHawn91/shawn-bio-search-lite)

### Document QA & Automation
- [SHawn-hwp](https://github.com/L-SHawn91/SHawn-hwp)
- [shawn-docx-qa](https://github.com/L-SHawn91/shawn-docx-qa)

### Router / Orchestration Layer
- [newbrain-router](https://github.com/L-SHawn91/newbrain-router)
- [shawn-sync-lite](https://github.com/L-SHawn91/shawn-sync-lite)

### Service
- [SHawn-WEB](https://github.com/L-SHawn91/SHawn-WEB)

---

## 03. 운영 철학

- **Public-safe boundary**: 공개 레포와 내부 운영을 분리해 외부 노출 경로를 최소화.
- **Composable design**: 공개 레이어는 독립 모듈처럼 연결.
- **Evidence-ready structure**: 산출물과 규약을 한눈에 연결 가능한 구조로 정리.

---

## 04. Quick Links

- [🔬 EvidenceMap Demo](https://l-shawn91.github.io/SHawn-EvidenceMap/)
- [🌐 SHawn-WEB](https://shawnlab.vercel.app)

<p align="center"><sub>Public repositories only.</sub></p>
