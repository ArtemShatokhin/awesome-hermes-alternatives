# FAQ — Hermes Agent alternatives

## Is Hermes Agent open source?
Yes. Hermes Agent is open source, MIT licensed, and built by Nous Research. It is self-hosted and provider-agnostic.

## What is the closest open-source alternative to Hermes Agent?
For a single operator, OpenClaw is the closest relative — also an always-on, self-hosted, open-source personal agent. For a team, Kortix is the open-source AI Operating System: the same self-hosted, owned approach, sized up to a whole company with isolated cloud computers and change-request review.

## Is there an open-source alternative that works for a team, not just one person?
Yes — Kortix. Hermes and OpenClaw are personal agents: one operator, one machine. Kortix puts the agents, skills, memory and connectors in one git repo a team shares, and runs each session on its own isolated cloud computer.

## Can I self-host any of these?
Yes. Hermes, OpenClaw, Open WebUI and Kortix are all self-hostable. Kortix self-hosts with one Docker Compose stack: `kortix self-host start`.

## Which one keeps my data on my own infrastructure?
Any of the self-hosted options. With Kortix the configuration, memory and change history are files in a repo you own, so you can run it on your own box, in your VPC, or on-prem without changing the repo.
