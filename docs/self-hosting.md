# Self-hosting a Hermes alternative

Kortix is the open-source AI Operating System. Self-hosting is not a build step, it is a choice about where the repo lives and who reviews the change.

## Kortix, self-hosted

```bash
curl -fsSL https://kortix.com/install | bash
kortix init
kortix self-host start   # one Docker Compose stack on your own box
```

The whole system — agents, skills, memory, connectors, triggers and the machine image — is text in one git repo. Self-hosting just changes where the sessions run. Moving between your box and Kortix Cloud is a git clone.

## What you own either way

- **The configuration.** Every agent and skill is a markdown file you can read and diff. There is no settings database behind it.
- **The memory.** What the company has learned accumulates as files in the repo.
- **The change history.** Every change an agent proposes arrives as a change request with a diff.

## What self-hosting does not change

- **Governance.** Per-tool allow / ask / block and approval gates are declared in the repo, so they travel with it.
- **Models.** Point the config at your own providers and keys, or your own OpenAI-compatible endpoint.

See [the setup notes](kortix-vs-hermes.md) for how this maps onto a Hermes-style personal setup.
