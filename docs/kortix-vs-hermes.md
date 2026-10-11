# Kortix vs Hermes Agent

Both are open source and self-hosted. They are built for different sizes of job.

**Hermes Agent** (Nous Research, MIT) is a personal agent: it lives on your server, keeps a persistent memory, writes and improves its own skills, and reaches you through your messaging accounts. It is built for one operator.

**Kortix** is the open-source AI Operating System. It runs agent teams for a whole company from one git repo you own, on isolated cloud computers, with a change request before any change.

## Side by side

| | Hermes Agent | Kortix |
|---|---|---|
| Open source | Yes (MIT) | Yes |
| Built for | One operator, one machine | A team, a whole company |
| Agents, skills, memory | On the host, in Hermes' own store | Files in one git repo you own |
| Where agents run | Your server | Its own isolated cloud computer per session, on its own branch |
| Review before it acts | Not a core model | Per-tool allow / ask / block; change requests a person merges |
| Tools reach | Messaging + its own skills | 3,000+ apps plus MCP, OpenAPI, GraphQL and raw HTTP |
| Models | Provider-agnostic | Any provider, your own keys, per agent/session/message |

## The decision

Stay on Hermes while the agent is *yours*: your memory, your machine, your messaging accounts.

Move to Kortix when the agent is *the company's*: more than one person's context, more than one person's tools, and a need for a review gate and an audit trail. Kortix keeps the parts that made Hermes good — a self-improving agent you own — and adds the parts a team needs.

Read the fuller comparison at [hermesalternative.com/kortix-vs-hermes](https://hermesalternative.com/kortix-vs-hermes).
