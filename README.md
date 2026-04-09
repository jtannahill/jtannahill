<h1 align="center">James Tannahill</h1>

<p align="center">
  <strong>Intelligent Capital at <a href="https://x.ai">xAI</a> · PE Executive & Founder</strong> — New York City<br/>
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
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/AWS_CDK-232F3E?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Bedrock-FF9900?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Step_Functions-FF4F8B?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/SageMaker-7B68EE?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white" />
  <img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white" />
  <img src="https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat&logo=opensearch&logoColor=white" />
  <img src="https://img.shields.io/badge/SvelteKit-FF3E00?style=flat&logo=svelte&logoColor=white" />
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=flat&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/D3.js-F9A03C?style=flat&logo=d3dotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Mapbox-000000?style=flat&logo=mapbox&logoColor=white" />
  <img src="https://img.shields.io/badge/LiveKit-000000?style=flat&logo=webrtc&logoColor=white" />
  <img src="https://img.shields.io/badge/Replicate-000000?style=flat&logo=replicate&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat&logo=twilio&logoColor=white" />
  <img src="https://img.shields.io/badge/Deepgram-13EF93?style=flat&logo=deepgram&logoColor=black" />
  <img src="https://img.shields.io/badge/ElevenLabs-000000?style=flat&logo=elevenlabs&logoColor=white" />
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
| **[MonkeyThorn](https://meet.monkeythorn.com/meet)** | Privacy-first communications infrastructure (Meet, NatashAI) |

---

### What I Build

#### Intelligence & ML

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**Plocamium Content Engine**](https://github.com/jtannahill/plocamium-content-engine) | AI content pipeline + intelligence platform. 3 news sources, 172 RSS feeds / 13 lanes, OpenSearch RAG, 17 post types, brand-aware covers (Flux 1.1 Pro), Polly audio. **ML**: momentum scorer, sector clustering, cross-cluster triggers. **Plocamium Signal Index (PSI)**: daily composite z-score — 5 orthogonal signals (Hawkes, Titan drift, spectral shift, SMD, HHI), Kalman-smoothed, regime-aware (BOCPD), 12 canonical BICS sectors. PSI export PDF, diverging sector heatmap, So What narrative. **6-model link prediction** (GCN, Node2Vec, VGAE, TransE + heuristics). **Entity Intelligence Cards** with 5 proprietary metrics. **Entity watchlists** with 5 alert triggers + daily digest. **150 entity dossier pages**. **[Global Intelligence Network](https://plocamium.com/globals/intelligence)**: D3.js visualization, SEC EDGAR integration | `Step Functions` `Lambda` `Bedrock` `OpenSearch` `SES` `Polly` `Comprehend` `Replicate` `D3.js` `CloudFront` `Kalman Filter` `Node2Vec` `VGAE` `TransE` `BOCPD` `Titan Embeddings` `SEC EDGAR` `ReportLab` |
| [**Argus**](https://github.com/jtannahill/argus) | Building intelligence for NYC — point your phone at any building for ownership, value, violations, air rights, diplomatic status. GPS + 3D ray casting with LiDAR heights, CLIP visual matching (20K embeddings), Bedrock AI narratives, 8 NYC public data APIs | `Swift 6` `CDK` `Lambda` `DynamoDB` `SageMaker (CLIP)` `Bedrock` `Step Functions` `Mapbox` `Cognito` |
| **Aletheia** _(in development)_ | OSINT intelligence — entity enrichment from 11+ sources, sanctions/PEP screening, graph visualization, geofencing, AI briefs | `CDK` `Lambda` `DynamoDB` `Step Functions` `SvelteKit` `Mapbox` `Cytoscape.js` |
| **Email Intel** | Email header analysis + org infrastructure profiling. 147 orgs profiled, rules-based change classifier (positive/negative/neutral), web dashboard | `Python` `Lambda` `DynamoDB` `Bedrock` `CDK` |
| [**DomainIQ**](https://d17ia582bwv8z0.cloudfront.net) | Domain portfolio intelligence — SageMaker XGBoost valuation model, AI appraisals, weighted forecasting, rule-based renewal engine for 307+ domains | `SvelteKit` `Tailwind` `CDK` `Lambda` `DynamoDB` `SageMaker` `Bedrock` |
| [**Edgar Intel**](https://github.com/jtannahill/edgar-intel) | CLI-first SEC filing intelligence — XBRL financials, 8-K events, Form 4 insiders, SC 13D stakes, proxy filings, comment letters. Russell 1000 universe. WACC estimation, NL comparison, balance sheet/ratio analysis, sensitivity heatmaps. 8 crawler Lambdas, Bedrock AI summaries | `Python` `CDK` `Lambda` `DynamoDB` `S3` `Bedrock` `API Gateway` `Chart.js` `Tailwind` |
| **LeadFlow** _(in development)_ | Real estate lead intelligence — county records, skip trace enrichment, AI scoring, weekly delivery for South Florida agents | `CDK` `Lambda` `DynamoDB` `ECS Fargate` `Playwright` `SQS` `Bedrock` |

#### Creative & Generative

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**Art Generator**](https://art.jamestannahill.com) | Daily generative art from live atmospheric data — 50 global weather stations, 11 artist styles, 249+ artworks, satellite color palettes from Copernicus Sentinel-2. Rendered by Flux 1.1 Pro. ML art critic, weather forecaster, dynamic pricing. Newsletter, print shop, RSS syndication | `CDK` `Step Functions` `Lambda` `Replicate (Flux 1.1 Pro)` `Bedrock` `Open-Meteo` `Sentinel Hub` `Resend` `S3` `CloudFront` |
| [**FX30 Pipeline**](https://media.jamestannahill.com/browse/) | Live streaming + recording — IVS broadcast, MediaConvert transcoding, Transcribe + Bedrock analysis, media gallery with download/embed | `Lambda` `IVS` `MediaConvert` `Transcribe` `Bedrock` `CloudFront` |

#### Expression Intelligence

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**PRISM**](https://github.com/jtannahill/prism-ios) | Real-time expression intelligence for video calls — live floating HUD over Zoom and Google Meet. Self-analysis via ARKit TrueDepth (52 blend shapes at 60fps). Remote participant analysis via ReplayKit screen capture + Vision face landmarks. 6 composite signals: engagement, stress, smile authenticity, cognitive load, contempt, suppression. Key moment detection, post-session timeline dashboard, iCloud sync | `Swift` `SwiftUI` `ARKit` `Vision` `ReplayKit` `AVKit` `Swift Charts` |

#### Communications & Platforms

| Project | What It Does | Stack |
|---------|-------------|-------|
| **NatashAI** | Streaming voice AI phone assistant — manages calendar, email, and Zoom via real-time conversation. 30 tools, 14 services. Live at [natasha.monkeythorn.com](https://natasha.monkeythorn.com) | `Node.js` `ECS Fargate` `Docker` `Twilio` `Deepgram` `Claude` `ElevenLabs` |
| [**HMU API**](https://hmuapi.com) | Machine-readable inbox — open signup, AI triage, agent-discoverable REST endpoints, reputation graph, live pitch scoring | `Cloudflare Workers` `Cloudflare Pages` `D1` `Hono` `Astro 5` `React 19` `Claude` `Resend` |
| [**MonkeyThorn Meet**](https://meet.monkeythorn.com/meet) | Private, E2E encrypted video conferencing — no accounts, no tracking | `Next.js` `TypeScript` `LiveKit` `WebRTC` `Docker` |
| [**1ness Strategies Site**](https://www.1nessagency.com) | Self-hosted marketing site — 40 pages, 4 case studies, 8 service landing pages, glossary, full SEO/schema/AIO. Auto-publish pipeline via EventBridge → GitHub Actions | `Astro 6` `S3` `CloudFront` `CDK` `GitHub Actions` |
| [**1ness Insights**](https://www.1nessagency.com/blog) | Auto-publishing blog for 1ness Strategies — content engine integration, brand-aware covers, auto-deployed via GitHub Actions | `Astro 6` `Cloudflare Workers` `KV` `Bedrock Haiku` `S3` `CloudFront` |
| [**Project Zulu**](https://github.com/jtannahill/project-zulu) | xAI Hackathon — Chrome extension surfacing live X conversation intelligence on any webpage, powered by Grok. Video-aware, context-aware, real-time | `Chrome Extensions` `TypeScript` `Grok API` `xAI` |
| **Google Ads Manager** | Campaign management with health scoring, anomaly detection, wasted spend analysis, ROAS benchmarking | `Next.js` `TypeScript` `SQLite` |

#### Utilities

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**SigScan**](https://github.com/jtannahill/SigScan) | Personal RF environment scanner for iOS — BLE device fingerprinting (50+ vendors, RSSI-based distance estimates, device classification), NFC tag decoding, WiFi/cellular info, GPS-stamped scan logging with map view, AR overlay with world-space bubble placement and RSSI trilateration, on-device anomaly/risk detection, Claude AI query interface (key via AWS Secrets Manager) | `Swift` `SwiftUI` `CoreBluetooth` `CoreNFC` `ARKit` `RealityKit` `SwiftData` `MapKit` `CoreLocation` `CryptoKit` |
| [**VECTOR**](https://github.com/jtannahill/vector-nfc) | Universal NFC reader — decodes every tag type reachable from CoreNFC on iOS 17+: NDEF, ISO 7816 (PIV/CAC/EMV/FIDO2), ISO 14443-B, ISO 15693, MIFARE, FeliCa, and PACE/ePassport (ICAO 9303 EF.CardAccess). Intelligent payload decoding, APDU exchange logging, cancel-scan gesture, AWS DynamoDB scan history | `Swift` `SwiftUI` `CoreNFC` `AWS SAM` `Lambda` `DynamoDB` `API Gateway` |
| [**gOOOvy**](https://gooovy.com) | Auto-reply bot for Google Voice texts — dual-tier (free + Pro at $8.99/mo), VIP contacts, scheduling, native iOS companion app, OAuth brand-verified | `Python` `Swift` `SwiftUI` `CDK` `Lambda` `DynamoDB` `Stripe` `Apple IAP` |
| [**wx.jamestannahill.com**](https://wx.jamestannahill.com) | Live hyperlocal weather dashboard for Midtown Manhattan — 5-minute resolution personal weather station data, analog forecast (nearest-neighbor pattern matching on 90 days of history), comfort score, rain probability, urban heat island delta vs JFK/LGA/EWR, station records, uPlot history charts | `JavaScript` `AWS CDK` `Lambda` `DynamoDB` `S3` `CloudFront` `Ambient Weather` `NOAA` `Apple WeatherKit` |
| [**jamestannahill.com**](https://www.jamestannahill.com) | Personal portfolio — Astro 6, full SEO/schema/AIO, self-hosted NHG Display font CDN. Subdomains: interactive Mapbox map, tactical digital business card with MECARD QR + Apple Wallet pass | `Astro 6` `Tailwind` `S3` `CloudFront` `CDK` `Mapbox` |
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
