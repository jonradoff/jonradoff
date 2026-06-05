# Jon Radoff · Metavert

**Product & AI Strategy Leader · 4x Founder (IPO, $200M+ Revenue) · Building the Agentic Economy · [metavert.io](https://metavert.io)**

> *"The bottleneck isn't engineering anymore. It's imagination."*

I've spent 25 years at the frontier of whatever comes next — social networks before they had a name, online games before they had a business model, live game infrastructure before it was a category. Now I'm building AI-native products and infrastructure for the agentic economy.

My companies have generated $200M+ in revenue, reached 20M+ players worldwide, and taken a product to NASDAQ. The throughline: build the infrastructure layer before the market knows it needs it.

---

## 🧠 The Intellectual Framework

Everything I build is grounded in three connected theses:

**1. Pioneer → Engineering → Creator Eras**
Every creative industry moves through three stages. The Pioneer Era: first movers build everything from scratch. The Engineering Era: frameworks and middleware make engineers more productive. The Creator Era: top-down tools finally decouple creative work from engineering — Shopify for e-commerce, Roblox for game development, YouTube for broadcasting. Software itself has now entered its Creator Era. Language models are becoming compilers for natural language, translating intent into implementation the way Fortran once translated mathematics into machine code. ([Software's Creator Era Has Arrived](https://meditations.metavert.io/p/softwares-creator-era-has-arrived))

**2. The Direct-from-Imagination Era**
In 2023 I wrote that generative AI, parallel compute, and compositional frameworks would let people "speak entire worlds into existence." The vision was about games and virtual worlds — but it turned out to be about *everything*. The same principle that collapses the distance between imagining a world and shipping it applies just as powerfully to software, to products, to companies. Smaller teams do the work that much larger teams could only do in the past. Eventually, a single person with clear vision can build what once required hundreds. ([The Direct from Imagination Era Has Begun](https://meditations.metavert.io/p/the-direct-from-imagination-era-has-begun-8a01244b75))

**3. The Full-Stack Product Manager**
When the distance between "I think we should build this" and "here's a working prototype" collapses to an afternoon, the traditional PM/engineering divide dissolves. The new archetype — the Full-Stack Product Manager — doesn't coordinate between strategy and engineering; they operate across both simultaneously, using agents as force multipliers. Four concurrent loops: **Ship** (prototype your strategy, don't just present it), **Discover** (build for AI-native visibility from day one), **Compete** (deploy agents for continuous intelligence), **Iterate** (collapse the feedback-to-action loop from sprints to hours). ([Ship Your Strategy](https://meditations.metavert.io/p/ship-your-strategy))

---

## 🛠 Open-Source (MIT-Licensed) Projects

### 🎛 VibeCtl — Command-and-control orchestration for the agentic coding era
[`github.com/jonradoff/vibectl`](https://github.com/jonradoff/vibectl)

I hit Level 6 of the agentic adoption hierarchy — running six agent-built projects simultaneously — and traditional tooling collapsed. Jira doesn't understand finite context windows. GitHub Issues doesn't know your "engineering team" is you and three Claude sessions in parallel. So I built the tool that should exist.

A self-hosted project management system designed for the Full-Stack PM workflow: AI agents doing the coding, humans directing strategy.

- `VIBECTL.md` per project — the single source of truth that agents read before every session (open issues by priority, deployment info, recent decisions, architecture summary)
- **MCP server (20+ tools)** — agents manage issues, sessions, health, and feedback without leaving Claude Code
- **AI feedback triage** — user reports convert to structured issues via Claude automatically
- **Health monitoring** — `/healthz` protocol, 24hr uptime timeline, webhook alerts on down/recovery
- **Multi-user** — GitHub OAuth, role-based permissions per project, API keys
- **CLI + Web UI** — terminal-native and visual workflows
- **Fly.io one-command deployment**

---

### 🏗 Infrastructure & Platforms

| Project | What it is | Stack | MCP |
|---|---|---|---|
| [**LightCMS**](https://github.com/jonradoff/lightcms) | AI-native CMS powering metavert.io (186 published pages). Versioned, open-source, agent-controlled. | Go + React + MongoDB | ✅ |
| [**LastSaaS**](https://github.com/jonradoff/lastsaas) | Production-ready SaaS boilerplate: multi-tenant auth, Stripe, webhooks, white-label, admin UI. Built entirely through conversation with Claude Code. MIT licensed. The "Ship Your Strategy" principle applied: prototype → production in days. | Go + React 19 + TypeScript + MongoDB | ✅ |
| [**Flipbook**](https://github.com/jonradoff/flipbook) | SEO-optimized presentation viewer (PPTX/PDF/Google Slides). Publish directly from agentic workflows. | Go + React | ✅ |
| [**markupmarkdown**](https://github.com/jonradoff/markupmarkdown) | Google-Docs-style commenting on any markdown file (paste a GitHub URL or upload). Threaded replies, @-mentions, realtime sync, AI revision via Claude. The MCP server lets agents join the same review loop as humans — read, comment, reply, resolve, revise. Live at [mumd.metavert.io](https://mumd.metavert.io). | Go + React 19 + MongoDB | ✅ |

### 🤖 Agent Systems & Research

| Project | What it is |
|---|---|
| [**Agent Almanac**](https://almanac.metavert.io) | Directory of AI agents, MCP servers, and agentic software — autonomously discovered and indexed by Agent(Agent), an AI agent that surfs the web and monitors community conversations. The agentic web discovering itself. |
| [**LLM Optimizer**](https://metavert.io/llm-optimizer) | Open-source AI visibility intelligence platform. 80% of URLs cited by LLMs don't appear in Google's top 100. LLM citation signals and SEO signals correlate only 12–18%. This tool measures how Claude, ChatGPT, Gemini, and Grok perceive your brand across five dimensions, producing a composite AI Visibility Score. MIT licensed, bring your own API keys. Discoverability is a product architecture decision, not a marketing one. |
| [**HiddenBench**](https://github.com/jonradoff/hiddenbench) | Benchmark for collective reasoning in multi-agent LLM systems. Based on the "hidden profile" paradigm from social psychology. **Results: Claude Opus 4.5 achieved 89.3% post-discussion accuracy, +76.2% information gain.** |

### ♟ Games & Applied AI

| Project | What it is | MCP |
|---|---|---|
| [**Chessmata**](https://github.com/jonradoff/chessmata) | Open-source chess platform for humans and AI agents on a unified Elo leaderboard. Maia2 agents at multiple skill levels, 3D board, MCP + API integration. Built in a weekend — direct-from-imagination in practice. | ✅ |
| [**Legends of Future Past**](https://github.com/jonradoff/lofp) | The 1992 commercial MUD I worked on as a teenager, fully resurrected from the original script files via agentic AI — every room, monster, spell, and quest line. Went viral with 1M+ views and 4K+ upvotes on r/programming. Proof that the bottleneck is creative vision, not implementation. | ❌ |

### 🎨 Creative Tools

| Project | What it is | MCP |
|---|---|---|
| [**ShaderVine**](https://github.com/jonradoff/shadervine) | WebGPU shader programming toolkit. Write WGSL with live preview, GPU compute simulations (Reaction-Diffusion, Game of Life, Fluid, Slime Mold), genetic evolution, shader morphing, and export to Unity, Unreal, Blender, and Three.js. AI is great at generating shader code from natural language but visual iteration is the bottleneck — ShaderVine bridges that with direct manipulation. | ✅ |
| [**Threelab**](https://github.com/jonradoff/threelab) | Generative 3D art platform built on Three.js. 21 built-in patterns (mathematical curves, physics simulations, GPU shaders, procedural geometry), visual node-graph editor with live code editing, multi-layer compositing, client-side evolution via mutation/crossover, and export to standalone HTML / React components / JSON. | ✅ |

---

## 📊 Research & Writing

- **[Resurrecting a 1992 MUD with Agentic AI](https://meditations.metavert.io/p/resurrecting-a-1992-mud-with-agentic)** *(Apr 2026)* — Reconstructing *Legends of Future Past* — the commercial multiplayer text game I worked on as a teenager — from the original script files via agentic AI. **1M+ views, 4K+ upvotes on r/programming.** A live demonstration of the Direct-from-Imagination thesis: the implementation bottleneck collapses; what's left is the creative vision.
- **[Ship Your Strategy](https://meditations.metavert.io/p/ship-your-strategy)** *(Mar 2026)* — The Full-Stack Product Manager: four pillars (Ship, Discover, Compete, Iterate) for the agentic era. Why your strategy deck is a liability. Why LinkedIn replaced its APM program with "Associate Product Builder."
- **[Software's Creator Era Has Arrived](https://meditations.metavert.io/p/softwares-creator-era-has-arrived)** *(Feb 2026)* — The SaaSpocalypse ($285B market cap loss) through the Pioneer → Engineering → Creator lens. The Copilot Trap. Who wins when LLMs become universal middleware.
- **[State of AI Agents & Agentic Engineering 2026](https://metavert.io/state-of-ai-agents-2026)** — 205 slides. $211B in AI venture capital. 7-layer market map. How Anthropic, OpenAI, Google, Meta, Microsoft, Amazon, Apple, and NVIDIA are placing fundamentally different bets on the stack.
- **[Market Map of the Agentic Economy](https://meditations.metavert.io)** — 7-layer framework. Reed's Law (not Metcalfe's) for agentic networks. MCP crossed 10,000 active servers with 97M monthly SDK downloads.
- **[GEO: Marketing in the Age of AI](https://meditations.metavert.io/p/llm-optimizer-marketing-in-the-age)** — Why authoritative quotations drive +41% LLM citation rates while keyword stuffing hurts −9%. The discovery layer has reset.
- **[The Direct from Imagination Era Has Begun](https://meditations.metavert.io/p/the-direct-from-imagination-era-has-begun-8a01244b75)** *(Jan 2023)* — The original thesis: generative AI, parallel compute, and compositional frameworks will let people speak entire worlds into existence.
- **[Semantic Programming](https://metavert.io/semantic-programming)** — LLM prompts as functional subroutines within traditional software architecture. Won a16z AI Tech Week 2023 Grand Prize.

---

## 🏆 Background

| Company | Role | Outcome |
|---|---|---|
| **Beamable** | Co-Founder & CPO | Live game infrastructure → acquired by Skillz (NYSE: SKLZ), Feb 2026 |
| **Disruptor Beam** | Founder & CEO | *Star Trek Timelines* (10+ yr lifespan, top 1% globally), *Game of Thrones Ascent*; $200M+ revenue, 20M+ players |
| **Eprise Corporation** | Founder & CEO | Enterprise CMS → NASDAQ IPO |
| **GamerDNA** | Founder | Social gaming network |

**Speaking:** MIT Media Lab (MAS.S61), MIT Sloan, GDC, GamesBeat Summit, Gamescom Congress

**Published:** *[Game On]([https://www.wiley.com/en-us/Game+On-p-9780470936269](https://www.amazon.com/Game-Energize-Business-Social-Media/dp/0470936266/ref=sr_1_1?crid=32XBOWH4T2VN5&dib=eyJ2IjoiMSJ9.i_riqQPKF8FqjxJ01lF14GvothbkqP4Cn0rv7PNIqQfmzLgINyRXwM3Fju32--_n.boUS4-maXNbPipseqq9iESj0XAtdDh4BGiJ_6bJieMQ&dib_tag=se&keywords=game+on+radoff&qid=1774302167&sprefix=game+on+radof%2Caps%2C164&sr=8-1))* (Wiley, 2011) — how game mechanics reshape online applications and business

**Education:** A.B., Harvard University (Extension Studies), Psychology; former Teaching Fellow with George Church (Computational Genomics, MIT/Harvard)

---

## 🔧 Stack

`Go` · `React 19` · `TypeScript` · `MongoDB Atlas` · `Fly.io` · `React Native / Expo` · `Claude Code` · `MCP` · `Stripe` · `Cloudflare` · `Vite` · `chi`

---

## 🔗 Find Me

[metavert.io](https://metavert.io) · [Substack](https://meditations.metavert.io) · [LinkedIn](https://linkedin.com/in/jonradoff) · [X / Twitter](https://x.com/jradoff) · [YouTube](https://www.youtube.com/@BuildingTheMetaverseRadoff)

---

*Building at the edge of what's next.*
