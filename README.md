<!--
  Hi 👋 — this README is hand-written, but several blocks below are SVGs
  re-generated nightly by GitHub Actions in this repo:
    .github/workflows/metrics.yml   → metrics.svg
    .github/workflows/snake.yml     → output branch
  See the easter-egg <details> at the bottom for the why.
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img src="assets/header-dark.svg" alt="Markus Götz — Edge-AI Researcher" width="100%">
</picture>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2600&pause=600&color=7AA2F7&center=true&vCenter=true&width=720&lines=Edge-AI+Researcher+%C2%B7+M.S.+Artificial+Intelligence;Phi+Tau+Phi+%E2%80%A2+GPA+4.0%2F4.0+%E2%80%A2+2%C3%97+IEEE+first+author;Reliable+LLMs+on+constrained+devices;Currently+in+New+Taipei%2C+Taiwan+%28%E6%96%B0%E5%8C%97%E5%B8%82%2C+%E5%8F%B0%E7%81%A3%29" alt="What I do">
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=XSnelliusX&style=for-the-badge&color=7aa2f7&label=PROFILE+VIEWS" alt="Profile views">
  &nbsp;
  <a href="https://xsnelliusx.github.io"><img src="https://img.shields.io/badge/Portfolio-xsnelliusx.github.io-bb9af7?style=for-the-badge&logo=astro&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/markus-goetz-ai"><img src="https://img.shields.io/badge/LinkedIn-markus--goetz--ai-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://doi.org/10.1109/TSC.2026.3679374"><img src="https://img.shields.io/badge/IEEE_TSC-LEMON-005a9c?style=for-the-badge&logo=ieee&logoColor=white" alt="LEMON DOI"></a>
</p>

---

## `> whoami`

I'm **Markus Götz** — a German engineer who fell hard for Taiwan during a 2023 exchange and stayed for an M.S. in Artificial Intelligence at **Chang Gung University** (GPA **4.0 / 4.0**, **Phi Tau Phi** honor society — top 3% of all M.S. students nationwide).

Before the AI pivot I spent **three years inside safety-critical aviation** at Frequentis Comsoft as part of a German dual-study program (B.S. Computer Science, GPA **4.0 / 4.0**) — Java, real-time ADS-B sensor fusion, the kind of code where "it works on my machine" is not a sentence anyone is allowed to say. That mindset is the lens I bring to AI work today: **deployment realism over benchmark theatre.**

My current research lives at the **edge-AI / LLM-reliability** intersection:

