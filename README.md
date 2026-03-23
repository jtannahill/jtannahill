<h1 align="center">James Tannahill</h1>

<p align="center">
  <strong>PE Executive & Founder</strong> — New York City<br/>
  <em>Building production systems at the intersection of finance, healthcare, and AI</em>
</p>

<p align="center">
  <a href="https://www.jamestannahill.com">jamestannahill.com</a> ·
  <a href="https://www.linkedin.com/in/jamesstannahill/">LinkedIn</a> ·
  <a href="https://plocamium.com">Plocamium Holdings</a> ·
  <a href="https://www.bloomberg.com/profile/person/23291921">Bloomberg</a> ·
  <a href="https://hmuapi.com">HMU API</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS_CDK-232F3E?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Bedrock-FF9900?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Step_Functions-FF4F8B?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/SageMaker-7B68EE?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white" />
  <img src="https://img.shields.io/badge/SvelteKit-FF3E00?style=flat&logo=svelte&logoColor=white" />
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/D3.js-F9A03C?style=flat&logo=d3dotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Mapbox-000000?style=flat&logo=mapbox&logoColor=white" />
  <img src="https://img.shields.io/badge/LiveKit-000000?style=flat&logo=webrtc&logoColor=white" />
</p>

---

### Why I Build

I run a private equity firm. I also write code every day.

That isn't a contradiction — it's the thesis. The best investment judgment comes from understanding what technology can actually do, not what a pitch deck says it can do. Every tool here started as a real problem: an inbox that couldn't scale, a phone that couldn't triage, a portfolio that couldn't value itself, a content pipeline that couldn't keep up.

I build because operators who ship their own tools make better decisions than those who delegate to committees. And because the gap between "technically possible" and "actually deployed" is where most value gets destroyed.

---

### Ventures

