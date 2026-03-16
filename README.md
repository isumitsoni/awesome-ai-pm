# Awesome AI PM [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated, opinionated list of resources for Product Managers navigating the AI era.

Not everything — just the signal. Filtered by a practicing PM who builds AI products and uses these tools daily.

**Maintained by [Sumit Soni](https://github.com/isumitsoni) · [LinkedIn](https://linkedin.com/in/isumitsoni)**

---

## Contents

- [AI PM Foundations](#-ai-pm-foundations)
- [Vibe Coding & Agentic Tools](#-vibe-coding--agentic-tools)
  - CLI Agents · UI Prototyping · Code Editors · Agentic Workflow Tools · PM Skill Libraries
- [Prompt Libraries for PMs](#-prompt-libraries-for-pms)
- [Evals & AI Quality](#-evals--ai-quality)
  - Eval Frameworks · Observability · Quality Scorecards
- [Building AI Products](#-building-ai-products)
- [LLM Economics for PMs](#-llm-economics-for-pms)
- [Learning Resources](#-learning-resources)
- [Newsletters & Communities](#-newsletters--communities)
- [Open Source PM Tools](#-open-source-pm-tools)

---

## 🧠 AI PM Foundations

Understanding what it means to be a PM in the AI era — not just using AI tools, but owning AI features end-to-end.

- **[What Is an AI Product Manager?](https://www.productcompass.pm/p/what-is-an-ai-product-manager)** — Paweł Huryn's take on the role. Solid starting point.
- **[AI PM Learning Roadmap](https://www.productcompass.pm/p/ai-product-management-learning-roadmap)** — Structured path from PM → AI PM.
- **[How to Build a RAG Chatbot](https://www.productcompass.pm/p/how-to-build-a-rag-chatbot)** — Hands-on guide for PMs who want to build, not just spec.
- **[How to Create an AI Product Strategy](https://www.productcompass.pm/p/how-to-create-an-ai-product-strategy)** — Strategy frameworks for AI products.

---

## 🛠️ Vibe Coding & Agentic Tools

The tools PMs are using to ship without a dedicated engineering team.

### CLI Agents (for building end-to-end)
- **[Claude Code](https://docs.anthropic.com/en/docs/claude-code)** — Anthropic's CLI agent. Best for structured SDLC, serious builds, and repo-level context. Skills + hooks + MCP support.
- **[OpenAI Codex](https://platform.openai.com/docs/guides/code)** — OpenAI's coding agent. Good for agentic experiments and broad exploration.
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — Google's CLI. Best for large-context analysis, research, and multimodal tasks.

### UI Prototyping (ship the interface first)
- **[v0.dev](https://v0.dev)** — Vercel's AI UI generator. Describe → get production-ready React components.
- **[Bolt.new](https://bolt.new)** — Full-stack prototyping in the browser. Clone → deploy in minutes.

### Code Editors with AI
- **[Cursor](https://cursor.com)** — AI-native code editor. Best for longer coding sessions with full codebase context.
- **[GitHub Copilot](https://github.com/features/copilot)** — In-IDE pair programmer. Good entry point if you're already in VS Code.

### Agentic Workflow Tools
- **[BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban)** ⭐ 23k — PM-friendly workflow layer for coding agents. Helps non-engineers structure agent tasks and track progress.
- **[OpenHands/OpenHands](https://github.com/OpenHands/OpenHands)** ⭐ 69k — Autonomous coding agent with broad community support and active maintenance.
- **[Aider-AI/aider](https://github.com/Aider-AI/aider)** ⭐ 42k — Terminal-based coding agent built for iterative product build loops.
- **[stackblitz-labs/bolt.diy](https://github.com/stackblitz-labs/bolt.diy)** ⭐ 19k — Open-source browser-based full-stack vibe coding. Strong for rapid founder prototyping.

### PM-Specific Skill Libraries
- **[phuryn/pm-skills](https://github.com/phuryn/pm-skills)** ⭐ 7.3k — 100+ agentic skills for Claude Code, Codex, Gemini CLI, Cursor, and Kiro. Covers discovery → strategy → GTM.

---

## 💬 Prompt Libraries for PMs

Structured prompts for real PM workflows — not generic "write me a PRD" prompts.

- **[isumitsoni/pm-prompts](https://github.com/isumitsoni/pm-prompts)** — Practical prompt library for every PM workflow: discovery, strategy, execution, AI feature specs, metrics analysis, and career. 8 categories, 40 prompts.
- **[Claude Code Skills Marketplace](https://github.com/phuryn/pm-skills)** — Slash commands and skills for Claude Code that automate PM workflows.

*Know a good prompt library? Open a PR.*

---

## 📊 Evals & AI Quality

How to define "good" for an AI feature — the PM's job, not the ML engineer's.

- **[Anthropic's Guide to Evals](https://docs.anthropic.com/en/docs/build-with-claude/develop-tests)** — How to build test suites for LLM applications. The starting point.
- **[AI Evals Course on Maven](https://bit.ly/aievals-ph)** — Practical eval design for PMs. Highly recommended.
- **[promptfoo/promptfoo](https://github.com/promptfoo/promptfoo)** ⭐ 16k — Evals + red-teaming framework PMs can use as a release gate. Runs prompt comparisons and catches regressions.
- **[confident-ai/deepeval](https://github.com/confident-ai/deepeval)** ⭐ 14k — Straightforward framework for building LLM evaluation suites. Good starting point for PM-led eval programs.
- **[Arize-ai/phoenix](https://github.com/Arize-ai/phoenix)** ⭐ 8.8k — Observability + eval workflows for production AI features. Useful for ongoing quality monitoring.
- **[truera/trulens](https://github.com/truera/trulens)** ⭐ 3.1k — Feedback and eval instrumentation for LLM systems.
- **Key PM mental model:** Define your eval criteria *before* you build. "The AI should sound like a human" is not an eval. "95% of outputs score ≥4/5 on our rubric" is.

---

## 🏗️ Building AI Products

Patterns, frameworks, and hard-won lessons from PMs who ship AI features.

- **[Vibe Coding vs. Vibe Engineering](https://www.productcompass.pm/p/vibe-coding-vs-vibe-engineering)** — Important distinction: vibe coding is prototyping; vibe engineering is production. Know which one you're doing.
- **[The PM's Guide to RAG](https://www.productcompass.pm/p/how-to-build-a-rag-chatbot)** — When to use RAG vs fine-tuning vs prompt engineering, explained for PMs.
- **[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)** — Working code examples for LLM applications. Clone → run. Great for PMs who want to understand by doing.

### Key architectural decisions PMs own
| Decision | What to consider |
|----------|-----------------|
| RAG vs fine-tuning | RAG for dynamic/private data; fine-tuning for consistent tone/style |
| Model choice | Cost/latency/capability triangle — don't default to the biggest model |
| Streaming vs batch | User experience decision first, then engineering |
| Memory architecture | Session vs persistent vs none — depends on your trust model |

---

## 💰 LLM Economics for PMs

Cost and latency are product decisions. PMs need to own them.

- **Token pricing reference:** [Anthropic pricing](https://www.anthropic.com/pricing) · [OpenAI pricing](https://openai.com/api/pricing) · [Google pricing](https://ai.google.dev/pricing)
- **Mental model:** Input tokens are cheap. Output tokens cost 3-5x more. Design your prompts accordingly.
- **Haiku/Flash for high-volume, low-stakes tasks. Sonnet/Pro for core reasoning. Opus/Ultra for one-shot complex analysis.**
- **Caching:** If your system prompt is long and reused, prompt caching can cut costs 80-90%.

---

## 📚 Learning Resources

Courses and programs worth your time.

| Resource | What it covers | Who it's for |
|----------|---------------|--------------|
| [AI PM Certification (Maven)](https://bit.ly/aipmcohort) | Full AI PM curriculum | PMs transitioning to AI PM |
| [AI Evals (Maven)](https://bit.ly/aievals-ph) | How to evaluate LLM outputs | PMs owning AI quality |
| [fast.ai](https://fast.ai) | Practical deep learning | PMs who want technical depth |
| [Anthropic Claude Code Docs](https://docs.anthropic.com/en/docs/claude-code) | Building with Claude Code | PMs who vibe code |
| [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) ⭐ 108k | Structured lesson path for AI builders | PMs new to AI development |
| [openai/openai-cookbook](https://github.com/openai/openai-cookbook) ⭐ 72k | Implementation patterns and examples | PMs prototyping AI features |
| [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) ⭐ 35k | Practical Claude workflows and examples | PMs building with Claude API |

---

## 📡 Newsletters & Communities

High signal-to-noise sources on AI PM.

- **[The Product Compass](https://www.productcompass.pm/)** — Paweł Huryn. Best AI PM newsletter. Actionable, not hype.
- **[Unwind AI](https://www.theunwindai.com/)** — Shubham Saboo. Open-source AI builder community. High technical signal.
- **[Lenny's Newsletter](https://www.lennysnewsletter.com/)** — Not AI-specific, but the best general PM source.

---

## 🔧 Open Source PM Tools

Tools PMs can use, fork, or learn from.

- **[isumitsoni/purepaste](https://github.com/isumitsoni/purepaste)** — AI text cleaner. Strips robotic LLM residue from outputs. Live at [purepaste.pro](https://purepaste.pro).
- **[Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)** — Working LLM app templates. Great reference for scoping AI features.

---

## Contributing

This list is maintained by a practicing PM — not a curator scraping the internet.

- **Open a PR** if you have a resource that genuinely belongs here
- **Quality bar:** would you recommend this to a senior PM who has 30 minutes? If yes, submit it.
- No self-promotion without real value. No courses you haven't taken.

---

*Star this repo if you find it useful. It helps other PMs find it.*
