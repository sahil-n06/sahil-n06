<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:05070F,55:0B1F4B,100:1E3A8A&height=230&section=header&text=Sahil%20Nawaz&fontSize=64&fontColor=FFFFFF&animation=twinkling&fontAlignY=38&desc=Software%20Development%20Engineer%20%C2%B7%20I%20build%20things%20that%20ship&descAlignY=60&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&width=780&lines=Hey+there!+I'm+Sahil+%F0%9F%91%8B;SDE+I+%40+Nikah+Forever+%C2%B7+Delhi%2C+India;I+made+an+API+go+from+6.8s+%E2%86%92+240ms+%E2%9A%A1;Building+AI+agents+that+check+prod+before+they+panic;5k%2B+devs+use+my+VS+Code+extensions+%F0%9F%A7%A9;Open+to+SDE+roles+%C2%B7+India+%2F+Remote" />

<br/>

<a href="https://sahilnawaz.vercel.app"><img src="https://img.shields.io/badge/Portfolio-sahilnawaz.vercel.app-0B1F4B?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://linkedin.com/in/sahil-nawaz"><img src="https://img.shields.io/badge/LinkedIn-Let's%20talk-0B1F4B?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://sahilnawaz.vercel.app/Sahil_Nawaz_Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-0B1F4B?style=for-the-badge&logo=readthedocs&logoColor=white"/></a>
<a href="mailto:mdsahil622004@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-0B1F4B?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://leetcode.com/u/sahil060204/"><img src="https://img.shields.io/badge/LeetCode-300%2B%20solved-0B1F4B?style=for-the-badge&logo=leetcode&logoColor=FFA116"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=sahil-n06&style=flat-square&color=1E3A8A&label=you+are+visitor+no." />

</div>

<br/>

<table>
<tr>
<td width="58%" valign="top">

### <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28"/> `$ cat sahil.json`

```json
{
  "name": "Sahil Nawaz",
  "role": "SDE I @ Nikah Forever",
  "based_in": "Delhi, India 🇮🇳",
  "ships": [
    "web platforms",
    "AI agents",
    "payments infra",
    "developer tools"
  ],
  "building_now": "Coco — an AI triage agent for Slack + Jira",
  "plot_twist": "intern → full-time SDE in 6 months",
  "fuel": ["chai", "EXPLAIN ANALYZE", "lofi"],
  "open_to": "SDE roles · India / Remote"
}
```

</td>
<td width="42%" valign="top" align="center">

<img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="300"/>

```text
sahil.status
─────────────────────────────
● ONLINE   shipping to prod
▸ stack    TS · React · Node
▸ db       Postgres · MySQL
▸ ai       GPT-4o · LLM agents
▸ edge     Cloudflare Workers
▸ chai     ██████████░  92%
```

</td>
</tr>
</table>

<br/>

## 📉 `git diff production` — things I made better

```diff
- API response time ........... 6–7 s
+ API response time ........... 200–300 ms    # query rewrites + composite indexes + app cache

- Feedback triage ............. read every call, review & ticket by hand
+ Feedback triage ............. 5-stage AI pipeline, −85% manual effort

- LLM first token (NEXUS) ..... cold model load
+ LLM first token (NEXUS) ..... ~2.5 s faster  # VRAM-aware model pre-warm at startup

- SEO pages ................... hitting origin on every request
+ SEO pages ................... 38,718 warmed at the edge, 98%+ success, zero servers

- Payments .................... one gateway, fingers crossed
+ Payments .................... Razorpay · Cashfree · PayGlocal, picked live by success rate
```

<br/>

## 🕹️ `git log --author="sahil" --graph`

```text
* 7f3c2a1 (HEAD -> main, tag: SDE-I)                         Jun 2026 · Nikah Forever
│   feat: AI hiring platform — GPT-4o screening + voice interviews in 12 Indian languages
│   feat: Coco — AI agent that verifies bugs against prod before filing Jira tickets
│   feat: real-time chat moderation — flagged messages arrive blurred, tap to reveal
│   feat: multi-gateway payments that choose the gateway by country + success rate
│   feat: rebuilt web.nikahforever.com from scratch on Next.js 16 + React 19
│   perf: high-traffic API 6–7s → 200–300ms
│
* 3b9e0d4 (tag: intern → full-time 🎉)                         Dec 2025 · Nikah Forever
│   feat: GoSalam.com — travel site fully run from an admin portal, zero code changes
│   feat: CRM from scratch — 200+ live enquiries in the first two weeks
│   feat: feedback intelligence platform — calls + reviews + tickets → ranked pain points
│
* 9a1d6e8                                                    Jun 2025 · Tussle Digital
│   feat: AI chat API with short + long-term memory (Azure OpenAI + embeddings)
│   feat: Kanban / Gantt / Workload views with WebSocket sync — 30+ tickets a day
│
* 0c4f7b2 (root)                                             Nov 2024 · Freelance
    feat: Shopify store — SEO +35%, load time −28%, organic traffic +40% in month one
```

