# multi-agent-sdlc has moved

This project has been renamed to **AgentFlow SDLC**.

New repository:

https://github.com/smota/agentflow-sdlc

The old `multi-agent-sdlc` name is no longer maintained except as a compatibility pointer. Please update remotes, package references, documentation, and automation to use `agentflow-sdlc`.

For adopting projects, run the AgentFlow SDLC assisted update flow and rename migration:

```bash
node /path/to/agentflow-sdlc/bin/cli.mjs update-prompt --target /path/to/project
node /path/to/agentflow-sdlc/bin/cli.mjs migrate-rename --target /path/to/project
node /path/to/agentflow-sdlc/bin/cli.mjs migrate-rename --target /path/to/project --write
```
