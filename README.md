<h1 align="center">Josh Garza</h1>
<p align="center">
  Full-stack engineer · AI infrastructure · San Francisco
</p>
<p align="center">
  <a href="https://joshgarza.dev">joshgarza.dev</a> ·
  <a href="https://linkedin.com/in/joshbgarza">LinkedIn</a> ·
  <a href="mailto:josh@josh-garza.com">josh@josh-garza.com</a>
</p>

---

I started as a musician (San Francisco Conservatory, 2010), pivoted into software, and attended the [Recurse Center](https://recurse.com) in 2024. I build complete systems — database to UI — and I have a particular pull toward AI infrastructure: MCP servers, agent orchestration, embedding pipelines. I also build the tools I personally use, which keeps me honest about whether they work.

---

## What I'm building

**[task-runner](https://github.com/joshgarza/task-runner)** — Linear-powered agent orchestration for Claude Code. Pulls tickets from Linear, spins up Claude agents in isolated git worktrees, opens PRs, and runs automated code reviews. The coding workflow I actually use.

**[atlas](https://github.com/joshgarza/atlas)** — Personal memory service. Append-only event log that builds a living knowledge graph. Concepts deepen with access, decay with neglect, branch on correction. Nothing deleted. Inspired by neuroscience attractor models.

**[attention_verifier](https://github.com/joshgarza/attention_verifier)** — LLM factual grounding via attention analysis. Llama 3.3 generates an answer while exposing attention over a source document; top-attended sentences become evidence for an NLI model to judge entailment or contradiction. Outputs a confidence score + HTML report with evidence highlighted by attention intensity.

**wedding-venue-finder** *(private)* — AI-powered venue discovery with a "Tinder for Venues" swipe interface. Users build aesthetic profiles via CLIP embeddings; recommendations via pgvector similarity search + PostGIS spatial queries. Actually for my wedding.

---

## Experience

**Software Engineer — UbiquityVX** *(July 2024 – present)*
Healthcare platform serving thousands of clinicians. Led frontend architecture (React/TypeScript), designed the ML data pipeline (Kinesis → Flink → PostgreSQL), managed Hasura/GraphQL backend integration. Reduced downtime incidents ~85%.

**Technical Program Manager — 0xPARC Foundation / Zupass** *(Jan – June 2024)*
ZKP application infrastructure. Built a React Proof Carrying Data Verifier visualizing 2,000+ claims in the ZKP ecosystem. Translated event requirements into ZKP technical specs across 3 international partners.

**Frontend Developer — Robert Half** *(Aug 2023 – Jan 2024)*
Built a Chrome extension that automated Adobe Experience Manager page builds — 30 minutes to under 10 seconds. Shipped 100+ AEM pages for international marketing campaigns across 16 sites.

**Assistant Instructor — Hack Reactor** *(Nov 2022 – Mar 2023)*

---

## Stack

**Strong:** TypeScript, React, Node.js, PostgreSQL, Python, Docker
**Extended:** Apache Flink, Hasura/GraphQL, AWS Kinesis, PostGIS, pgvector, ChromaDB, CLIP
**AI tooling:** Anthropic SDK, MCP protocol, Ollama, LangChain, SentenceTransformers
**Exploring:** C++ (KV stores), Go (Redis clone), Godot/GDScript

---

## Background

Conservatory → bootcamp → Robert Half → 0xPARC → Recurse Center → UbiquityVX. The through-line is building things end-to-end. Music taught me that quality of attention matters more than raw output; software taught me that shipping beats theorizing.