| | |
|---|---|
| **[Plocamium Holdings](https://plocamium.com)** | Private equity and operational advisory — $900+ MM AUM, 100+ investments |
| **[1ness Strategies](https://1nessagency.com)** | Compliance-focused digital marketing for healthcare and regulated sectors |
| **[HLTHvrs](https://hlthvrs.com)** | Marketing intelligence platform for behavioral health |
| **[NewYorkLab](https://newyorklab.co)** | Environmental intelligence for urban climate risk |
| **[MonkeyThorn](https://monkeythorn.com)** | Privacy-first communications infrastructure (Meet, NatashAI) |

---

### What I Build

#### Intelligence & ML

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**Plocamium Content Engine**](https://github.com/jtannahill/plocamium-content-engine) | AI content pipeline + intelligence platform. 3 news sources, 151 RSS feeds / 12 lanes, OpenSearch RAG, 14 post types, brand-aware covers, Polly audio. **ML**: momentum scorer, sector clustering, cross-cluster triggers. **Plocamium Signal Index (PSI)**: daily composite z-score measuring narrative disruption — 5 orthogonal signals, Kalman-smoothed, regime-aware (BOCPD). **Entity Intelligence Cards** with 5 proprietary metrics embedded in articles. **Entity watchlists** with 4 alert triggers + daily SES digest. **[Global Intelligence Network](https://plocamium.com/globals/intelligence)**: BICS-classified entity graph, D3.js visualization, PDF export | `Step Functions` `Lambda` `Bedrock` `OpenSearch` `SES` `Polly` `Comprehend` `D3.js` `CloudFront` `Kalman Filter` `Isolation Forest` `Titan Embeddings` |
| [**Argus**](https://github.com/jtannahill/argus) | Building intelligence for NYC — point your phone at any building for ownership, value, violations, air rights, diplomatic status. GPS + 3D ray casting with LiDAR heights, CLIP visual matching (20K embeddings), Bedrock AI narratives, 8 NYC public data APIs | `Swift 6` `CDK` `Lambda` `DynamoDB` `SageMaker (CLIP)` `Bedrock` `Step Functions` `Mapbox` `Cognito` |
| **Aletheia** | OSINT intelligence — entity enrichment from 11+ sources, sanctions/PEP screening, graph visualization, geofencing, AI briefs | `CDK` `Lambda` `DynamoDB` `Step Functions` `SvelteKit` `Mapbox` `Cytoscape.js` |
| **Email Intel** | Email header analysis + org infrastructure profiling. 147 orgs profiled, rules-based change classifier (positive/negative/neutral), web dashboard | `Python` `Click` `Jinja2` |
| [**DomainIQ**](https://d17ia582bwv8z0.cloudfront.net) | Domain portfolio intelligence — SageMaker XGBoost valuation model, AI appraisals, weighted forecasting, rule-based renewal engine for 307+ domains | `SvelteKit` `Tailwind` `CDK` `Lambda` `DynamoDB` `SageMaker` `Bedrock` |
| **LeadFlow** | Real estate lead intelligence — county records, skip trace enrichment, AI scoring, weekly delivery for South Florida agents | `CDK` `Lambda` `DynamoDB` `ECS Fargate` `Playwright` `SQS` `Bedrock` |

#### Creative & Generative

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**Art Generator**](https://art.jamestannahill.com) | Daily generative art from live atmospheric data — 50 global weather stations, 11 artist styles, 249+ artworks, satellite color palettes from Copernicus Sentinel-2. ML art critic, weather forecaster, dynamic pricing. Newsletter, print shop, RSS syndication | `CDK` `Step Functions` `Lambda` `Bedrock` `Open-Meteo` `Sentinel Hub` `Resend` `S3` `CloudFront` |
| [**FX30 Pipeline**](https://media.jamestannahill.com/browse/) | Live streaming + recording — IVS broadcast, MediaConvert transcoding, Transcribe + Bedrock analysis, media gallery with download/embed | `Lambda` `IVS` `MediaConvert` `Transcribe` `Bedrock` `CloudFront` |

#### Communications & Platforms

| Project | What It Does | Stack |
|---------|-------------|-------|
| **NatashAI** | Streaming voice AI phone assistant — manages calendar, email, and Zoom via real-time conversation. 30 tools, 14 services. Live at natasha.monkeythorn.com | `Node.js` `ECS Fargate` `Twilio` `Deepgram` `Claude` `ElevenLabs` |
| [**HMU API**](https://hmuapi.com) | Machine-readable inbox — open signup, AI triage, agent-discoverable REST endpoints, reputation graph, live pitch scoring | `Cloudflare Workers` `D1` `Hono` `Astro 5` `React 19` `Claude` `Resend` |
| [**MonkeyThorn Meet**](https://meet.monkeythorn.com/meet) | Private, E2E encrypted video conferencing — no accounts, no tracking | `Next.js` `TypeScript` `LiveKit` `WebRTC` |
| [**1ness Insights**](https://www.1nessagency.com/insights) | Auto-publishing blog for 1ness Strategies — content engine integration, brand-aware covers, FAQ extraction | `Cloudflare Workers` `Bedrock` `S3` `CloudFront` |
| **Google Ads Manager** | Campaign management with health scoring, anomaly detection, wasted spend analysis, ROAS benchmarking | `Next.js` `TypeScript` `SQLite` |

#### Utilities

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**gOOOvy**](https://gooovy.com) | Auto-reply bot for Google Voice texts with native iOS companion app | `Python` `Swift` `SwiftUI` |
| [**OpenTime**](https://apps.apple.com/us/app/opentime/id6760204246) | Calendar availability widget — free/busy slots on macOS and iOS | `Swift` `WidgetKit` `EventKit` |
| **Resy Sniper** | Automated restaurant reservation bot — monitors and books the moment slots open | `Python` `Flask` `Resy API` |
| **Quick Reply** | macOS utility — contextual text replies in multiple tones via keyboard shortcut | `Python` `Claude Haiku` |
| **Flipper Bridge** | Flipper Zero + Claude AI bridge for hardware analysis | `Python` `Claude` |

---

### Background

Cornell MBA · M.S. Biotechnology · Former Vaxart, M Science/Jefferies

---

<p align="center">
  <a href="https://www.jamestannahill.com">jamestannahill.com</a> ·
  <a href="https://www.linkedin.com/in/jamesstannahill/">LinkedIn</a> ·
  <a href="https://plocamium.com">Plocamium Holdings</a> ·
  <a href="https://www.bloomberg.com/profile/person/23291921">Bloomberg</a> ·
  <a href="https://hmuapi.com">HMU API</a>
</p>
