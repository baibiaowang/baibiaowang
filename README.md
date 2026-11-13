![banner](banner.jpg)

# Hi, I'm 老王 (Lao Wang) 👋

<img align="right" src="avatar.jpg" width="120" alt="老王" />

I build **AI agent tooling for cross-border e-commerce and market data**. Most of my work is
about letting an AI agent safely operate a real production system — a store, a data pipeline,
or a desktop harness — instead of just chatting about it.

## What I work on

- **WooCommerce × MCP** — plugins that give AI agents controlled access to a store:
  store operations (products / orders / refunds / SEO), storefront design, and infrastructure
  (backup / mail / consent / cache / hardening). Built with confirmation tokens, undo and audit trails.
- **Market data pipelines** — market-wide public disclosure dashboards: scheduled collection →
  rule filtering → AI classification → summarization → curated pools → static dashboard.
- **DeepSeek Harness (dsh) ecosystem** — plugins, skills and voice-input tooling for a
  local, agent-driven desktop workspace.

## Featured repositories

| Repository | What it is |
|---|---|
| [aihand-for-woocommerce](https://github.com/baibiaowang/aihand-for-woocommerce) | Store operations MCP plugin — products, orders, refunds, SEO, support |
| [aidesign-for-woocommerce](https://github.com/baibiaowang/aidesign-for-woocommerce) | Storefront design MCP plugin — theme styles, sections, palettes, comparisons |
| [aitools-for-woocommerce](https://github.com/baibiaowang/aitools-for-woocommerce) | Store infrastructure MCP plugin — backup, mail, consent, pixels, cache, hardening |
| [panda-board](https://github.com/baibiaowang/panda-board) | Market disclosure dashboard — sandbox collection → data repo → GitHub Pages |
| [dsh-voice-input-wb-asr](https://github.com/baibiaowang/dsh-voice-input-wb-asr) | Hold-to-talk voice input for DeepSeek Harness, cloud speech recognition |

## Tech

`PHP` · `Python` · `TypeScript` / `JavaScript` · `WordPress` / `WooCommerce` · `MCP` · `GitHub Actions` · `LLM pipelines`

## Working principles

1. **Verify by running it.** A configuration that has not been executed is a guess.
2. **Guardrails over hope.** Every agent-facing write should have a confirmation step, an undo path, and a log.
3. **Small, self-contained tools.** One job per plugin or script; no hidden service dependencies.

---

<sub>Most repositories are private or in active development — feel free to reach out.</sub>
