# Hi, I'm **SHawn** 👋

## 숀 생태계 (SHawn) — GitHub 대표 지도

<p align="center">
  <a href="https://github.com/L-SHawn91?tab=followers"><img src="https://img.shields.io/github/followers/L-SHawn91?style=flat-square" /></a>
  <a href="https://github.com/L-SHawn91?tab=repositories"><img src="https://img.shields.io/github/stars/L-SHawn91?style=flat-square" /></a>
  <img src="https://img.shields.io/badge/Role-Research%20Ops%20%2B%20Creator%20Tooling-6f42c1?style=flat-square" />
</p>

```mermaid
flowchart LR
    root["SHawn Umbrella"] --> personal["SH: Personal layer"]
    root --> research["SHio: Bio/Research layer"]
    root --> side["SHide: Content & Growth layer"]

    personal --> p1["SH-sync\n(personal control plane)"]
    personal --> p2["Private workspaces\n(real-estate, investment, career)"]

    research --> r1["SHawn-paper-assist\n(private)"]
    research --> r2["SHawn-paper-mapping\n(private)"]
    research --> r3["SHawn-academic-research\n(private)"]
    research --> r4["SHio private stack"]

    side --> s1["SHide-IG\n(private)"]
    side --> s2["SHide-YT\n(private)"]
    side --> s3["SHide-BLOG\n(private)"]

    root --> open["Public OSS Surface"]
    open --> o1["SHawn-EvidenceMap"]
    open --> o2["SHawn-hwp"]
    open --> o3["SHawn-WEB"]
    open --> o4["newbrain-router"]
    open --> o5["shawn-docx-qa"]
    open --> o6["paper-map-lite"]
    open --> o7["shawn-sync-lite"]
    open --> o8["shawn-bio-search-lite"]
```

### Public repos

- **Research / Knowledge Infra**
  - [SHawn-EvidenceMap](https://github.com/L-SHawn91/SHawn-EvidenceMap)
  - [paper-map-lite](https://github.com/L-SHawn91/paper-map-lite)
  - [shawn-bio-search-lite](https://github.com/L-SHawn91/shawn-bio-search-lite)
- **Document QA / Automation**
  - [SHawn-hwp](https://github.com/L-SHawn91/SHawn-hwp)
  - [shawn-docx-qa](https://github.com/L-SHawn91/shawn-docx-qa)
- **Tools / Router / Orchestration**
  - [newbrain-router](https://github.com/L-SHawn91/newbrain-router)
  - [shawn-sync-lite](https://github.com/L-SHawn91/shawn-sync-lite)
- **Web / Service**
  - [SHawn-WEB](https://github.com/L-SHawn91/SHawn-WEB)

### Quick Links

- 🔬 [EvidenceMap Demo](https://l-shawn91.github.io/SHawn-EvidenceMap/)
- 🌐 [SHawn-WEB](https://shawnlab.vercel.app)
- 📬 더 자세한 제어면: `SH-sync`, `SHio-sync`, `SHide-sync` (private)

### Focus Areas

- **오픈소스 배포**: 연구·문서 QA·오케스트레이션 엔진의 공개 컴포넌트 정리
- **생태계 경계 정책 준수**: SH / SHio / SHide의 private/public 경계 유지
- **실험 자동화 친화적 구조**: 공통 실행 규약, 모듈형 연결, 문서화 우선

### Visual Principles

- **Layered by domain** (SH / SHio / SHide)
- **Public-safe + private-first design**
- **Reproducible tooling** for document QA and evidence workflows
- **No leakage** of private-layer state

---

<p align="center"><sub>Public profile surface only. Internal layer state is maintained in control-plane repos.</sub></p>
