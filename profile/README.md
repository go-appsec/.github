Focused building blocks for application security testing. Proxy interception, reconnaissance, and out-of-band detection, each usable on its own or composed together. Our flagship project, **[toolbox](https://github.com/go-appsec/toolbox)**, presents these capabilities through a CLI and an MCP server, letting human operators and LLM agents collaborate on the same authenticated session.

### Repositories

**[go-appsec/toolbox](https://github.com/go-appsec/toolbox)** — A collaborative workbench for humans and coding agents, not a scanner. Proxy history, request replay, crawling, OAST, flow diffing, and reflection detection are exposed as MCP tools for your agent and as CLI commands for you. You drive the browser and handle auth; the agent queries flows, mutates requests, and iterates on permutations against the same live session.

**[go-appsec/interactsh-lite](https://github.com/go-appsec/interactsh-lite)** — A dependency-minimal Go implementation of both client and server for Interactsh out-of-band (OOB/OAST) interaction detection. Wire-compatible with ProjectDiscovery's official client and server, so either side can be swapped independently. Ships as an embeddable library, a small standalone CLI (under 8MB), and a self-hosted capture server that adds flexible correlation ID formats for shorter or LLM-friendly payload domains.

**[go-appsec/scout](https://github.com/go-appsec/scout)** — Passive reconnaissance module for broadening the attack surface. Discovers subdomains and URLs to expand the set of targets worth testing.
