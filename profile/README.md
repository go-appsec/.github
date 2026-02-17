## go-appsec

Application security tools written in Go. Built for pentesters, AppSec engineers, and coding agents.

Our modules focus on practical testing workflows — proxy interception, reconnaissance, out-of-band detection — designed to work standalone or together. The flagship project, **toolbox**, exposes these capabilities through both a CLI and an MCP server, so human operators and LLM agents can collaborate on the same session.

### Repositories

**[toolbox](https://github.com/go-appsec/toolbox)** — Collaborative application security testing between humans and agents via CLI and MCP. Proxy history, request replay, crawling, OAST, flow diffing, reflection detection — all accessible to your coding agent as MCP tools, or from the terminal as CLI commands. You handle auth and UI; the agent queries flows, mutates requests, and tests permutations.

**[interactsh-lite](https://github.com/go-appsec/interactsh-lite)** — Lightweight Interactsh client for out-of-band testing (OOB/OAST). Minimal dependencies, designed for embedding, but also distributed as a small CLI executable.

**[scout](https://github.com/go-appsec/scout)** — Passive recon module to expand testing targets. Discovers subdomains and URLs to widen testing scope.
