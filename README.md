# Hi, I'm Benoit Desnos

Staff Engineer with 20 years of experience. I build things from scratch with small teams: identity systems, reverse engineering, developer tools, AI pipelines.

Currently at [SpringCard](https://www.springcard.com), working on digital identity (mDL, MRTD, EUDI Wallet) and B2B SaaS architecture.

---

### What I build

**MCP Servers**

- **[melchizedek](https://github.com/louis49/melchizedek)** ![npm](https://img.shields.io/npm/dt/melchizedek?label=npm) - Persistent memory for Claude Code. Hybrid search engine (BM25 + vectors + reranker) over conversation history. 100% local, zero API keys.

**Reverse Engineering & IoT**

- **[androidtv-remote](https://github.com/louis49/androidtv-remote)** ![npm](https://img.shields.io/npm/dt/androidtv-remote?label=npm) - Reverse-engineered the Android TV remote control protocol (PairingSession + RemoteManager over TLS). Node.js library, 88 stars. [Write-up](https://medium.com/@bdesnos/side-project-androidtv-homekit-d0a26a780c1d).
- **[homebridge-plugin-androidtv](https://github.com/louis49/homebridge-plugin-androidtv)** ![npm](https://img.shields.io/npm/dt/homebridge-androidtv?label=npm) - Homebridge verified plugin. Bridges Android TV into Apple HomeKit. Built on top of androidtv-remote.
- **[homebridge-browsercam](https://github.com/louis49/homebridge-browsercam)** - Turn any old phone into a HomeKit camera via browser. [Write-up](https://medium.com/@bdesnos/comment-fabriquer-une-camera-homekit-avec-un-vieux-smartphone-36d8f0bf5b3a).
- **[NineBot-ES2](https://github.com/louis49/NineBot-ES2)** - Reverse-engineered the Ninebot ES2 scooter BLE protocol. Found a security flaw allowing remote unlock without authentication. [Write-up (19K views)](https://medium.com/@bdesnos/comment-jai-hack%C3%A9-ma-trottinette-4eae1fc1dca1).

**Cryptography & Identity**

- OpenSSL compiled to WebAssembly - 70+ elliptic curves, 28 hash algorithms, full crypto in the browser
- ISO 18013-5 (mDL) and ICAO 9303 (MRTD) implementations from scratch in TypeScript
- France Identite app reverse engineering (Frida, Ghidra)

**ML / AI**

- **YokeBrain** *(private)* - AI-powered business model generator. Collides two domains via bisociation theory (Koestler), ~450 LLM calls across 7 pipeline phases. NestJS, Vue 3, PostgreSQL, Kubernetes.
- **Lego Emergent Communication** *(private)* - Research project: AI agents develop their own communication protocol to describe and reconstruct 3D LEGO structures under bandwidth constraints. PyTorch, NumPy, TensorBoard.
- **arXiv Scanner** *(private)* - Pipeline that ingests ~5K arXiv papers, filters by LLM (Haiku triage, Sonnet commercial scoring across 6 dimensions), identifies papers transformable into products. TypeScript, SQLite, Claude API.
- **CE Differentiator** *(private)* - CNN image classifier distinguishing authentic EU CE marking from counterfeit Chinese CE marking. 151K synthetic training images (Albumentations, Perlin noise). TensorFlow/Keras, OpenCV.
- **[ml-sonets](https://github.com/louis49/ml-sonets)** - Self-generative sonnets using autoencoder (TensorFlow/Keras). Trained on 4,820 classical French poems.

---

### Tech stack

**Languages** - TypeScript, JavaScript, Python, Swift, Objective-C, C

**Backend** - Node.js, NestJS, Kafka, PostgreSQL, YugabyteDB, Redis, SQLite

**Infrastructure** - Kubernetes, Docker, Helm, CI/CD, Prometheus, Grafana

**AI/ML** - TensorFlow/Keras, Transformers.js, MCP SDK, LLM pipelines

**Security** - OpenSSL, PKCS#7, ECDH, PACE/BAC, NFC protocols, BLE reverse engineering

**Frontend** - Vue.js, React Native

---

### Career highlights

| Period | Role | Scope |
|--------|------|-------|
| 2024–now | Staff Engineer, SpringCard | Digital identity (mDL, MRTD, EUDI), SaaS B2B (70k LOC), OpenSSL-WASM |
| 2021–2024 | Tech Lead, Groupe CREATIVE | Agile projects (200–1000 man-days), 8-person team |
| 2018–2020 | CTO, BeMyApp | Hackathon SaaS (Microsoft, Google, L'Oreal), team 4 to 8, -80% hosting costs |
| 2016–2018 | CTO, iLearn | ML/speech recognition R&D, TensorFlow feasibility study |
| 2015–2016 | CTO, MobilisPro | Two-sided SaaS connecting voice actors and producers (film, TV, radio, games), 1st tech hire, team of 5–7 |
| 2012–2015 | PM / Mobile Lead, Netapsys | Mobile projects (iOS/Android), 3–10 person teams |
| 2006–2011 | Analyst / Designer, Infotel then Sogeti | Enterprise (E.Leclerc, MMA, France Telecom) |

---

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-benoit--desnos-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/benoit-desnos/)
