<h1 align="center">Hi, I'm Tony Sheng 👋</h1>
<p align="center">
  <b>I build AI agent workflows, evals, and learning products. Educator since 2018.</b><br/>
  <i>Learning by building and using what I make every day — staying curious, open-minded, and committed to shaping the future of education.</i>
</p>

<p align="center">
  <a href="#关于我">🇨🇳 中文简介</a> ·
  <a href="https://zturnsgo.com/">🌐 Website</a> ·
  <a href="https://notes.zturnsgo.com/">🌱 Knowledge Garden</a> ·
  <a href="https://github.com/shengdabai/Tony-Articles">✍️ 630+ Daily Essays</a> ·
  <a href="https://x.com/tonyzturns">𝕏 @tonyzturns</a> ·
  <a href="https://www.youtube.com/@zturns-zheteng">▶️ YouTube</a> ·
  <a href="https://www.linkedin.com/in/changchun-sheng-520493255">💼 LinkedIn</a>
</p>

---

## Start here

Four entry points that best show how I build with AI and design for learners:

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧪 <a href="https://github.com/shengdabai/CC-Eval">CC-Eval</a> · <a href="https://github.com/shengdabai/AgentProof">AgentProof</a></h3>
      <p><b>AI evaluation &amp; verification discipline.</b></p>
      <p><code>CC-Eval</code> benchmarks cost vs. task accuracy across Claude Code model×effort settings using 28 real failure cases (19 train / 9 held-out test) with paired autonomy/safety checks. <code>AgentProof</code> captures local snapshots and verifiable acceptance evidence for AI-assisted code changes.</p>
      <p><code>Python</code> <code>LLM Evals</code> <code>Claude Code</code> <code>QA Evidence</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/shengdabai/AI-Built-Mini-Tools">AI-Built-Mini-Tools</a> · <a href="https://shengdabai.github.io/AI-Built-Mini-Tools/">Try 58 tools live →</a></h3>
      <p><b>Repeatable AI software delivery.</b></p>
      <p>58 offline, zero-backend browser tools built with AI coding agents using a workflow that combines written specs, unit tests, and scripted browser checks — built to test and refine how far agent-assisted engineering can go.</p>
      <p><code>Spec-Driven</code> <code>Unit Tests</code> <code>Browser QA</code> <code>Offline-First</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/shengdabai/ChineseThinking">ChineseThinking</a> · <a href="https://github.com/shengdabai/College-Major-Selector">College-Major-Selector</a> (<a href="https://shengdabai.github.io/College-Major-Selector/">live →</a>)</h3>
      <p><b>Pedagogy turned into working learning tools.</b></p>
      <p><code>ChineseThinking</code> teaches Chinese framing patterns through daily micro-challenges and an AI partner rather than word-for-word translation. <code>College-Major-Selector</code> parses provincial admissions data locally in the browser with an optional AI major advisor.</p>
      <p><code>TypeScript</code> <code>AI Tutor</code> <code>EdTech</code> <code>Zero-Backend</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>✍️ <a href="https://github.com/shengdabai/Tony-Articles">Tony-Articles</a> (<a href="https://notes.zturnsgo.com/">630+ essays →</a>) · <a href="https://github.com/shengdabai/AI-Research-Gallery">AI-Research-Gallery</a> (<a href="https://shengdabai.github.io/AI-Research-Gallery/">166 pages →</a>)</h3>
      <p><b>Thinking and learning in public, every day.</b></p>
      <p>630+ bilingual (中文/EN) deep-dives on learning, growth, and AI published via a 13-step writing pipeline, alongside 166 self-contained interactive HTML research explainers curated from ~1,600 notes after privacy passes.</p>
      <p><code>Bilingual</code> <code>Python Pipeline</code> <code>Interactive HTML</code> <code>Quartz</code></p>
    </td>
  </tr>
</table>

---

## How I build · Learning by building

I don't study AI from the sidelines. **I use AI coding agents (Claude Code, Codex) and LLMs (Claude, GPT, Gemini) in my work every day, and I learn by building products I can actually use and test.**

When a workflow fails or a model surprises me, I capture the exact case, revise the workflow or add a test, and verify the fix on the next build. Staying curious and open-minded means treating every shipped tool as both a product and a live experiment.

