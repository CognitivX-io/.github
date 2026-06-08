<div align="center">

<img src="https://cognitivx.io/og-cognitivx.png" alt="CognitiveX — it's all about you being remembered" width="640" />

<h1>CognitiveX</h1>

<h3><em>It's all about you being remembered.</em></h3>

<p>
Persistent memory and a cognition layer for AI — so the tools you already use
remember you across every session, every agent, and every device.
</p>

<p>
<a href="https://cognitivx.io"><b>Website</b></a> &nbsp;·&nbsp;
<a href="https://icog.app"><b>Open iCog</b></a> &nbsp;·&nbsp;
<a href="https://docs.cognitivx.io"><b>Docs</b></a> &nbsp;·&nbsp;
<a href="https://x.com/CognitivX"><b>X / Twitter</b></a>
</p>

</div>

---

## Why we exist

A stateless LLM forgets you the moment a conversation ends. You re-explain your
context, your preferences, and your history every single time. CognitiveX closes
that gap: we build the **memory and cognition layer** that sits underneath your
AI tools, so they accumulate a real, evolving understanding of you.

> **LLMs are infrastructure, not the product.** The intelligence lives in the
> memory architecture, the retrieval algorithms, and the relationship graph —
> the model is just the text-rendering primitive at the end of a structured
> pipeline. Swap one model for another and quality changes; behavior doesn't.

## What we build

### 🧠 iCog — your personal memory layer
MCP-native, **personal** memory that plugs into the AI tools you already use —
**Claude, Cursor, ChatGPT, and Codex** share one long-term memory of you. On top
of storage it runs a cognition layer: it reflects on conversations, consolidates
memories (we call it *dreaming*), and forms a model of who you are by memory type
— episodic, semantic, procedural, and foundational.

**Not smart. Just knows you.** → [icog.app](https://icog.app)

### 📦 cogix — the Large Cognitive Model (LCM) SDK
The developer surface. A persistent, evolving memory + cognition layer you build
applications on top of. Recall blends HNSW vector search and BM25 full-text via
Reciprocal Rank Fusion, reranked by a PageRank graph and a per-embodiment lens.

```bash
pip install cogix
```

```python
import cogix
cogix.init(pool)
await cogix.remember("user prefers dark mode", user_id="u1")
hits = await cogix.recall("ui preferences", embodiment_id="app", user_id="u1")
```

### ⌨️ cogx — the terminal client
`recall`, `remember`, and `talk` to your personal AI from any terminal. Pure
Node.js, zero dependencies.

## How it fits together

| Layer | What it is | Who it's for |
|-------|-----------|--------------|
| **iCog** | Hosted, MCP-native personal memory + cognition | Anyone who lives inside AI tools |
| **cogix** | The LCM SDK powering iCog | Developers embedding memory in their own apps |
| **cogx** | A zero-dependency CLI | Terminal-first users and scripts |

## The cognition layer

Storage is table stakes. What makes the memory *think about you*:

- **Reflection** — periodic cognitive self-assessment with trend deltas.
- **Dreaming** — offline consolidation that compresses memories and synthesizes
  relationships between them.
- **An identity model** — a structured picture of you built from typed memories,
  not a flat embedding blob.
- **Ranked recall** — vector + lexical fusion, graph reranking, and decay, so
  what surfaces is what *matters*, not just what's recent.

## Get started

- **Use it** → [icog.app](https://icog.app)
- **Build on it** → `pip install cogix` and read the [docs](https://docs.cognitivx.io)
- **Connect your tools** → add iCog as an MCP server in Claude, Cursor, ChatGPT, or Codex

---

<div align="center">
<sub>CognitiveX · United Kingdom · <a href="mailto:contact@cognitivx.io">contact@cognitivx.io</a></sub>
</div>
