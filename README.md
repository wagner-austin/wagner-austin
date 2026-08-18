<p align="center">
  <img src="https://github-stats-api-production-5042.up.railway.app/api/hero?name=Austin%20Wagner&subtitle=Software%20Engineer%20%7C%20MCP%20%26%20Agent%20Infrastructure%20%7C%20ML%20Research&lines=B.A.%20Language%20Science%20%E2%80%94%20ML%20%26%20LLMs%20%40%20UC%20Irvine|Published%3A%20HSP%202026%20%26%20Tu%2B11%20(MIT)|LightGBM%20Contributor%20(9%20merged%20PRs)|Multi-tenant%20MCP%20platform%20operator|Former%20EMT%20(7%20yrs)&theme=cyberpunk" alt="hero" />
</p>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Briefcase.png" width="24" /> Experience</h2>

<table>
<tr>
<td><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Classical%20Building.png" width="24"/></td>
<td><b>Council Executive Assistant</b></td>
<td>Local elected official's office (Southern California)</td>
<td><code>Policy</code></td>
</tr>
<tr>
<td><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Microscope.png" width="24"/></td>
<td><b>Research Assistant</b></td>
<td>UC Irvine</td>
<td><code>Aug 2024 - Present</code></td>
</tr>
<tr>
<td><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Camera%20with%20Flash.png" width="24"/></td>
<td><b>Professional Photographer</b></td>
<td>Corvis Photography</td>
<td><code>May 2022 - Present</code></td>
</tr>
<tr>
<td><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Ambulance.png" width="24"/></td>
<td><b>Emergency Medical Technician</b></td>
<td>Falck Ambulance</td>
<td><code>Mar 2015 - Nov 2021</code></td>
</tr>
</table>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Scroll.png" width="24" /> Research</h2>

**Language Model Loss Captures Mutual Intelligibility Gradients in Turkic Languages**
<br>Moldir Baidildinova, Shiva Upadhye, Austin Wagner (UC Irvine)