```mermaid
flowchart LR
    A[Use AI in daily work] --> B[Capture failure or surprise]
    B --> C[Revise skill, rubric, or test]
    C --> D[Verify on next product build]
    D --> A
```

**What this looks like in practice:**
- In [`CC-Eval`](https://github.com/shengdabai/CC-Eval), real frustrations from daily coding sessions became 28 test cases split into `train` (19) and held-out `test` (9) — pairing `no-pause` against `must-ask` so optimizing autonomy never trains recklessness, backed by budget caps, model-identity checks, and offline regression tests.
- In [`Tony-Claude-Code-Skills`](https://github.com/shengdabai/Tony-Claude-Code-Skills), recurring workflows accumulate into 320+ curated and custom skills, 9 agents, 39 commands, and a Codex bridge — continuously refined through daily shipping across 75+ public repos.

### Working principles

- **Ship daily, learn continuously.** Something concrete lands every day — a tool, a fix, an eval case, an essay. Streaks are a by-product; compounding skill is the goal.
- **One problem, one branch, one PR.** Small commits; tests and docs travel with the code; merged cleanly.
- **AI as co-worker, human as owner.** Claude Code, Codex, and Gemini draft, review, and cross-check each other; I define the acceptance bar and own what ships.
- **Teach what I build, build what I teach.** Classroom friction shapes what gets built; every product tests my assumptions about learning.
- **Learn in public, publish clean.** Workflows, datasets, and notes are open; personal data is stripped before anything leaves my machine.
- **Read the graph honestly.** Many commits are co-authored with AI coding agents (see `Co-Authored-By` trailers) and land via one-branch, one-PR merges. Judge the work by the shipped repos, test suites, and live demos above.

---

## About me

I started teaching in **2018** and have spent the years since working across almost every corner of education — bilingual classrooms, curriculum R&amp;D, K–12 international student recruitment, content and community operations, and education sales. Trained in engineering (**BEng**, Hefei University of Technology) and school leadership (**MA in Educational Leadership &amp; Administration**, The University of Manchester), I now bring those worlds together at **Z Turns**.

- **Bilingual Teaching &amp; Pedagogy** — Taught English and contributed to curriculum development and teacher training at New Oriental (~3,000 K–12 learners, #1 in department), built an independent online language studio, and currently deliver corporate Mandarin coaching at Learnlight (**400+ hours, 5.0/5.0 rating** for professionals from JPMorgan Chase, ExxonMobil, the World Bank Group, Novartis, and PUIG).
- **International Education &amp; Study Abroad** — Coordinated K–12 international recruitment partnerships, webinars, and China/Asia go-to-market initiatives connecting students with Canadian and U.S. schools at ApplyBoard.
- **Self-Media, Community Operations &amp; Commercial Growth** — Managed content, video-platform, and community operations across a **1M+ combined follower** network (mentoring **300+ creators** and leading delivery of a RMB 3M private advisory-board program); generated RMB 600K quarterly course sales at New Oriental and advised **20+ creators and small businesses** on positioning, pricing, and WeChat-ecosystem growth.
- **Long-Term Mission** — Inspired by [@xiaolai](https://github.com/xiaolai)'s practice of self-teaching as a craft and being a producer rather than a passive consumer, I build with an open, curious mindset toward what comes next. **My long-term commitment is to stay in education and build better ways for learners to practice, get meaningful feedback, and see their own progress — helping shape the future of learning in the AI era.**

<a id="关于我"></a>

### 关于我

我从 **2018 年**开始从事教学，八年多来一直围绕教育展开实践——走过中英文一线教学与教研、K-12 海外留学招生、百万级自媒体与社群运营、课程销售与独立顾问。本科毕业于**合肥工业大学（211）工程管理专业**，硕士毕业于**英国曼彻斯特大学教育领导力与管理专业（MA）**，如今在 **Z Turns** 把一线教育经验与 AI 工程实践结合在一起。

对我而言，学习 AI 最好的方式不是旁观，而是**在每天高频使用中不断迭代，通过做出真实可用、可测的产品继续学习**。我始终保持好奇心和开放心态，面向未来持续打磨工具与认知：

- **AI 实战与「做中学」飞轮（Z Turns）**：每天使用 Claude Code、Codex、MCP 与主流大模型做真实开发，把踩过的坑沉淀为评测集（`CC-Eval`）、验收证据工具（`AgentProof`）、精选与自研结合的 Skills 工具箱（`Tony-Claude-Code-Skills`），已公开发布 **75+ 个开源仓库**、**630+ 篇日更中英双语长文**与 **20 册 HSK 分级主题教材**。
- **中英文教学与教研**：2018 年起步于新东方（教授约 3,000 名 K-12 学员、参与教研与师训、部门业绩第一），后独立创办在线语言工作室；现为 Learnlight 远程企业中文培训师（累计授课 **400+ 小时、评分 5.0/5.0**，服务来自 JPMorgan Chase、ExxonMobil、世界银行集团、Novartis、PUIG 等跨国机构人士）。
- **海外留学与国际教育**：在 ApplyBoard 协调中国及亚洲市场的 K-12 国际招生合作、双语研讨会与市场推广，对接加拿大与美国院校。
- **自媒体、社群运营与商业销售**：操盘过合计**百万级粉丝**内容矩阵与社群运营，辅导 **300+ 创作者**，主导交付 300 万元私董会项目；具备单季 60 万课程销售与 20+ 小微企业/创作者增长咨询经验。
- **面向未来的长期愿景**：受 [@xiaolai](https://github.com/xiaolai)「自学是门手艺、在 AI 时代做生产者」的启发，我选择长期扎根教育——**希望用持续进化的 AI 工具与教学设计，让学习者更容易练习、获得高质量反馈并看见自己的进步，参与改变未来教育。**

### Credentials &amp; background · 教育背景与专业资质

| Dimension | Verified Credentials &amp; Track Record |
|---|---|
| **Degrees · 学历** | **MA, Educational Leadership &amp; Administration** — The University of Manchester (2021–2023)<br/>**BEng, Engineering Management** — Hefei University of Technology, Project 211 (2014–2018) |
| **Teaching · 教学资质** | **Trinity DipTESOL** (Level 7, Ofqual RQF, Trinity College London) · **Cambridge CELTA** · **Cambridge TKT** (Modules 1–3, YL, CLIL) · **China High School English Teacher Qualification** |
| **Growth · 运营与营销** | **China Internet Senior Marketer** · 1M+ combined follower network ops · 300+ creators mentored · K–12 international study-abroad recruitment (ApplyBoard) · Education sales &amp; consulting |
| **Languages · 语言** | Mandarin Chinese (Native) · English (Professional Working Proficiency) |

---

## Full open-source index

75+ public repos across AI workflows, education products, and daily knowledge output. Click any group to browse the curated index:

<details>
<summary><b>1 · AI workflows, evals &amp; builder tools (21 repos)</b></summary>
<br/>

| Project | Highlights |
|---|---|
| [CC-Eval](https://github.com/shengdabai/CC-Eval) | 28-case (19 train / 9 test) eval suite measuring cost vs. task accuracy across Claude Code model×effort settings |
| [AgentProof](https://github.com/shengdabai/AgentProof) | Local-first snapshot, acceptance check &amp; verifiable evidence pack for AI-assisted code changes |
| [Tony-Claude-Code-Skills](https://github.com/shengdabai/Tony-Claude-Code-Skills) | 320+ curated &amp; custom Claude Code skills, 9 agents, 39 commands, sanitized configs &amp; a Codex bridge |
| [AI-Built-Mini-Tools](https://github.com/shengdabai/AI-Built-Mini-Tools) · [live](https://shengdabai.github.io/AI-Built-Mini-Tools/) | 58 offline browser tools built with AI agents using written specs, unit tests &amp; scripted browser checks |
| [Claude-Code-Plugins](https://github.com/shengdabai/Claude-Code-Plugins) | Daily Claude Code plugins: devflow process guard, decision tracker, secret-shield &amp; task-ledger band |
| [Agent-Toolforge](https://github.com/shengdabai/Agent-Toolforge) | Ten building blocks for AI agents: 5 MCP servers and 5 Claude / Codex skills |
| [Tony-Skill](https://github.com/shengdabai/Tony-Skill) | Agent Skill distilling a person's cognitive OS (pedagogy × AI workflows × cross-domain thinking) |
| [Idea-Trio-Devtools](https://github.com/shengdabai/Idea-Trio-Devtools) · [Whylog](https://github.com/shengdabai/Whylog) | `promptdiff` (snapshot/diff AI configs), `SkillLint`, `CardStack` · local-first decision log feeding review lessons forward |
| [IdeaForge](https://github.com/shengdabai/IdeaForge) | Turn any idea, link, or image into a self-contained visual knowledge page locally (Codex / Claude / Ollama) |
| [AI-Team](https://github.com/shengdabai/AI-Team) · [live](https://ai-team.pages.dev) | Multi-model playground: @-mention GPT, Claude, Gemini, Grok, DeepSeek &amp; 5 Chinese models to compare or debate |
| [GH-Audit](https://github.com/shengdabai/GH-Audit) | One-command redaction-first security audit for GitHub repos &amp; orgs: secrets, PII, vulnerable deps, IaC &amp; governance |
| [Insidebar-AI](https://github.com/shengdabai/Insidebar-AI) | All your AI chatbots in one browser sidebar — no API keys, privacy-first, open source |
| [FreeSpace](https://github.com/shengdabai/FreeSpace) | Smart tab manager: one keystroke files open tabs across windows into auto-classified, searchable sessions |
| [Feishu-Lark-To-Obsidian](https://github.com/shengdabai/Feishu-Lark-To-Obsidian) | One-click &amp; batch export of Feishu/Lark docs to clean Obsidian-ready Markdown (extension + Playwright CLI) |
| [AI-Learning-Step-By-Step](https://github.com/shengdabai/AI-Learning-Step-By-Step) | Bilingual learning path: from AI tools, to agents, to an AI startup |
| [Dev-Guides-Collection](https://github.com/shengdabai/Dev-Guides-Collection) · [Everything-Claude-Code](https://github.com/shengdabai/Everything-Claude-Code) | Copy-paste-ready engineering guides · curated Claude Code agents, rules, hooks &amp; MCP toolkit |
| [QuickTranslate](https://github.com/shengdabai/QuickTranslate) · [Content-Creator-Hub](https://github.com/shengdabai/Content-Creator-Hub) · [AI-Video-Workflow](https://github.com/shengdabai/AI-Video-Workflow) ([site](https://shengdabai.github.io/AI-Video-Workflow/)) | Always-on-top Rust/Tauri translator · terminal X/YouTube publishing tools · end-to-end AI video automation pipeline |

</details>

<details>
<summary><b>2 · Education &amp; learning products (18 repos)</b></summary>
<br/>

| Project | Highlights |
|---|---|
| [ChineseThinking](https://github.com/shengdabai/ChineseThinking) | AI Mandarin platform teaching framing &amp; thinking patterns via daily micro-challenges + AI partner (TypeScript) |
| [HSK-Prep-Platform](https://github.com/shengdabai/HSK-Prep-Platform) | HSK exam-prep web app: leveled content, timed mock exams, spaced-repetition mistake book (Next.js 16 + Supabase + Stripe integration) |
| [Chinese-Mission](https://github.com/shengdabai/Chinese-Mission) | Learn Chinese by completing real-world missions via AI conversation with pinyin, gloss &amp; voice |
| [Chinese-Learning](https://github.com/shengdabai/Chinese-Learning) | AI Mandarin tutor: topic vocabulary, voice conversation, and graded session reports in 24 native languages |
| [LinguaLens](https://github.com/shengdabai/LinguaLens) | AI Chinese-learning toolkit: immersive reading, shadowing, translation &amp; fluency coaching (BYO key) |
| [Chinese-Textbook-Generator](https://github.com/shengdabai/Chinese-Textbook-Generator) | Multi-LLM pipeline for generating HSK-aligned, print-ready themed textbooks (20 volumes built &amp; rubric-reviewed) |
| [Chinese-Character-Content](https://github.com/shengdabai/Chinese-Character-Content) · [browse](https://shengdabai.github.io/Chinese-Character-Content/) | Open Chinese character datasets for English speakers — 3,500/7,000 lists + corpus frequency &amp; HSK bands (CSV/JSON) |
| [Teaching-Notes-Sidebar](https://github.com/shengdabai/Teaching-Notes-Sidebar) · [Browser-Extensions](https://github.com/shengdabai/Browser-Extensions) | Chrome MV3 extensions turning Chinese text into leveled teaching notes, pinyin &amp; splitters across 9 AI providers |
| [TeachLoop-Workbench](https://github.com/shengdabai/TeachLoop-Workbench) | Offline static learning workbench turning any topic into immediate recall + 7-day consolidation loop |
| [College-Major-Selector](https://github.com/shengdabai/College-Major-Selector) ([live](https://shengdabai.github.io/College-Major-Selector/)) · Gaokao suite ([Review](https://github.com/shengdabai/Gaokao-Review), [600](https://github.com/shengdabai/Gaokao-600), [Assistant](https://github.com/shengdabai/Gaokao-Assistant), [Materials](https://github.com/shengdabai/Gaokao-Study-Materials)) | Browser-based Gaokao planning with local admissions parsing + optional AI advisor, plus Socratic tutoring &amp; essay grading tools |
| [Futurecraft](https://github.com/shengdabai/Futurecraft) · [Future-Path-Quest-Open](https://github.com/shengdabai/Future-Path-Quest-Open) · [VoiceReaderApp](https://github.com/shengdabai/VoiceReaderApp) | Career exploration RPG · gamified future-path simulator · trilingual iOS PDF/EPUB reader with AI voice cloning (Swift) |

</details>

<details>
<summary><b>3 · Daily production, digital garden &amp; utilities (5 repos)</b></summary>
<br/>

| Project | Highlights |
|---|---|
| [Tony-Articles](https://github.com/shengdabai/Tony-Articles) · [read online](https://notes.zturnsgo.com/) | 630+ bilingual deep-dive essays on learning, growth &amp; AI, published daily via a 13-step writing pipeline |
| [AI-Research-Gallery](https://github.com/shengdabai/AI-Research-Gallery) · [browse](https://shengdabai.github.io/AI-Research-Gallery/) | 166 self-contained HTML research pages &amp; visualizations curated from ~1,600 notes after privacy passes |
| [Tony-Knowledge-Garden](https://github.com/shengdabai/Tony-Knowledge-Garden) · [visit](https://notes.zturnsgo.com/) | Public Quartz digital garden: bilingual notes on AI, Chinese teaching &amp; learning science |
| [Small-Yet-Smart-Programs](https://github.com/shengdabai/Small-Yet-Smart-Programs) | Daily scout for small, profitable, replicable software ideas scored on a 7-dimension anti-hype rubric |
| [Apple-Refurb-Watch](https://github.com/shengdabai/Apple-Refurb-Watch) | Utility that notifies you when Apple's refurbished store lists new Macs |

</details>

<sub><i>Apps containing payment records or learner data remain private on purpose.</i></sub>

---

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=shengdabai&show_icons=true&hide_border=true&count_private=true&theme=github_dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=shengdabai&show_icons=true&hide_border=true&count_private=true&theme=default" />
    <img src="https://github-readme-stats.vercel.app/api?username=shengdabai&show_icons=true&hide_border=true&count_private=true&theme=default" alt="GitHub stats" height="165" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=shengdabai&layout=compact&hide_border=true&langs_count=6&theme=github_dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=shengdabai&layout=compact&hide_border=true&langs_count=6" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shengdabai&layout=compact&hide_border=true&langs_count=6" alt="Top languages" height="165" />
  </picture>
</p>
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=shengdabai&hide_border=true&theme=github-dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=shengdabai&hide_border=true" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=shengdabai&hide_border=true" alt="Contribution streak" height="165" />
  </picture>
</p>

---

## Let's connect

If you are working on **AI agent workflows &amp; evals**, building **the future of education**, or looking for a collaborator who bridges real classrooms and working software — open an issue on any repo above, or say hi on [X](https://x.com/tonyzturns) / [LinkedIn](https://www.linkedin.com/in/changchun-sheng-520493255). I reply in English or 中文.
