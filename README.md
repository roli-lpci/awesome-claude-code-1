<!--lint disable awesome-heading-->

<div align="center">
  <h1>Awesome Claude Code</h1>
  <p>
    <a href="https://awesome.re"><img src="https://awesome.re/badge-flat2.svg" alt="Awesome"></a>
    <a href="https://github.com/fix2015/awesome-claude-code/stargazers"><img src="https://img.shields.io/github/stars/fix2015/awesome-claude-code?style=flat-square&color=yellow" alt="Stars"></a>
    <a href="https://github.com/fix2015/awesome-claude-code/network/members"><img src="https://img.shields.io/github/forks/fix2015/awesome-claude-code?style=flat-square" alt="Forks"></a>
    <a href="#contributing"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"></a>
  </p>
  <p>A curated list of awesome resources, tools, plugins, MCP servers, hooks, and tips for <a href="https://github.com/anthropics/claude-code">Claude Code</a> — the agentic coding tool that lives in your terminal.</p>
  <p><sub>If you find this list useful, please consider giving it a star. It helps others discover it too!</sub></p>
</div>

---

## Contents

- [Official Resources](#official-resources)
- [Agent Harnesses & Frameworks](#agent-harnesses--frameworks)
- [MCP Servers](#mcp-servers)
  - [General Purpose](#general-purpose)
  - [Browser & Web](#browser--web)
  - [Database & Cloud](#database--cloud)
  - [Design & Creative](#design--creative)
  - [Code Intelligence](#code-intelligence)
  - [Security](#security)
- [Skills & Plugins](#skills--plugins)
- [Hooks & Automation](#hooks--automation)
- [Memory & Context Management](#memory--context-management)
- [CLAUDE.md Templates & Best Practices](#claudemd-templates--best-practices)
- [IDE Integrations](#ide-integrations)
- [UI & Desktop Clients](#ui--desktop-clients)
- [Configuration & Optimization](#configuration--optimization)
- [Community Resources](#community-resources)
- [Contributing](#contributing)

---

## Official Resources

- [Claude Code](https://github.com/anthropics/claude-code) - The official Claude Code repository by Anthropic.
- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code) - Official documentation and guides.
- [Model Context Protocol Specification](https://modelcontextprotocol.io/) - The official MCP spec that powers Claude Code's extensibility.
- [MCP Servers](https://github.com/modelcontextprotocol/servers) - Official collection of reference MCP server implementations.
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Visual testing and debugging tool for MCP servers.

## Agent Harnesses & Frameworks

- [ECC](https://github.com/affaan-m/ECC) - Agent harness performance optimization system with skills, instincts, memory, and security for Claude Code and beyond.
- [gstack](https://github.com/garrytan/gstack) - Garry Tan's Claude Code setup with 23 opinionated tools serving as CEO, Designer, Eng Manager, and more.
- [get-shit-done](https://github.com/gsd-build/get-shit-done) - Meta-prompting, context engineering, and spec-driven development system for Claude Code.
- [ruflo](https://github.com/ruvnet/ruflo) - Multi-player swarm orchestration with adaptive memory, self-learning intelligence, and RAG integration.
- [Trellis](https://github.com/mindfold-ai/Trellis) - A high-performance agent harness for Claude Code.
- [oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) - Teams-first multi-agent orchestration for Claude Code.
- [FastMCP](https://github.com/PrefectHQ/fastmcp) - The fast, Pythonic way to build MCP servers and clients.

## MCP Servers

### General Purpose

- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - The definitive collection of MCP servers (90k+ stars).
- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Microsoft's official Playwright MCP server for browser automation.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub's official MCP server for repository operations.
- [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) - Terminal control, file system search, and diff editing capabilities.
- [GitMCP](https://github.com/idosal/git-mcp) - Free, open-source remote MCP server for any GitHub project. Eliminates code hallucinations.
- [Activepieces](https://github.com/activepieces/activepieces) - AI workflow automation with 400+ MCP servers for AI agents.
- [mcp-use](https://github.com/mcp-use/mcp-use) - Fullstack MCP framework to develop MCP apps and servers for AI agents.

### Browser & Web

- [MCP Chrome](https://github.com/hangwin/mcp-chrome) - Chrome extension-based MCP server for browser automation and content analysis.
- [Headroom](https://github.com/headroomlabs-ai/headroom) - Compress tool outputs and logs before they reach the LLM. 20% fewer tokens for coding agents.

### Database & Cloud

- [MCP Toolbox for Databases](https://github.com/googleapis/mcp-toolbox) - Google's open-source MCP server for databases.
- [AWS MCP Servers](https://github.com/awslabs/mcp) - Open-source MCP servers for AWS services.

### Design & Creative

- [Figma Context MCP](https://github.com/GLips/Figma-Context-MCP) - Provides Figma layout information to AI coding agents.

### Code Intelligence

- [Codebase Memory MCP](https://github.com/DeusData/codebase-memory-mcp) - Indexes codebases into a persistent knowledge graph. 158 languages, sub-ms queries.
- [Graphify](https://github.com/Graphify-Labs/graphify) - Turn any folder of code, SQL schemas, docs into a queryable knowledge graph.
- [CodeGraph](https://github.com/colbymchenry/codegraph) - Pre-indexed code knowledge graph that auto-syncs on code changes.
- [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) - Turn any code into an interactive knowledge graph you can explore and search.

### Security

- [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) - MCP server for Ghidra reverse engineering.
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - 150+ cybersecurity tools for automated pentesting and vulnerability discovery.

## Skills & Plugins

- [andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) - A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations.
- [caveman](https://github.com/JuliusBrussee/caveman) - Cuts 65% of tokens by compressing communication style.
- [humanizer](https://github.com/blader/humanizer) - Removes signs of AI-generated writing from text.
- [claude-skills](https://github.com/alirezarezvani/claude-skills) - 345+ skills and plugins for Claude Code across engineering, marketing, product, and more.
- [agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) - Installable library of 1,900+ agentic skills with installer CLI and bundles.
- [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) - 148 ready-to-use skills for science covering biology, chemistry, medicine, and drug discovery.
- [book-to-skill](https://github.com/virgiliojr94/book-to-skill) - Turn any technical book PDF into a Claude Code skill.
- [android-reverse-engineering-skill](https://github.com/SimoneAvogadro/android-reverse-engineering-skill) - Claude Code skill for Android app reverse engineering.
- [Trail of Bits Skills](https://github.com/trailofbits/skills) - Security research, vulnerability detection, and audit workflow skills.
- [codebase-to-course](https://github.com/zarazhangrui/codebase-to-course) - Turns any codebase into a beautiful, interactive single-page HTML course.
- [agent-rules](https://github.com/steipete/agent-rules) - Rules and knowledge to work better with agents such as Claude Code or Cursor.
- [Claude-Red](https://github.com/SnailSploit/Claude-Red) - Curated library of offensive security skills for Claude Code.
- [Raptor](https://github.com/gadievron/raptor) - Turns Claude Code into a general-purpose AI offensive/defensive security agent.
- [NotFair](https://github.com/nowork-studio/NotFair) - Open-source SEO, GEO/AEO, and paid-ads skills for Claude Code; bundles Google Search Console MCP, Google Analytics (GA4) MCP, Google Ads MCP, and Meta Ads MCP servers for live account data.

## Hooks & Automation

- [claude-code-hooks-mastery](https://github.com/disler/claude-code-hooks-mastery) - Master Claude Code hooks with examples and patterns.
- [claude-code-hooks-multi-agent-observability](https://github.com/disler/claude-code-hooks-multi-agent-observability) - Real-time monitoring for Claude Code agents through hook event tracking.
- [Continuous-Claude-v3](https://github.com/parcadei/Continuous-Claude-v3) - Context management with hooks that maintain state via ledgers and handoffs.
- [ccproxy](https://github.com/starbaser/ccproxy) - Build mods for Claude Code: hook any request, modify any response, intelligent model routing.
- [claude-ip-guard](https://github.com/cso1z/claude-ip-guard) - Claude Code hook plugin for IP-based access control and account protection.
- [workout-gate](https://github.com/BotchetDig/workout-gate) - A fun hook that blocks your prompt until you do your push-ups, counted via webcam.

## Memory & Context Management

- [claude-mem](https://github.com/thedotmack/claude-mem) - Persistent context across sessions. Captures, compresses, and injects relevant context into future sessions.
- [agentmemory](https://github.com/rohitg00/agentmemory) - Persistent memory for AI coding agents based on real-world benchmarks.
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Persistent file-based planning for long-running agentic tasks. Crash-proof markdown plans.
- [claude-code-memory-setup](https://github.com/lucasrosati/claude-code-memory-setup) - Up to 71.5x fewer tokens per session with Obsidian + Graphify integration.

## CLAUDE.md Templates & Best Practices

- [claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice) - From vibe coding to agentic engineering — practice makes Claude perfect.
- [claude-code-system-prompts](https://github.com/Piebald-AI/claude-code-system-prompts) - All parts of Claude Code's system prompt, 27 built-in tool descriptions, and sub-agent prompts.
- [claude-token-efficient](https://github.com/drona23/claude-token-efficient) - One CLAUDE.md file to keep responses terse and reduce output verbosity.
- [my-claude-code-setup](https://github.com/centminmod/my-claude-code-setup) - Shared starter template configuration and CLAUDE.md memory bank system.
- [tweakcc](https://github.com/Piebald-AI/tweakcc) - Customize system prompts, create custom toolsets, themes, input highlighters, and unlock private features.
- [learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) - A nano Claude Code-like agent harness, built from scratch.

## IDE Integrations

- [claudecode.nvim](https://github.com/coder/claudecode.nvim) - Official Claude Code Neovim IDE extension.
- [CC Switch](https://github.com/farion1231/cc-switch) - Cross-platform desktop all-in-one assistant for Claude Code, Codex, OpenCode, and more.
- [Open Design](https://github.com/nexu-io/open-design) - Open-source Claude Design alternative. Local-first desktop app for prototypes, dashboards, and more.
- [pal-mcp-server](https://github.com/BeehiveInnovations/pal-mcp-server) - Use Claude Code with Gemini, OpenAI, OpenRouter, Azure, Grok, Ollama, and custom models.

## UI & Desktop Clients

- [Claude Code UI](https://github.com/siteboon/claudecodeui) - Free open-source web UI/GUI to manage Claude Code sessions and projects remotely.

## Configuration & Optimization

### Token Optimization

- Use `--output-format stream-json` for programmatic integration.
- Set `CLAUDE_CODE_MAX_TURNS` to control autonomous operation length.
- Use `/compact` command regularly to reduce context window usage.
- Leverage `.claude/settings.json` for project-specific configurations.

### Useful Environment Variables

```bash
# Set max output tokens
export CLAUDE_CODE_MAX_OUTPUT_TOKENS=16384

# Enable extended thinking
export CLAUDE_CODE_USE_BEDROCK=1

# Custom API endpoint
export ANTHROPIC_BASE_URL=https://your-proxy.com

# Set max turns for headless mode
export CLAUDE_CODE_MAX_TURNS=25
```

### Recommended .claude/settings.json Structure

```json
{
  "permissions": {
    "allow": [
      "Bash(git *)",
      "Bash(npm run *)",
      "Bash(npx *)",
      "Read",
      "Write",
      "Edit",
      "Glob",
      "Grep"
    ],
    "deny": [
      "Bash(rm -rf /)",
      "Bash(curl * | bash)"
    ]
  }
}
```

## Community Resources

- [awesome-claude-code (hesreallyhim)](https://github.com/hesreallyhim/awesome-claude-code) - Another well-maintained awesome list for Claude Code.
- [awesome-mcp-servers (punkpeye)](https://github.com/punkpeye/awesome-mcp-servers) - The largest collection of MCP servers.
- [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) - A collection of MCP clients.
- [awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) - Ultimate guide to agent skills with quickstart and resources.
- [system-prompts-leaks](https://github.com/asgeirtj/system_prompts_leaks) - Extracted system prompts from Claude Code and other AI tools.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

If you find this list useful, a star on the repo would be greatly appreciated. It helps other developers discover these resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work. See [LICENSE](LICENSE) for details.
