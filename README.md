<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1b1847,55:2b2770,100:1b1847&height=210&section=header&text=Wealthometer&fontSize=68&fontColor=ffc72c&animation=fadeIn&fontAlignY=38&desc=Backend-heavy%20full-stack%20developer%20%E2%80%A2%20Lagos%2C%20Nigeria&descAlignY=60&descSize=18&descColor=fff9e8" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=FFC72C&center=true&vCenter=true&width=900&lines=I+build+APIs+that+scale;Servers+in+C+and+Rust;Android+and+Windows+apps+you+can+install;My+own+programming+language%3A+Ometer;Dev+tools+on+npm%3A+DevDoctor)](https://wealthometer-portfolio.vercel.app/)

<a href="https://wealthometer-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Board_the_danfo-ffc72c?style=for-the-badge&labelColor=1b1847" /></a>
<a href="https://wealthometer-apps.vercel.app/"><img src="https://img.shields.io/badge/My_apps-Download-7ee0b5?style=for-the-badge&labelColor=1b1847" /></a>
<a href="mailto:wealthhajoh87@gmail.com"><img src="https://img.shields.io/badge/Open_to-Freelance_%26_full--time-ff6b4a?style=for-the-badge&labelColor=1b1847" /></a>

![Visitors](https://komarev.com/ghpvc/?username=Wealthometer&style=flat&color=ffc72c&label=profile+views)

</div>

---

## 👋 Hey, I'm Wealth

Also known as **Wealthometer**. I'm a full-stack developer in Lagos who leans towards the back end: APIs, auth, payments, real-time systems and the infrastructure under them.

I learn by building the thing itself. That's how I ended up writing **Ometer**, a programming language with its own compiler and VM, **FlowCSS**, a CSS framework, and **DevDoctor**, a pre-production check-up for JavaScript and TypeScript repos. It's also why this profile has servers in C next to GSAP landing pages.

- 💼 Most recently: Backend Developer at **Lincoln City Property** (May – Oct 2026), a mobile banking app for a microfinance business
- 🏦 Built the **Dangote Refinery IPO** subscription platform at SCM Capital: **₦1.6bn** in applications from **1,500+** investors
- 🎓 BSc Software Engineering, 2024 – now
- 📫 [wealthhajoh87@gmail.com](mailto:wealthhajoh87@gmail.com)

> Build. Learn. Ship. Repeat.

---

## 🩺 New: DevDoctor

<a href="https://www.npmjs.com/package/@wealthometer/devdoctor"><img src="https://img.shields.io/npm/v/@wealthometer/devdoctor?style=flat-square&color=ffc72c&labelColor=1b1847&label=npm" /></a>
<a href="https://www.npmjs.com/package/@wealthometer/devdoctor"><img src="https://img.shields.io/npm/dm/@wealthometer/devdoctor?style=flat-square&color=7ee0b5&labelColor=1b1847" /></a>
<img src="https://img.shields.io/badge/license-MIT-fff9e8?style=flat-square&labelColor=1b1847" />
<img src="https://img.shields.io/badge/node-20%2B-fff9e8?style=flat-square&labelColor=1b1847" />

**A check-up for your repo before production does it for you.** Eight checks for JavaScript and TypeScript projects in one install. They catch the migration that locks a table, the env var nobody documented, and the import that breaks your architecture.

```bash
npx @wealthometer/devdoctor check
```

```text
$ migraguard check
MigraGuard: migration safety (PostgreSQL)
  checked: 2   framework: prisma   high risk: 1

  ✖ Adds NOT NULL column User.role without a default
    prisma/migrations/20260301_roles/migration.sql:1
    → Fails if the table has any rows. Add a DEFAULT,
      or add it nullable, backfill, then SET NOT NULL.
  ▲ Creating an index on User blocks writes until it finishes
    → Use CREATE INDEX CONCURRENTLY.

  2 errors, 1 warning
```

| Check | What it catches |
| --- | --- |
| **RepoDoctor** | Grades tests, docs, TypeScript strictness, scripts, CI, Docker and hygiene: a 0–100 score with a fix for every point lost |
| **MigraGuard** | Dropped columns, NOT NULL without a default, indexes without CONCURRENTLY (SQL, Prisma, Drizzle, Knex) |
| **PulseAPI** | Chained API tests in YAML, with environments, JSON Schema checks and response-time limits |
| **DepScope** | Duplicate, unused, undeclared and outdated packages, heavy trees and import cycles |
| **EnvDoctor** | Compares `.env`, `.env.example`, your Zod schema, the code, Compose and CI, without printing secrets |
| **CommitSmith** | Conventional Commit suggestions and linting, changelogs, and blocks keys and `.env` files |
| **ArchWatch** | Imports that cross your declared layers, deep imports and circular imports |
| **LogLens** | Groups errors from JSON, logfmt and plain-text logs and shows when they spike |

Output as text, JSON, Markdown or SARIF, so problems show up inline on the pull request through GitHub code scanning. Zero config to start. 72 tests against real git repos and HTTP servers.

[Website](https://devdoctor-site.vercel.app) · [npm](https://www.npmjs.com/package/@wealthometer/devdoctor) · [Code](https://github.com/Wealthometer/devdoctor)

---

## 📦 Open-source packages

<table>
<tr>
<td width="50%" valign="top">

### 🛠️ Ometer

A programming language for the web, written from scratch in TypeScript: lexer, recursive-descent parser, bytecode compiler and a stack VM with a built-in web server. You can [run it in my portfolio](https://wealthometer-portfolio.vercel.app/#ometer).

<a href="https://www.npmjs.com/package/@wealthometer/ometer"><img src="https://img.shields.io/npm/v/@wealthometer/ometer?style=flat-square&color=ffc72c&labelColor=1b1847&label=npm" /></a>

[npm](https://www.npmjs.com/package/@wealthometer/ometer) · [Code](https://github.com/Wealthometer/Ometer)

</td>
<td width="50%" valign="top">

### 🎨 FlowCSS

An animation-first CSS framework in one file: 40+ animations, glassmorphism, 3D tilt, scroll reveals, ready-made components and dark mode. No dependencies, no build step.

<a href="https://www.npmjs.com/package/flowcss-style"><img src="https://img.shields.io/npm/v/flowcss-style?style=flat-square&color=ffc72c&labelColor=1b1847&label=npm" /></a>

[npm](https://www.npmjs.com/package/flowcss-style) · [Code](https://github.com/Flow-css/flowcss)

</td>
</tr>
</table>

---

## 🚀 Shipped: production-ready builds

Each one has real tests against real databases, Docker, CI, demo data and a full README.

| Project | What it is | Tests | Links |
| --- | --- | --- | --- |
| **Switchboard** | Support ticketing SaaS: hosted help center, shared inbox with live presence, internal notes, response targets and reports | 69 | [Live](https://switchboard-tau-bay.vercel.app/) · [Code](https://github.com/Wealthometer/switchboard) |
| **Stallhouse** | Multi-vendor marketplace: one cart across many stalls, one payment, each stall paid its share minus commission | Integration + Playwright | [Live](https://stallhouse.vercel.app/) · [Code](https://github.com/Wealthometer/stallhouse) |
| **Diffwise** | GitHub App that reviews pull requests with built-in checks and Claude, commenting on the exact changed lines | 99 | [Live](https://diffwise.onrender.com/) · [Code](https://github.com/Wealthometer/diffwise) |
| **Portline** | Logistics platform: courier, fleet, freight brokerage and a 3PL warehouse on one database, billed into one customer portal | 28 + 5 Playwright | [Code](https://github.com/Wealthometer/portline) |
| **Pingwell** | Self-hosted uptime monitoring: checks, incidents, team alerts and a public status page | 91 | [Live](https://pingwell-three.vercel.app/) · [Code](https://github.com/Wealthometer/Pingwell) |
| **DevDoctor** | The eight-check CLI above | 72 | [Live](https://devdoctor-site.vercel.app) · [Code](https://github.com/Wealthometer/devdoctor) |

---

## 📲 Apps you can install

Designed, built, tested and packaged myself. Each one has a page with screenshots and a download: **[wealthometer-apps.vercel.app](https://wealthometer-apps.vercel.app/)**

| App | Platform | What it does | Links |
| --- | --- | --- | --- |
| **FlowTask** | Android | Team task boards that sync live and keep working offline | [Download](https://wealthometer-apps.vercel.app/flowtask/) · [Code](https://github.com/Wealthometer/flowtask) |
| **StockPilot** | Android | Barcode-driven stock control for small shops, with profit by product | [Download](https://wealthometer-apps.vercel.app/stockpilot/) · [Code](https://github.com/Wealthometer/stockpilot) |
| **Scanly** | Android | QR and barcode scanner that checks links before you open them | [Download](https://wealthometer-apps.vercel.app/scanly/) · [Code](https://github.com/Wealthometer/scanly) |
| **Wallora** | Windows | Wallpaper playlists, schedules, per-monitor walls and live widgets | [Download](https://wealthometer-apps.vercel.app/wallora/) · [Code](https://github.com/Wealthometer/wallora) |
| **ClipNest** | Windows | Clipboard history in Rust (Tauri), searchable, with a Ctrl+Alt+V quick paste | [Download](https://wealthometer-apps.vercel.app/clipnest/) · [Code](https://github.com/Wealthometer/clipnest) |
| **Sortify** | Windows | File organiser with a drag-and-drop rule builder, full preview and undo | [Download](https://wealthometer-apps.vercel.app/sortify/) · [Code](https://github.com/Wealthometer/sortify) |
| **MediaVault** | Windows | Photo and video timeline, trip albums, look-alike finder and an AES-256 vault | [Download](https://wealthometer-apps.vercel.app/mediavault/) · [Code](https://github.com/Wealthometer/media-vault) |

---

## ⚙️ Under the hood

Frameworks hide a lot, so I rebuild the pieces underneath them.

| | Project | |
| --- | --- | --- |
| `C` | [Command-line shell](https://github.com/Wealthometer/Command-line-shell) | Bash-like shell with process management, pipes and built-ins |
| `C` | [HTTP server](https://github.com/Wealthometer/HTTP-Server) | Requests, headers and responses over raw sockets |
| `C` | [Memory allocator](https://github.com/Wealthometer/Memory-allocator) | My own `malloc` and `free`, with splitting and coalescing |
| `C` | [Huffman compressor](https://github.com/Wealthometer/File-Compression-Tool) | File compression with Huffman coding |
| `C` | [Text editor](https://github.com/Wealthometer/Text-editor) | A small terminal editor |
| `C++` | [Web server](https://github.com/Wealthometer/Web-Server) | Static files over HTTP/1.1 |
| `Rust` | [TCP/UDP chat server](https://github.com/Wealthometer/TCP-UDP-Chat-Server) | Multi-client chat on Rust's async runtime |
| `Rust` | [JWT auth server](https://github.com/Wealthometer/rust-warp-jwt-yt) | Token-based auth on Warp |
| `TS` | [Lisp interpreter](https://github.com/Wealthometer/Lisp-lntepreter) | REPL with closures and macros |
| `Go` | [Friendlier Git CLI](https://github.com/Wealthometer/Human-Friendly-Git-CLI-Tool) | Readable commits and a simpler branch flow |
| `x86` | [Assembly programs](https://github.com/Wealthometer/Assembly-1) | Arithmetic, memory and system calls, by hand |

---

## ⚡ Tech stack

**Languages**

<p align="center"><img src="https://skillicons.dev/icons?i=java,ts,js,go,rust,c,cpp,kotlin,python,php,dart,cs&perline=12" /></p>

**Back end**

<p align="center"><img src="https://skillicons.dev/icons?i=spring,nodejs,nestjs,express,fastapi,django,flask,laravel,graphql,prisma&perline=10" /></p>

**Front end & motion**

<p align="center"><img src="https://skillicons.dev/icons?i=react,nextjs,vue,angular,svelte,tailwind,threejs,vite,html,css&perline=10" /></p>
<p align="center"><img src="https://img.shields.io/badge/GSAP-0AE448?style=for-the-badge&logo=greensock&logoColor=black" /> <img src="https://img.shields.io/badge/Framer_Motion-black?style=for-the-badge&logo=framer" /></p>

**Mobile & desktop**

<p align="center"><img src="https://skillicons.dev/icons?i=react,flutter,kotlin,androidstudio,electron,tauri&perline=6" /></p>
<p align="center"><img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" /></p>

**Data, cloud & DevOps**

<p align="center"><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,supabase,firebase,docker,kubernetes,aws,gcp,azure,terraform,githubactions,linux,nginx&perline=15" /></p>

**AI**

<p align="center">
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge" />
<img src="https://img.shields.io/badge/LlamaIndex-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Ollama-black?style=for-the-badge" />
</p>

**Tools**

<p align="center"><img src="https://skillicons.dev/icons?i=git,vscode,idea,postman,figma,blender,unity,vercel&perline=8" /></p>

---

## 📊 GitHub stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Wealthometer&show_icons=true&count_private=true&hide_border=false&bg_color=1b1847&title_color=ffc72c&text_color=fff9e8&icon_color=ff6b4a&border_color=ffc72c" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Wealthometer&layout=compact&langs_count=10&bg_color=1b1847&title_color=ffc72c&text_color=fff9e8&border_color=ffc72c" />

<img src="https://streak-stats.demolab.com?user=Wealthometer&background=1b1847&border=ffc72c&ring=ffc72c&fire=ff6b4a&currStrNum=ffc72c&sideNums=fff9e8&currStrLabel=fff9e8&sideLabels=b9b4e6&dates=b9b4e6&stroke=2b2770" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Wealthometer&bg_color=1b1847&color=fff9e8&line=ffc72c&point=ff6b4a&area=true&area_color=ffc72c&hide_border=true" />

</div>

---

<div align="center">

```diff
+          ██╗      █████╗ ███╗   ███╗    ██╗  ██╗██╗███╗   ███╗
-          ██║     ██╔══██╗████╗ ████║    ██║  ██║██║████╗ ████║
!          ██║     ███████║██╔████╔██║    ███████║██║██╔████╔██║
-          ██║     ██╔══██║██║╚██╔╝██║    ██╔══██║██║██║╚██╔╝██║
+          ██║     ██║  ██║██║ ╚═╝ ██║    ██║  ██║██║██║ ╚═╝ ██║
```

</div>

## 💡 Builder mindset

Most of my projects start with one question: **"What happens if I build this?"** That question has taken me from backend APIs and payment flows to compilers, C servers, desktop apps and 3D websites. Every project teaches something new, and the next one is always loading.

---

## 📫 Connect

<div align="center">

<a href="https://wealthometer-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-wealthometer--portfolio-ffc72c?style=for-the-badge&labelColor=1b1847" /></a>
<a href="https://www.linkedin.com/in/wealth-hajoh-a5a61433a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&labelColor=1b1847" /></a>
<a href="https://x.com/wealthometer_10"><img src="https://img.shields.io/badge/X-@wealthometer__10-fff9e8?style=for-the-badge&logo=x&labelColor=1b1847" /></a>
<a href="mailto:wealthhajoh87@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_talk-ff6b4a?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1b1847" /></a>

<br><br>

![snake](https://github.com/Wealthometer/Wealthometer/blob/output/github-snake-dark.svg)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1b1847,55:2b2770,100:1b1847&height=120&section=footer" />

</div>