<br/>

## 🚀 Things I've shipped

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [NEXUS](https://github.com/sahil-n06/NEXUS)
**Sovereign AI desktop app** — your LLMs, your hardware, zero pings home.

<img src="https://skillicons.dev/icons?i=electron,react,ts,sqlite&perline=4" height="32"/>

<details>
<summary><b>🔍 peek under the hood</b></summary>
<br/>

- Probes VRAM at startup and **pre-warms the likely model** → first token ~2.5s faster
- One interface across **llama.cpp, Ollama and cloud** models
- **MCP integration** for real-time web search, no external tracking
- Built with Electron, React, TypeScript, node-llama-cpp, SQLite

</details>

</td>
<td width="50%" valign="top">

### 🧩 [Nudge Dev Suite](https://open-vsx.org/namespace/nudge-dev)
**Three VS Code extensions**, 5k+ downloads and counting.

<a href="https://open-vsx.org/extension/nudge-dev/nudge-dev"><img src="https://img.shields.io/open-vsx/dt/nudge-dev/nudge-dev?label=Nudge%20Dev&color=0B1F4B&style=flat-square"/></a>
<a href="https://open-vsx.org/extension/nudge-dev/nudge-junior"><img src="https://img.shields.io/open-vsx/dt/nudge-dev/nudge-junior?label=Nudge%20Junior&color=0B1F4B&style=flat-square"/></a>
<a href="https://open-vsx.org/extension/nudge-dev/branchmap-file-tree"><img src="https://img.shields.io/open-vsx/dt/nudge-dev/branchmap-file-tree?label=BranchMap&color=0B1F4B&style=flat-square"/></a>

<details>
<summary><b>🔍 peek under the hood</b></summary>
<br/>

- **Nudge Dev** — six AI personas *debate your plan* before you write a line, plus a Guard Loop before and after every task (DeepSeek R1 · Groq · Gemini)
- **Nudge Junior** — lightweight in-editor AI nudges
- **BranchMap File Tree** — clean, copy-ready project trees for docs, PRs and prompts

</details>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ [AI Hiring Platform](https://career.nikahforever.com)
**Resume → MCQs → code → a real voice interview**, all run by AI.

<img src="https://skillicons.dev/icons?i=nextjs,ts,postgres,prisma&perline=4" height="32"/>

<details>
<summary><b>🔍 peek under the hood</b></summary>
<br/>

- GPT-4o resume screening, MCQ + subjective rounds, optional coding challenge
- **15–25 min AI voice interviews** in **12 Indian languages** (ElevenLabs + Sarvam AI)
- Anti-cheat with **GPT-4o Vision** and typing-speed (WPM) analysis

</details>

</td>
<td width="50%" valign="top">

### 📨 [MailSetu](https://mailssetu.in)
**Email + SMS delivery SaaS** — like a homegrown SendGrid.

<img src="https://skillicons.dev/icons?i=nextjs,nodejs,postgres,redis&perline=4" height="32"/>

<details>
<summary><b>🔍 peek under the hood</b></summary>
<br/>

- REST API with **sandbox and live** modes
- SPF / DKIM / DMARC domain verification, **HMAC-signed webhooks**
- BullMQ async workers with retries on a self-hosted Stalwart SMTP server
- Razorpay billing with GST invoices

</details>

</td>
</tr>
</table>

<details>
<summary><b>📦 click for more builds (there are a lot)</b></summary>
<br/>

| Build | What it does |
|---|---|
| 🤖 **Coco** | AI triage agent in Slack + Jira; verifies escalations against read-only prod MySQL and the codebase, dedupes by error signature |
| 💬 **Chat moderation** | ML-scored messages; flagged ones arrive blurred with tap-to-reveal; fails open on timeout |
| 🌍 **Edge cache warmer** | GitHub Actions + regional proxies warming 38,718 pages across US / DE / IN |
| 📊 **Feedback Intelligence Engine** | 5-stage AI pipeline turning calls, reviews and tickets into ranked product pain points |
| 💍 **[web.nikahforever.com](https://web.nikahforever.com)** | Next.js 16 rebuild with OTP auth, 4-step identity check, real-time chat, subscriptions |
| 📚 **[FlutterEngine.com](https://www.flutterengine.com)** | Flutter docs + community platform; I owned frontend, design system and deploys |
| 🍔 **[Lazy Foody](https://github.com/sahil-n06/lazy-foody)** | MERN food pre-ordering that cut campus queue time from 30 to 15 minutes |
| 🧘 **[Focus extension](https://github.com/sahil-n06/distraction-free-browser-extension)** | Locks your screen for 20s on every tab switch. Brutal. Effective. |

</details>

<br/>

## 🔥 When prod is on fire

<table>
<tr>
<td width="45%" align="center">

<img src="https://media.giphy.com/media/13GIgrGdslD9oQ/giphy.gif" width="280"/>

<sub>me, mid-incident</sub>

</td>
<td width="55%" valign="top">

<details>
<summary><b>👀 click if you dare — a true(ish) story</b></summary>
<br/>

```text
14:02  slack: "app feels slow 🥲"
14:03  me: it's probably fine
14:05  EXPLAIN ANALYZE → full table scan 💀
14:09  me: it is not fine
14:20  query rewrite + composite index
14:26  app-level cache for the hot path
14:31  6.8s → 240ms ⚡
14:32  me: told you it was fine 😌
```

</details>

**My loop:**
`understand → build → break → debug → ship → repeat`

</td>
</tr>
</table>

<br/>

## 🧰 Daily loadout

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=ts,js,python,java,c,html,css,bash" />

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,electron,vite" />

**Backend & data**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,postgres,mysql,mongodb,redis,firebase,supabase,prisma,sqlite" />

**Cloud & tooling**<br/>
<img src="https://skillicons.dev/icons?i=cloudflare,workers,githubactions,vercel,git,vscode,linux" />

**AI**<br/>
<img src="https://img.shields.io/badge/OpenAI-0B1F4B?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure%20OpenAI-0B1F4B?style=flat-square&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/ElevenLabs-0B1F4B?style=flat-square&logo=elevenlabs&logoColor=white"/>
<img src="https://img.shields.io/badge/Sarvam%20AI-0B1F4B?style=flat-square"/>
<img src="https://img.shields.io/badge/MCP-0B1F4B?style=flat-square&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Groq-0B1F4B?style=flat-square"/>
<img src="https://img.shields.io/badge/Gemini-0B1F4B?style=flat-square&logo=googlegemini&logoColor=white"/>

</div>

<br/>

## 📊 The numbers

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=sahil-n06&show_icons=true&count_private=true&hide_border=true&rank_icon=github&bg_color=05070F&title_color=7AA2F7&icon_color=7AA2F7&text_color=E5E7EB&ring_color=1E3A8A" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahil-n06&layout=compact&langs_count=8&hide_border=true&bg_color=05070F&title_color=7AA2F7&text_color=E5E7EB" />

<img src="https://streak-stats.demolab.com?user=sahil-n06&hide_border=true&background=05070F&ring=7AA2F7&fire=7AA2F7&currStreakLabel=7AA2F7&sideLabels=E5E7EB&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=9CA3AF&stroke=1E3A8A" />

<a href="https://leetcode.com/u/sahil060204/"><img src="https://leetcard.jacoblin.cool/sahil060204?theme=dark&font=Fira%20Code&ext=heatmap&border=0&radius=10" /></a>

</div>

<br/>

## 🐍 Watch the snake eat my commits

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sahil-n06/sahil-n06/output/github-snake-dark.svg" />
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/sahil-n06/sahil-n06/output/github-snake.svg" />
</picture>
</div>

<br/>

## 🏆 Wins

- 🧩 **5k+ downloads** across 3 VS Code extensions on Open VSX
- 🎉 **Intern → full-time SDE** at Nikah Forever
- 🐛 **Bug Bounty Winner** — MSIT
- 🥇 **Top 5 Finalist** — MSIT Hackathon
- 🎓 **B.Tech CSE, First Division** · **CGPA 8.90** in IIT Guwahati's AI/ML program

<br/>

<div align="center">

## 📬 Let's build something

<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="220"/>

**Hiring? Got a wild idea? Want to contribute to [NEXUS](https://github.com/sahil-n06/NEXUS)?**<br/>
My inbox is open → **[mdsahil622004@gmail.com](mailto:mdsahil622004@gmail.com)**

<sub>`chai → code → debug → ship → repeat`</sub>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:1E3A8A,50:0B1F4B,100:05070F&height=120&section=footer" width="100%"/>

</div>
