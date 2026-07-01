![Ghost Conductor - AI Agent Orchestration](gc_hero.png)

**Ghost Conductor** is an AI agent orchestration platform. Set your context, choose an intent, and describe the task — your ghosts read the codebase, write the code, and open a pull request for your review.

Support for Anthropic, OpenAI, and Google models. Bring your own API keys and monitor costs per job, per provider, per model.

## Get Started

**Mac**
```bash
brew tap GhostConductor/ghostconductor
brew install --cask ghostconductor
ghostconductor
```

**Server (AWS)**

Deploy to AWS with one CloudFormation command — see the [server deployment guide](https://github.com/GhostConductor/ghostconductor/blob/main/deploy/cf/standalone/server.md).

**Linux**

Download the latest `.deb` or binary from the [latest release](https://github.com/GhostConductor/ghostconductor/releases/latest).

## Repos

- [ghostconductor](https://github.com/GhostConductor/ghostconductor) — the platform
- [ghost](https://github.com/GhostConductor/ghost) — the agent runtime
