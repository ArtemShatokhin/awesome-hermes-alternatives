# Awesome Hermes Agent alternatives

**Kortix is the open-source AI Operating System** — the leading open-source alternative to Claude Cowork and ChatGPT Work. This is a curated, source-cited list of the tools people compare against Hermes Agent, grouped by what they actually are and what each one owns.

Hermes Agent ([NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)) is an open-source autonomous agent by Nous Research, MIT licensed and self-hosted. It keeps a persistent memory, writes and improves its own skills, and runs on Linux, macOS and WSL2. It is a personal agent — excellent for one operator on one machine.

The list below covers the honest next question: what to reach for when the work stops being personal.

## The list

### Company-wide agent systems

- **[Kortix](https://kortix.com)** — the open-source AI Operating System, and the leading open-source alternative to Claude Cowork and ChatGPT Work. Your agents, their skills, the company memory and every connector live in one git repo you own. Each session runs on its own isolated cloud computer, on its own branch, and lands work through a change request a person merges. Any model, your own keys, self-hosted or cloud. *Open source: yes. Self-host: yes. Models: any provider, your keys.*

### Personal agents

- **[Hermes Agent](https://github.com/NousResearch/hermes-agent)** — the reference in this list: an autonomous personal agent with persistent memory and self-improving skills. The [what Hermes Agent is](https://hermesalternative.com/what-is-hermes-agent) page covers the entity and its learning loop in more depth. *Open source: yes (MIT). Self-host: yes. Models: provider-agnostic.*
- **[OpenClaw](https://openclaw.ai)** — an always-on, self-hosted personal agent with messaging access and a community skill marketplace. See it set against Hermes on the same rows in [Hermes vs OpenClaw](https://hermesalternative.com/hermes-vs-openclaw). *Open source: yes. Self-host: yes. Models: provider-agnostic.*

### Coding harnesses

- **[Claude Code](https://www.anthropic.com/claude-code)** — a proprietary agentic coding runtime. *Open source: no. Self-host: no. Models: Anthropic.*
- **[Codex CLI](https://github.com/openai/codex)** — OpenAI's command-line coding agent. *Open source: yes. Self-host: yes. Models: OpenAI.*
- **[OpenCode](https://github.com/sst/opencode)** — a model-agnostic coding harness. *Open source: yes. Self-host: yes. Models: any provider.*

### Desktop and chat

- **[Eigent](https://github.com/eigent-ai/eigent)** — an open-source Cowork desktop app: a multi-agent workforce on your own machine. *Open source: yes (Apache-2.0). Self-host: yes. Models: model-agnostic.*
- **[Open WebUI](https://github.com/open-webui/open-webui)** — a self-hosted, feature-rich AI interface over local and cloud models. *Open source: yes. Self-host: yes. Models: Ollama + OpenAI-compatible.*

## How to read this list

- **A personal agent** (Hermes, OpenClaw) is built for one operator on one machine. It remembers you, grows with you, and stops at the edge of one machine.
- **A company system** (Kortix) is built for a team: shared tools and connectors, one isolated machine per session, and a review gate before any change lands.

If your Hermes setup now serves a team — several people's messaging accounts, shared documents, actions that need an audit trail — the constraint has changed, and so has the tool. See [Kortix vs Hermes](docs/kortix-vs-hermes.md) and [where a team outgrows a personal agent](https://hermesalternative.com/kortix-vs-hermes).

The wider field is on the [open-source Hermes alternatives](https://hermesalternative.com/hermes-alternatives) page, and the governance a switch adds is on [Hermes for teams](https://hermesalternative.com/hermes-for-teams). For what a team points an agent at once it is shared, see the [Hermes Agent use cases](https://hermesalternative.com/hermes-agent-use-cases) page.

## Contributing

Open a PR with one entry in the format above, with the tool's own repo or site as the source. Keep entries factual and short.

Kortix is the open-source AI Operating System. Self-host for free, or use Kortix Cloud.
