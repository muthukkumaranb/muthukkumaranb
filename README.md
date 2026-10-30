<div align="center">

<img src="./hero-banner.png" width="100%" alt="Muthukkumaran B, backend and ML engineer. I build ML systems you can verify, and the backends that run them."/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=17&duration=2600&pause=900&color=4FE08A&center=true&vCenter=true&width=700&lines=Backend+%2B+ML+engineer;Merged+fix+in+deepset+Haystack;SIH+2026+team+lead+%C2%B7+5x+hackathon+finalist;Open+to+backend+%2F+ML+internships" alt="Backend + ML engineer · Merged fix in deepset Haystack · SIH 2026 team lead · 5x hackathon finalist"/>

**[Portfolio](https://muthukkumaranb.is-a.dev)** · [Résumé](https://muthukkumaranb.is-a.dev/Muthukkumaran_B_Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/muthukkumaranb/) · [Email](mailto:mailtomuthukkumaranb@gmail.com)

</div>

```console
$ whoami
Muthukkumaran B · Second Year B.Tech IT, SKCET Coimbatore · CGPA 9.05
I build ML systems you can verify, and the backends that run them:
baselines, held-out tests and reproducible numbers behind every claim.

$ status
● Android Development Intern @ Pensive (Nov 2026 –)
● open to backend / ML internships: remote part-time now, full-time Summer 2027
```

## Open Source

| Project | What I did | Status |
|---|---|---|
| **deepset Haystack** · [haystack-core-integrations](https://github.com/deepset-ai/haystack-core-integrations) | Lara translator silently ignored `reasoning=False` because of an `x or default` check. Fixed it to `x if x is not None else default` and added a mocked regression test. [Issue #4168](https://github.com/deepset-ai/haystack-core-integrations/issues/4168) · [PR #4169](https://github.com/deepset-ai/haystack-core-integrations/pull/4169) · [write-up](https://muthukkumaranb.is-a.dev/notes-x-or-default.html) | ✅ Merged |
| **LlamaIndex** · [llama_index](https://github.com/run-llama/llama_index) | `SimpleDirectoryReader` crashed when loading through an fsspec `DirFileSystem`. Passed string paths to `fs.open()` and added three regression tests. [Issue #23663](https://github.com/run-llama/llama_index/issues/23663) · [PR #23664](https://github.com/run-llama/llama_index/pull/23664) | 🔍 In review |

## Featured projects

All are team projects. Each one says the team size and what I personally built.

### 🛩️ [SHIKRA](https://github.com/muthukkumaranb/shikra): predicting engine removals for a 54-aircraft fleet
<sub>Smart India Hackathon 2026 · SIH26249 (Ministry of Defence) · team of 6 · **team lead**</sub>

- **ML:** LightGBM quantile models with conformal calibration. **11.64 RMSE** on NASA C-MAPSS FD001 (vs 18.45 for a published CNN baseline), and **81% coverage** of 80% intervals on held-out engines.
- **Systems:** **72.7 → 0** unscheduled removals per year in fleet simulation, OR-Tools CP-SAT scheduling, HMAC audit log.
- **My part:** the remaining-life model, data ingestion and audit logs.
- `Python` `LightGBM` `conformal prediction` `OR-Tools` `Streamlit` · [Case study](https://muthukkumaranb.is-a.dev/shikra.html) · [Live demo](https://muthukkumaranb.is-a.dev/#demos)

### 🐈‍⬛ [ShadowCat](https://github.com/muthukkumaranb/ShadowCat): early attack warning with a log nobody can quietly edit
<sub>Smart India Hackathon 2026 · SIH26153 (NTRO) · team of 6 · **team lead**</sub>

- **ML:** **0.907** five-minute onset F1 under 37-fold leave-one-episode-out validation, and **0.990** detection F1.
- **Systems:** an Ed25519-signed SHA-256 hash chain with a Merkle root, so any forecast has an O(log n) inclusion proof and edits are detectable offline.
- **My part:** ingestion and the cryptographic audit chain.
- `Python` `PyTorch` `scikit-learn` `Ed25519` `Merkle trees` · [Case study](https://muthukkumaranb.is-a.dev/shadowcat.html) · [Tamper with the log](https://muthukkumaranb.is-a.dev/#demos)

### 🛡️ [SENTINEL](https://github.com/muthukkumaranb/vitcsiorigins): catching insider threats
<sub>CSI Origins 2026, VIT Chennai · **finalist** · team of 4</sub>

- Flags valid users doing valid actions in invalid patterns by fusing three engines: behaviour (45%), sequence (30%) and Random Forest (25%), scaled by operational context.
- **My part:** most of the React + TypeScript investigation console, the Flask API and event processing, the ML dataset builder and model registry, and the API and architecture docs.
- `Python` `Flask` `scikit-learn` `React` `TypeScript`

### 🧾 [Mini ERP](https://github.com/muthukkumaranb/minierp): 14 business modules in one Django codebase
<sub>Odoo x KAHE Hackathon · **finalist** · team of 2</sub>

- **My part:** inventory, purchasing and procurement with Celery background tasks, the audit log via Django signals, and the local-LLM (Ollama) voice assistant API.
- `Django` `HTMX` `Alpine.js` `Celery` `SQLite` `Ollama` · [Case study](https://muthukkumaranb.is-a.dev/minierp.html)

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it is | Team |
|---|---|---|
| [HoloTwin](https://github.com/muthukkumaranb/HoloTwin-AeroThon) | Physics-informed digital twin of a turbojet (Aerothon 2026, HAL x IIT Indore). I built the PINN surrogate in PyTorch with physics constraints in the loss, exported it to ONNX and compared it against a Random Forest. | 2 |
| [ASHA health voice agent](https://github.com/muthukkumaranb/murf-voice-ai) | Multilingual voice assistant for community health workers (Murf AI "10 Days of Voice Agents for Bharat"): consent-based memory, health centre lookup, outbound calls over LiveKit SIP. | — |
| [Air Canva](https://github.com/muthukkumaranb/aircanva) | Draw in the air: MediaPipe hand tracking drives a canvas, with gestures to draw, erase and pick colours. | solo |

</details>

## Experience

**Android Development Intern** · Pensive · *Nov 2026 – present* · remote

**Team lead, Smart India Hackathon 2026** · team of 6 · *Aug – Oct 2026*
- Led one team through two problem statements in parallel (SHIKRA and ShadowCat), split the work into data, ML, backend and front-end tracks, and reviewed every merge.
- Both projects were shortlisted at the college level and submitted for the national level.

**Student Hackathon Coordinator** · B.Tech IT, SKCET · *current*
- Coordinate hackathon participation for the department, including the [Tech-Escape](https://www.hackerrank.com/contests/tech-escape/challenges) coding contest.

**Technical Trainer Intern** · CSC Computer Education, Erode · *Apr – May 2026*
- Taught Python, C and C++ to 50+ students. Certificate of excellence for communication and technical delivery.

## Hackathons

**5x finalist:** Odoo x KAHE (Karpagam) · Samhita (MIT Chennai) · Hydro Hackathon (IIT Madras) · Sparkathon (CIT) · CSI Origins (VIT Chennai)

<sub>Also competed in: Smart India Hackathon 2026 (team lead) · Aerothon 2026 (HAL x IIT Indore) · Murf AI 10 Days of Voice Agents · UIDAI Data Hackathon · Road Safety Hackathon (IIT Madras) · Bharatiya Antariksh Hackathon (ISRO) · Samsung Solve for Tomorrow · Tally CodeBrewers · Snapdragon Multiverse · Flipkart GRiD 8.0</sub>

## What I work with

| | |
|---|---|
| **Backend** | Python, Django, REST APIs, Flask, Celery, SQLite, HTMX, Java, C++ |
| **ML** | LightGBM, PyTorch, scikit-learn, conformal prediction, pandas, OpenCV, MediaPipe, Ollama |
| **Systems** | SHA-256 / HMAC / Ed25519 audit logs, Merkle trees, OR-Tools CP-SAT |
| **Practice** | pytest and mocking, Ruff, uv, Hatch, Git, reproducible pipelines, open-source code review |
| **Learning now** | Kotlin, Jetpack Compose, Coroutines |

<div align="center">

<br/>

<sub>**VENI · VIDI · VICI** · Hiring for a backend or ML intern? [Email me](mailto:mailtomuthukkumaranb@gmail.com). I reply within a day.</sub>

</div>
