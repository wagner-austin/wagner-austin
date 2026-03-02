<p align="center">
  <img src="https://github-stats-api-production-5042.up.railway.app/api/hero?name=Austin%20Wagner&subtitle=ML%20Engineer%20%7C%20Linguist%20%7C%20Open%20Source%20Contributor&lines=Language%20Science%20%40%20UC%20Irvine%20%E2%80%94%20UROP%20Researcher|Published%3A%20HSP%202026%20%26%20Tu%2B11%20(MIT)|Council%20Executive%20Assistant%2C%20City%20of%20Irvine|LightGBM%20Contributor%20%7C%20Former%20EMT&theme=cyberpunk" alt="hero" />
</p>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Briefcase.png" width="24" /> Experience</h2>

<table>
<tr>
<td><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Classical%20Building.png" width="24"/></td>
<td><b>Council Executive Assistant</b></td>
<td>City of Irvine — Councilmember Melinda Liu</td>
<td><code>Policy</code></td>
</tr>
<tr>
<td><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Microscope.png" width="24"/></td>
<td><b>Research Assistant & UROP Researcher</b></td>
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

**Plant Metabolomics & BVOCs**

- Research on **biogenic volatile organic compounds** from tree leaf and root tissues across 9 California field sites
- GC-MS data processing pipeline: [**Tree Bot**](https://github.com/wagner-austin/Tree-Bot) — peak detection, co-elution analysis, compound classification
- Interactive [**Metabolomics Dashboard**](https://austinwagner.org/metabolomics/) — Welch's t-test with FDR correction, D3.js visualizations

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" width="24" /> Featured Projects</h2>

All services live in my [**API monorepo**](https://github.com/wagner-austin/API) — 13 microservices, 21 shared libraries, FastAPI + Redis + RQ architecture.

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
<p><sub>From-scratch gradient boosting — pure stdlib Python + high-performance Rust core via PyO3</sub></p>
</td>
</tr>
</table>

<details>
<summary><b>All Services (13) & Shared Libraries (21)</b></summary>
<br>

See the full [**API monorepo**](https://github.com/wagner-austin/API) for all services and libraries including Data Bank, Music Wrapped, Transcript API, Handwriting AI, QR API, GitHub Stats, Opportunity Radar, Procart API, and 21 shared libraries covering ML, NLP, workers, persistence, and more.

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
<h3>Flock Investigation</h3>
<a href="https://austinwagner.org/flock-investigation/"><img src="https://img.shields.io/badge/Live-ff00ff?style=for-the-badge"/></a>
<p><sub>OC Flock Safety ALPR surveillance research — FOIA documents, 19 cities, 5M+ plate scans</sub></p>
</td>
</tr>
</table>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Globe%20Showing%20Americas.png" width="24" /> Open Source</h2>

Contributor to [**microsoft/LightGBM**](https://github.com/microsoft/LightGBM) — 9 PRs merged across Python type safety, C++ networking fixes, and test coverage.

| PR | Description |
|----|-------------|
| [#7137](https://github.com/microsoft/LightGBM/pull/7137) | Fix socket timeout on POSIX systems (wrong type for `setsockopt`) |
| [#7131](https://github.com/microsoft/LightGBM/pull/7131) | Fix `test_numeric_split_direction` to test all parameter combinations |
| [#7133](https://github.com/microsoft/LightGBM/pull/7133) | Add test for `Booster.rollback_one_iter()` |
| [#7130](https://github.com/microsoft/LightGBM/pull/7130) | Fix numpy integer cast in `plot_importance` |
| [#7115–7119](https://github.com/microsoft/LightGBM/pull/7115) | Type annotations — `TypeGuard`, `Literal`, `DTypeLike`, return types for sklearn predict |

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Bar%20Chart.png" width="24" /> Statistics</h2>

<p align="center">
  <img src="https://github-stats-api-production-5042.up.railway.app/api?username=wagner-austin&theme=cyberpunk&show_icons=true&include_all_commits=true" alt="stats graph" /><br/>
  <img src="https://github-stats-api-production-5042.up.railway.app/api/top-langs?username=wagner-austin&theme=cyberpunk&layout=compact&langs_count=8&v=4" alt="languages graph" />
</p>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="24" /> Tech Stack</h2>

<p align="center">
  <img src="https://github-stats-api-production-5042.up.railway.app/api/skills?skills=Python,Rust,TypeScript,FastAPI,PyTorch,scikitlearn,polars,optuna,Transformers,Docker,Redis,PostgreSQL,Hypercorn,Railway,OpenAI&theme=cyberpunk" alt="tech stack" />
</p>
