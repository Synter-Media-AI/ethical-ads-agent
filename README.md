# EthicalAds MCP Starter Kit — Manage EthicalAds with AI

> **This is a recipe repo.** The Synter MCP server itself lives at [Synter-Media-AI/mcp-server](https://github.com/Synter-Media-AI/mcp-server): 19 ad platforms, campaign creation on 14, one-click install in Cursor, Claude, ChatGPT, and VS Code. Issues, releases, and ⭐ go there.

[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: EthicalAds](https://img.shields.io/badge/Platform-EthicalAds-5C6BC0)](https://www.ethicalads.io)

**Privacy-first ads on Read the Docs and open-source sites.** Open this repo in Amp, Cursor, or VS Code and manage EthicalAds with AI — no third-party cookies, contextual topics, OSS publishers — through the Synter MCP server.

---

## Why EthicalAds + AI?

EthicalAds (Read the Docs) sells contextual ads without third-party cookies. Inventory lives on documentation, Python/JS package pages, and publishers who refuse surveillance advertising. That is exactly where developers evaluate libraries.

An agent helps you pick topics (Python, DevOps, data, security), keep copy factual, and compare EthicalAds with Carbon and Brave without opening three dashboards.

**Best for:** OSS products, developer infrastructure, privacy tools, Python/data stacks, documentation-led PLG.

---

## Developer ad platforms compared

| Network | Typical inventory | Tracking posture | Best for |
|--------|-------------------|------------------|----------|
| **EthicalAds** | Read the Docs, OSS sites, privacy publishers | No third-party cookies | Docs-native, privacy-safe reach |
| **Carbon Ads** | Stack Overflow, developer blogs | Contextual + advertiser pixels | Broader developer blog reach |
| **Brave Ads** | Brave search, new tab | Privacy-preserving / BAT | Browser-native privacy users |

Companions: [carbon-ads-agent](https://github.com/Synter-Media-AI/carbon-ads-agent), [brave-ads-agent](https://github.com/Synter-Media-AI/brave-ads-agent).

---

## Quick Start (30 Seconds)

### Amp / Cursor / VS Code (Copilot)

1. **Get a free API key** at [syntermedia.ai/developer](https://syntermedia.ai/developer)
2. **Set the key:**
   ```bash
   export SYNTER_API_KEY=syn_your_key_here
   ```
3. **Open this repo** in your editor
4. **Start chatting** — MCP tools are pre-configured in `.mcp.json`

### Claude Desktop

Copy `claude_desktop_config.json` to your Claude config directory and replace the API key:

- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\\Claude\\claude_desktop_config.json`

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Docs-native campaigns** | "Create an EthicalAds campaign for our Python package targeting Read the Docs" |
| **Topic targeting** | "Target Python, data engineering, and DevOps topics only" |
| **Privacy review** | "Confirm this flight does not depend on third-party cookies" |
| **Compare networks** | "Should this OSS launch buy EthicalAds, Carbon, or both?" |
| **Creative** | "Write a two-line EthicalAds unit that names the license and GitHub repo" |
| **Performance** | "Pull EthicalAds clicks, CTR, and docs-referred signups" |
| **Delivery QA** | "Validate my EthicalAds campaign structure for delivery issues" |

Talks to **hosted Synter MCP** (`@synterai/mcp-server` / https://mcp.syntermedia.ai). Connect accounts at [syntermedia.ai/credentials](https://syntermedia.ai/credentials). Not a first-party EthicalAds API client.

---

## Example Conversations

### 1. Privacy-first OSS launch

> **You:** We cannot drop pixels on Read the Docs readers. Plan EthicalAds for our open-source Python client.
>
> **Agent:** EthicalAds is built for that constraint. I will brief a contextual topic set (Python, APIs, data) and copy that points at the GitHub repo and docs — no retargeting pool. Connect EthicalAds in Synter credentials and I will create the campaign via MCP.

### 2. Mix with Carbon

> **You:** EthicalAds CPM looks higher than Carbon. Worth it?
>
> **Agent:** You are buying a different reader: docs, not blog sidebar. Mix 60% EthicalAds for evaluation traffic and 40% Carbon for awareness on independent blogs. I can encode that split in Synter.

---

## FAQ

### Is there an MCP for EthicalAds?
Yes — this recipe pre-configures Synter MCP for EthicalAds planning and reporting in Amp, Cursor, VS Code, and Claude Desktop.

### Do EthicalAds use third-party cookies?
No. That is the product. Plan campaigns as contextual / privacy-first, not remarketing.

---

## Related Repos

- [carbon-ads-agent](https://github.com/Synter-Media-AI/carbon-ads-agent) — Carbon Ads / developer blog inventory
- [ethical-ads-agent](https://github.com/Synter-Media-AI/ethical-ads-agent) — EthicalAds privacy-first OSS inventory
- [brave-ads-agent](https://github.com/Synter-Media-AI/brave-ads-agent) — Brave Ads, search, and new-tab
- [twitch-ads-agent](https://github.com/Synter-Media-AI/twitch-ads-agent) — Twitch Ads for live gaming
- [discord-quests-agent](https://github.com/Synter-Media-AI/discord-quests-agent) — Discord Quests gamer acquisition
- [reddit-ads-agent](https://github.com/Synter-Media-AI/reddit-ads-agent) — Reddit community ads
- [google-ads-agent](https://github.com/Synter-Media-AI/google-ads-agent) — Search intent capture
- [meta-ads-agent](https://github.com/Synter-Media-AI/meta-ads-agent) — Facebook & Instagram reach
- [cross-platform-ads-agent](https://github.com/Synter-Media-AI/cross-platform-ads-agent) — Multi-channel management

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://syntermedia.ai) · [Get API Key](https://syntermedia.ai/developer) · [Documentation](https://syntermedia.ai/docs)