- Accepted at [**HSP 2026**](https://hsp2026.org/) (39th Annual Conference on Human Sentence Processing, MIT) and [**Tu+11**](https://turkicworkshop.github.io/tu11/) (11th Workshop on Turkic and Languages in Contact with Turkic, MIT)
- Character-level LSTM trained on 6 Turkic languages + Finnish (control), all transliterated to broad IPA
- Built on [**Turkic API**](https://github.com/wagner-austin/API/tree/main/services/turkic-api) — rules-based IPA transliteration with phonetic rules cited from peer-reviewed research

**Corpus-Level Knowledge Interventions — a Seven-Arm Extraction Ablation**

- Tested whether two published corpus-design interventions replicate on real cited prose rather than synthetic data — GPT-2, seven arms, three seeds each
- Built the evaluation instrument first: **2,627 four-way cloze items** generated from a corpus's own citation apparatus, with the unexposed-model baseline established at 52.3% before any arm ran
- Contrasts scored with **exact McNemar tests over discordant items**, run per seed rather than pooled — the arms share one deterministic item set, so per-seed differences are correlated
- Three of five contrasts reported as nulls, including a published intervention inert under all three conditions its source specifies

**Plant Metabolomics & BVOCs**

- Research on **biogenic volatile organic compounds** from tree leaf and root tissues across 9 California field sites
- GC-MS data processing pipeline: [**Tree Bot**](https://github.com/wagner-austin/Tree-Bot) — peak detection, co-elution analysis, compound classification
- Interactive [**Metabolomics Dashboard**](https://austinwagner.org/metabolomics/) — Welch's t-test with FDR correction, D3.js visualizations

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="24" /> Featured Projects</h2>

All services live in my [**API monorepo**](https://github.com/wagner-austin/API) — 13 microservices, 22 shared libraries, FastAPI + Redis + RQ architecture.

<table>
<tr>
<td width="50%" valign="top">
<h3>Covenant Radar</h3>
<a href="https://github.com/wagner-austin/API/tree/main/services/covenant-radar-api"><img src="https://img.shields.io/badge/View_Repo-141321?style=for-the-badge&logo=github"/></a>
<p><sub>Loan covenant monitoring with ML breach prediction — XGBoost, LightGBM, MLP, LSTM, Optuna optimization, Kafka streaming</sub></p>
</td>
<td width="50%" valign="top">
<h3>Model Trainer</h3>
<a href="https://github.com/wagner-austin/API/tree/main/services/Model-Trainer"><img src="https://img.shields.io/badge/View_Repo-141321?style=for-the-badge&logo=github"/></a>
<p><sub>GPT-2 and Char-LSTM training with LoRA/QLoRA fine-tuning, mixed-precision (FP16/BF16), WandB integration</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>Turkic API</h3>
<a href="https://github.com/wagner-austin/API/tree/main/services/turkic-api"><img src="https://img.shields.io/badge/View_Repo-141321?style=for-the-badge&logo=github"/></a>
<p><sub>Turkic language corpus processing — FastText detection, IPA transliteration (Cyrillic/Latin/Arabic), 9 languages</sub></p>
</td>
<td width="50%" valign="top">
<h3>Grandma API</h3>
<a href="https://github.com/wagner-austin/API/tree/main/services/grandma-api"><img src="https://img.shields.io/badge/View_Repo-141321?style=for-the-badge&logo=github"/></a>
<a href="https://grandma.austinwagner.org/"><img src="https://img.shields.io/badge/Live_Demo-ff00ff?style=for-the-badge&logo=github"/></a>
<p><sub>Multi-language audio to English translation — Whisper STT, MMS-LID, GPT-4o-mini (57 languages)</sub></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>Art Trainer</h3>
<a href="https://github.com/wagner-austin/API/tree/main/services/Art-Trainer"><img src="https://img.shields.io/badge/View_Repo-141321?style=for-the-badge&logo=github"/></a>
<p><sub>LoRA/IP-Adapter training for Stable Diffusion 1.5, SDXL, and FLUX — auto-captioning, ComfyUI deployment</sub></p>
</td>
<td width="50%" valign="top">
<h3>ClearGBM</h3>
<a href="https://github.com/wagner-austin/API/tree/main/libs/cleargbm"><img src="https://img.shields.io/badge/View_Repo-141321?style=for-the-badge&logo=github"/></a>
<p><sub>From-scratch gradient boosting — Rust compute core via PyO3, ported from an original NumPy implementation that was retired once the port was verified</sub></p>
</td>
</tr>
</table>

<details>
<summary><b>All Services (13) & Shared Libraries (22)</b></summary>
<br>

See the full [**API monorepo**](https://github.com/wagner-austin/API) for all services and libraries including Data Bank, Music Wrapped, Transcript API, Handwriting AI, QR API, GitHub Stats, Opportunity Radar, Procart API, and 22 shared libraries covering ML, NLP, workers, persistence, and more.

</details>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Desktop%20Computer.png" width="24" /> Dashboards</h2>

Interactive data dashboards at [**austinwagner.org**](https://austinwagner.org/) — see the [**Dashboards repo**](https://github.com/wagner-austin/Dashboards).

<table>
<tr>
<td width="50%" valign="top">
<h3>OC City Councils</h3>
<a href="https://austinwagner.org/oc-city-councils/"><img src="https://img.shields.io/badge/Live-ff00ff?style=for-the-badge"/></a>
<p><sub>City council data for 34 Orange County cities — YAML-driven, SQLite-backed, GitHub Actions auto-rebuild</sub></p>
</td>
<td width="50%" valign="top">
<h3>ASUCI Senate</h3>
<a href="https://austinwagner.org/asuci/"><img src="https://img.shields.io/badge/Live-ff00ff?style=for-the-badge"/></a>
<p><sub>UC Irvine student-government voting records — Playwright web scraper + daily GitHub Actions cron</sub></p>
</td>
</tr>
</table>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Building%20Construction.png" width="24" /> Platform Work</h2>

**Multi-tenant AI operations platform** *(private repo — access on request)*

25 service backends serving 248 tools behind one proxy, powering document ingestion, meeting parsing, and knowledge synthesis. Custom 4-layer architecture enforcement — workspace guard rules + architecture tests + boot-time checks + MCP-tool rejection — that lint invariants CI-time so drift can't ship. Wiki-in-DB with primary-source audit chain (RLS-sliced tenant scoping, audit trail on writes). Tenant provisioning via canonical-writer pattern with policy-enforced sandbox namespaces. Deterministic parser fleet for meeting sources (5 platforms, 34+ agencies) with codegen-emitted migrations from a typed source registry. Semantic search via `gte-small` embeddings + HNSW (`hnswlib-node`). TypeScript + Python, Postgres 16 with RLS, Keycloak OAuth 2.1, Docker Compose orchestration.

**Personal research wiki** *(private — architecture write-up on request)*

757 atomic pages across 29 topic hubs (nursing quality improvement, mass surveillance & civil liberties, computational linguistics, atmospheric chemistry, QFT, metabolomics, parametric knowledge & model editing, others). SHA256-verified primary-source audit chain via `local_pdf:` frontmatter + a files/wiki archive; every claim is mechanically re-verifiable against a locally-archived PDF. Semantic search via `gte-small` embeddings + HNSW. Cross-domain synthesis layer — pages can link into multiple hubs (polyhierarchy).

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Globe%20Showing%20Americas.png" width="24" /> Open Source</h2>

Contributor to [**LightGBM**](https://github.com/lightgbm-org/LightGBM) — 9 PRs merged across Python type safety, C++ networking fixes, and test coverage. All nine merged Jan–Mar 2026, while the project was Microsoft-maintained; it has since moved to `lightgbm-org`.

| PR | Description |
|----|-------------|
| [#7137](https://github.com/lightgbm-org/LightGBM/pull/7137) | Fix socket timeout on POSIX systems (wrong type for `setsockopt`) |
| [#7131](https://github.com/lightgbm-org/LightGBM/pull/7131) | Fix `test_numeric_split_direction` to test all parameter combinations |
| [#7133](https://github.com/lightgbm-org/LightGBM/pull/7133) | Add test for `Booster.rollback_one_iter()` |
| [#7130](https://github.com/lightgbm-org/LightGBM/pull/7130) | Fix numpy integer cast in `plot_importance` |
| [#7115–7119](https://github.com/lightgbm-org/LightGBM/pull/7115) | Type annotations — `TypeGuard`, `Literal`, `DTypeLike`, return types for sklearn predict |

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="24" /> Statistics</h2>

<p align="center">
  <img src="https://github-stats-api-production-5042.up.railway.app/api?username=wagner-austin&theme=cyberpunk&show_icons=true&include_all_commits=true" alt="stats graph" /><br/>
  <img src="https://github-stats-api-production-5042.up.railway.app/api/top-langs?username=wagner-austin&theme=cyberpunk&layout=compact&langs_count=8&v=4" alt="languages graph" />
</p>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="24" /> Tech Stack</h2>

<p align="center">
  <img src="https://github-stats-api-production-5042.up.railway.app/api/skills?skills=Python,Rust,TypeScript,PyTorch,Transformers,FastAPI,scikitlearn,optuna,polars,PostgreSQL,Redis,Docker,Kafka,Keycloak,Anthropic,OpenAI&theme=cyberpunk" alt="tech stack" />
</p>