- **InverseTune** — adversarial inverse synthetic training for small (≤4B) language models. Beats Gemini 2.5 Flash by **+78.8 EM** on structured-output tasks. *Accepted, IEEE CCGrid 2026.*
- **LEMON** — LLM-driven microservices orchestration & monitoring. *Published, IEEE Transactions on Services Computing, 2026.* [`DOI 10.1109/TSC.2026.3679374`](https://doi.org/10.1109/TSC.2026.3679374)
- **STIM** — systematic SLM benchmarking on edge-class hardware. *Submitted, IEEE GLOBECOM 2026.*

I'm building a permanent career in **Taiwan** and looking for roles at the seam between research and shipped systems — edge inference, on-device LLMs, observability for ML, anything that demands both the paper and the post-mortem.

---

## 📚 Featured Research

<table>
  <tr>
    <td width="34%" align="center" valign="top">
      <h3>InverseTune</h3>
      <sub><img src="https://img.shields.io/badge/IEEE_CCGrid-2026-005a9c?style=flat-square"></sub><br>
      <sub><img src="https://img.shields.io/badge/+78.8%25_EM-vs_Gemini_2.5_Flash-9ece6a?style=flat-square"></sub>
      <p align="left"><sub>Adversarial inverse synthetic-data framework that fine-tunes &le;4B SLMs to emit reliable structured JSON on edge hardware — beating a much larger commercial cloud baseline.</sub></p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>LEMON</h3>
      <sub><img src="https://img.shields.io/badge/IEEE_TSC-2026-005a9c?style=flat-square"></sub><br>
      <sub><a href="https://doi.org/10.1109/TSC.2026.3679374"><img src="https://img.shields.io/badge/DOI-10.1109%2FTSC.2026.3679374-bb9af7?style=flat-square"></a></sub>
      <p align="left"><sub>LLM-driven orchestration and deterministic-RAG monitoring layer for Kubernetes microservices, closing the loop between Prometheus telemetry and automated remediation.</sub></p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>STIM</h3>
      <sub><img src="https://img.shields.io/badge/IEEE_GLOBECOM-2026_(submitted)-6b7280?style=flat-square"></sub>
      <p align="left"><sub>Systematic Tuning &amp; Inference Metrics — benchmarking SLMs from 0.5B&nbsp;to&nbsp;8B under edge constraints: latency, memory, and structured-output stability.</sub></p>
    </td>
  </tr>
</table>

---

## 🛠 Featured Engineering

<table>
  <tr>
    <td width="34%" align="center" valign="top">
      <h3>LangFlow</h3>
      <sub><img src="https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=000"> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=fff"> <img src="https://img.shields.io/badge/Postgres-336791?style=flat-square&logo=postgresql&logoColor=fff"></sub>
      <p align="left"><sub>Full-stack AI language-learning platform. React + TypeScript front, Node/Express + PostgreSQL back, fully dockerised. Dual LLM backends — local Ollama and hosted Groq — with runtime hot-swap.</sub></p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>Chinese Character Recognition</h3>
      <sub><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=fff"> <img src="https://img.shields.io/badge/99.47%25_top--1-9ece6a?style=flat-square"></sub>
      <p align="left"><sub>4,803-class handwritten-character benchmark across 11 architectures, with an ensemble ceiling of <strong>99.47%</strong> top-1 accuracy.</sub></p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>ADS-B Anomaly Detection</h3>
      <sub><img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=fff"> <img src="https://img.shields.io/badge/safety--critical-c2410c?style=flat-square"></sub>
      <p align="left"><sub>Real-time aviation-sensor anomaly pipeline in Java, validated against <strong>140k+</strong> live ADS-B messages during my time at Frequentis Comsoft.</sub></p>
    </td>
  </tr>
</table>

---

## 🧠 Research focus, in one diagram

```mermaid
mindmap
  root((Edge-AI<br/>reliability))
    Synthetic data
      InverseTune
      Adversarial inverse generation
      Structured JSON guarantees
    Retrieval
      LEMON
      Deterministic RAG
      Qdrant + k8s telemetry
    Benchmarking
      STIM
      Latency / memory envelopes
      0.5B–8B sweep
    Observability
      Prometheus + Grafana
      LLM-in-the-loop remediation
      Aviation-grade rigor
```

---

## ⚙️ Tech I reach for

<table>
  <tr>
    <td><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=python,java,cpp,ts,js,bash" alt="Languages"></td>
  </tr>
  <tr>
    <td><b>AI / ML</b></td>
    <td valign="middle">
      <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv" alt="ML" height="48">
      <img src="https://cdn.simpleicons.org/huggingface/FFD21E" alt="Hugging Face" height="40" style="vertical-align:middle;padding:0 6px;">
      <img src="https://cdn.simpleicons.org/qdrant/DC382D" alt="Qdrant" height="40" style="vertical-align:middle;padding:0 6px;">
      <img src="https://cdn.simpleicons.org/ollama/000000" alt="Ollama" height="40" style="vertical-align:middle;padding:0 6px;">
    </td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=fastapi,spring,nodejs,postgres,mongodb" alt="Backend"></td>
  </tr>
  <tr>
    <td><b>Infra</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,kubernetes,prometheus,grafana,linux,git,githubactions,bash" alt="Infra"></td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=astro,react,vite,html,css" alt="Frontend"></td>
  </tr>
</table>

---

## 📈 GitHub at a glance

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=XSnelliusX&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&card_width=420" alt="GitHub stats">
  <img height="170" src="https://streak-stats.demolab.com?user=XSnelliusX&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub streak">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=XSnelliusX&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&hide=html,css,scss,jupyter%20notebook,tex" alt="Top languages">
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=XSnelliusX&theme=tokyo-night&hide_border=true&area=true" alt="Activity graph" width="100%">
</p>

---

## 🐍 Watching the snake eat the contribution graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/XSnelliusX/XSnelliusX/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/XSnelliusX/XSnelliusX/output/github-snake.svg">
  <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/XSnelliusX/XSnelliusX/output/github-snake.svg">
</picture>

---

## 🔭 Live metrics — regenerated nightly

<p align="center">
  <img src="metrics.svg" alt="Live GitHub metrics — generated nightly by .github/workflows/metrics.yml" width="100%">
</p>

---

## 🚧 Currently

| Studying | Researching | Building |
|---|---|---|
| Mandarin (HSK 4 prep) | GRPO + DPO for SLM alignment | This README, recursively |
| Rust for safety-critical systems | Quantisation × structured-decoding interactions | A trilingual portfolio at [xsnelliusx.github.io](https://xsnelliusx.github.io) |

---

<details>
<summary><b>🥚 Why this README has its own CI pipeline</b></summary>

<br>

A profile README that never changes is a billboard. This one is a tiny living system.

- [`.github/workflows/metrics.yml`](.github/workflows/metrics.yml) runs `lowlighter/metrics` daily at 04:13 UTC, regenerates `metrics.svg`, and commits it back to `main`. Needs a `METRICS_TOKEN` repo secret — must be a **classic** PAT with `repo, read:user, read:org` scopes (the action does not yet support fine-grained tokens for the GraphQL API).
- [`.github/workflows/snake.yml`](.github/workflows/snake.yml) runs `Platane/snk` daily at 04:27 UTC and pushes the snake SVGs to a dedicated `output` branch — the README pulls them via `raw.githubusercontent.com`, so `main` stays clean.
- The header above is two hand-written SVGs (`assets/header-dark.svg`, `assets/header-light.svg`) swapped via `<picture>` + `prefers-color-scheme`. No external dependency, no rate limit.
- The `mindmap` is GitHub-native Mermaid — no image, just markdown. Try editing it.

If you ever wonder "is this README actually maintained?", check the commit log on `metrics.svg`. The bot is the answer.

</details>

<details>
<summary><b>🇩🇪 Auf Deutsch · 🇹🇼 中文</b></summary>

<br>

🇩🇪 &nbsp; Ich bin Markus, deutscher Ingenieur mit drei Jahren in sicherheitskritischer Luftfahrt‑Software (Java) und einem laufenden M.S. in Künstlicher Intelligenz an der Chang Gung University in Taiwan. Schwerpunkt: zuverlässiger LLM‑Einsatz auf Edge‑Geräten. Ich suche eine langfristige Position in Taiwan — gerne an der Schnittstelle zwischen Forschung und Produktion.

🇹🇼 &nbsp; 我是 Markus，德國工程師，目前於長庚大學人工智慧碩士班就讀（GPA 4.0／4.0，斐陶斐榮譽會員）。研究方向為小型語言模型在邊緣裝置上的可靠部署。希望長期留在台灣，尋找研究與工程兼具的職位。

</details>

---

<p align="center">
  <sub>
    Built with <code>&lt;picture&gt;</code>, Mermaid, GitHub Actions, and a stubborn refusal to commit a static SVG. ·
    Last manual edit: <code>2026-04-22</code> ·
    The widgets refresh themselves.
  </sub>
</p>
