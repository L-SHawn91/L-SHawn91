# Hi, I'm **SHawn** 👋

## 숀 생태계 (SHawn) GitHub 대표 지도

<div align="center">
  <img src="https://img.shields.io/badge/Status-Private%2BPublic%20Hybrid-6f42c1?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Research%20Ops%20%2B%20Automation-0ea5e9?style=flat-square" />
  <img src="https://img.shields.io/badge/Layer-ecosystem%20architecture-22c55e?style=flat-square" />
  <br/>
  <img src="https://img.shields.io/github/followers/L-SHawn91?style=social" />
  <img src="https://img.shields.io/github/stars/L-SHawn91?style=flat-square" />
</div>

![SHawn Ecosystem Hero](./shawn-ecosystem-hero.svg)

> **목표**: 공개 가능한 범위에서 SHawn 생태계의 계층, 경계, 공개 산출물을 한눈에 보여주는 프로필 카드.

---

```mermaid
flowchart LR
    U[SHawn\nUmbrella]
    U --> P[SH: 개인/실행 레이어]
    U --> R[SHio: 연구 레이어]
    U --> S[SHide: 콘텐츠·성장 레이어]

    P --> P1[SH-sync\ncontrol plane]
    P --> P2[라이프/투자/커리어\nprivate workspaces]

    R --> R1[paper-assist\n(private)]
    R --> R2[paper-mapping\n(private)]
    R --> R3[academic-research\n(private)]

    S --> S1[SHide-IG\n(private)]
    S --> S2[SHide-YT\n(private)]
    S --> S3[SHide-BLOG\n(private)]

    U --> O[Public OSS Surface]
    O --> O1[SHawn-EvidenceMap]
    O --> O2[SHawn-hwp]
    O --> O3[SHawn-WEB]
    O --> O4[newbrain-router]
    O --> O5[shawn-docx-qa]
    O --> O6[paper-map-lite]
    O --> O7[shawn-sync-lite]
    O --> O8[shawn-bio-search-lite]

    classDef umbrella fill:#1f2937,stroke:#60a5fa,color:#f9fafb,stroke-width:2px;
    classDef layer fill:#111827,stroke:#34d399,color:#e5e7eb,stroke-width:1.6px;
    classDef private fill:#0f172a,stroke:#a78bfa,color:#f8fafc,stroke-dasharray:3 3;
    classDef public fill:#0f172a,stroke:#fde68a,color:#fffbeb;
    class U fill:#334155,stroke:#60a5fa,color:#f8fafc,stroke-width:2px;
    class P,R,S layer;
    class P1,P2,R1,R2,R3,S1,S2,S3 private;
    class O,O1,O2,O3,O4,O5,O6,O7,O8 public;
```

### Public repositories

#### Research / Knowledge Infra
- [SHawn-EvidenceMap](https://github.com/L-SHawn91/SHawn-EvidenceMap)
- [paper-map-lite](https://github.com/L-SHawn91/paper-map-lite)
- [shawn-bio-search-lite](https://github.com/L-SHawn91/shawn-bio-search-lite)

#### Document QA / Automation
- [SHawn-hwp](https://github.com/L-SHawn91/SHawn-hwp)
- [shawn-docx-qa](https://github.com/L-SHawn91/shawn-docx-qa)

#### Tools / Router / Orchestration
- [newbrain-router](https://github.com/L-SHawn91/newbrain-router)
- [shawn-sync-lite](https://github.com/L-SHawn91/shawn-sync-lite)

#### Web / Service
- [SHawn-WEB](https://github.com/L-SHawn91/SHawn-WEB)

### Quick links

- 🔬 [EvidenceMap Demo](https://l-shawn91.github.io/SHawn-EvidenceMap/)
- 🌐 [SHawn-WEB](https://shawnlab.vercel.app)
- 📬 제어면(개인/연구/사이드): `SH-sync`, `SHio-sync`, `SHide-sync`

### Why this profile

- **Private-first boundary**: SH / SHio / SHide 분리 원칙을 유지하면서 공개 레이어만 노출
- **Reusable infrastructure**: 연구 증거맵, 문서 QA, 오케스트레이션 파이프를 공개 모듈화
- **Low-leakage design**: 내부 운영 정보는 프로필 외부로 노출하지 않음

---

<p align="center"><sub>Public profile surface only. Internal layer state is maintained in SHawn control-plane repos.</sub></p>
