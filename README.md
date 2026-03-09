# Hi, I'm Benoit Desnos

AI/LLM Architect with 20 years of engineering. I build production systems from scratch - AI pipelines, identity protocols, developer tools. Alone if needed, then with a team.

---

### AI / LLM Systems

- **YokeBrain** *(private)* - AI-powered business model generator. 6-phase pipeline orchestrating ~450 LLM calls via bisociation theory (Koestler). Embeddings, multi-criteria reranking, ontology-driven generation, cognitive bias integration (175+ biases across 7 roles). NestJS, Vue 3, PostgreSQL, Kubernetes.
- **[melchizedek](https://github.com/louis49/melchizedek)** ![npm](https://img.shields.io/npm/dt/melchizedek?label=npm) - MCP Server for Claude Code. Hybrid search engine combining BM25, vector similarity, and reranking over conversation history. 100% local, zero API keys. Published on npm.
- **arXiv Scanner** *(private)* - Pipeline ingesting ~5K arXiv papers, LLM-powered triage (Haiku for fast filtering, Sonnet for commercial scoring across 6 dimensions), identifies papers transformable into products. TypeScript, SQLite, Claude API.
- **Kalamos** *(private)* - Local-first LinkedIn editorial manager. MCP Server with 10 tools for Claude Code: hybrid search (BM25 + vectors + RRF + reranker), full lifecycle (draft → schedule → publish → analytics), OAuth2 publishing, anti-detection corpus scraping via Patchright. TypeScript, SQLite, sqlite-vec, ~9K LOC.
- **LLM Agent Pipeline** *(private)* - LinkedIn post generator using 9 parallel LLM agents. Each agent evaluates tension/angle pairs on content drafts via structured output (Zod schemas), automated congruence scoring, voice profile extraction. TypeScript, Claude API.
- **CE Differentiator** *(private)* - CNN image classifier distinguishing authentic EU CE marking from counterfeit Chinese export marking. 151K synthetic training images (Albumentations, Perlin noise). TensorFlow/Keras, OpenCV.
- **Lego Emergent Communication v2** *(private)* - Research: do neural agents develop modular or monolithic communication protocols under incremental complexity? 3D CNN encoder/decoder, Gumbel-Softmax discrete channel, 4x4x4 grids with 2-10 colors. Sequential learning produces stable modular protocols (F1>=95%); from-scratch collapses at N>=6. PyTorch, TensorBoard. Targeting publication Q2 2026.
- **[ml-sonets](https://github.com/louis49/ml-sonets)** - Self-generative sonnets using autoencoder (TensorFlow/Keras). Trained on 4,820 classical French poems.

### Reverse Engineering & IoT

- **[androidtv-remote](https://github.com/louis49/androidtv-remote)** ![npm](https://img.shields.io/npm/dt/androidtv-remote?label=npm) - Reverse-engineered the Android TV remote control protocol (PairingSession + RemoteManager over TLS). Node.js library, 88 stars, used by 30+ downstream projects including Home Assistant. [Write-up](https://medium.com/@bdesnos/side-project-androidtv-homekit-d0a26a780c1d).
- **[homebridge-plugin-androidtv](https://github.com/louis49/homebridge-plugin-androidtv)** ![npm](https://img.shields.io/npm/dt/homebridge-androidtv?label=npm) - Homebridge verified plugin. Bridges Android TV into Apple HomeKit.
- **[homebridge-browsercam](https://github.com/louis49/homebridge-browsercam)** - Turn any old phone into a HomeKit camera via browser. [Write-up](https://medium.com/@bdesnos/comment-fabriquer-une-camera-homekit-avec-un-vieux-smartphone-36d8f0bf5b3a).
- **[NineBot-ES2](https://github.com/louis49/NineBot-ES2)** - Reverse-engineered the Ninebot ES2 scooter BLE protocol. Found a security flaw allowing remote unlock without authentication. [Write-up (19K views)](https://medium.com/@bdesnos/comment-jai-hack%C3%A9-ma-trottinette-4eae1fc1dca1).

### Cryptography & Identity

- OpenSSL compiled to WebAssembly -70+ elliptic curves, 28 hash algorithms, full crypto in the browser
- ISO 18013-5 (mDL) and ICAO 9303 (MRTD) implementations from scratch in TypeScript
- France Identite government app reverse engineering (Frida, Ghidra)

---

### Tech stack

**AI/ML** - LLM pipelines (Claude, structured output, Zod), MCP SDK, embeddings, reranking, RAG, TensorFlow/Keras, Transformers.js

**Backend** - Node.js, NestJS, Kafka, PostgreSQL, YugabyteDB, Redis, SQLite

**Infrastructure** - Kubernetes, Docker, Helm, CI/CD, Prometheus, Grafana

**Security** - OpenSSL, PKCS#7, ECDH, PACE/BAC, NFC protocols, BLE reverse engineering

**Languages** - TypeScript, JavaScript, Python, Swift, C

**Frontend** - Vue.js

---

### Career highlights

| Period | Role | Scope |
|--------|------|-------|
| 2024–now | Staff Engineer, SpringCard | Digital identity (mDL, MRTD, EUDI), SaaS B2B (110k LOC), OpenSSL-WASM, sole developer |
| 2021–2024 | Tech Lead, Groupe CREATIVE | Agile projects (200–1000 man-days), 8-person team |
| 2020–2021 | Senior PM, Inetum | SI Vitale program (CNAM), 12-person team within 90 FTE program |
| 2018–2020 | CTO, BeMyApp | Hackathon SaaS (Microsoft, Google, L'Oréal), team 4 to 8, -80% hosting costs |
| 2016–2018 | CTO, iLearn | ML/speech recognition R&D, TensorFlow feasibility study |
| 2015–2016 | CTO, MobilisPro | Two-sided SaaS (film, TV, radio, games), 1st tech hire, team of 5–7 |
| 2012–2015 | PM / Mobile Lead, Netapsys | Mobile projects (iOS/Android), 3–10 person teams |
| 2010–2011 | PM / Analyst, Infotel | Detached at SIGMA (E.Leclerc) |
| 2006–2010 | Functional Designer, Sogeti | Enterprise clients (CNIEG, ENIM, MMA, France Telecom) |

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-benoit--desnos-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/benoit-desnos/)
