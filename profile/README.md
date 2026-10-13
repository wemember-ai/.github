<p align="center">
  <a href="https://wemember.ai">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wemember-ai/.github/main/assets/wemember-logo-white.svg">
      <img alt="Wemember" src="https://raw.githubusercontent.com/wemember-ai/.github/main/assets/wemember-logo.svg" width="280">
    </picture>
  </a>
</p>

<p align="center"><b>Company memory and a toolkit for organizational AI agents.</b></p>

---

Wemember is infrastructure, not another place to work. It sits as an MCP layer under the AI tools your team already uses, such as Claude, ChatGPT, Cursor, Codex and Grok, and gives every one of them the same company context: sources, knowledge and procedures, scoped to the workspace, team or person that may see them.

### How it works

- **One MCP endpoint.** Connect `https://app.wemember.ai/mcp` in your AI client and sign in with your own account (OAuth). Each agent acts as the person who connected it.
- **Context, within your rules.** Agents read sources and published knowledge that the signed-in person may see. Every delivery is recorded with the exact item versions.
- **Agents propose, people decide.** Agents can propose new memory or corrections. Publishing, revoking and actions in other apps go through review and approval.
- **Governed app access.** Connected apps are used through the same layer, with approval for anything that changes data outside Wemember.

### Get started

| Client | Connect |
| --- | --- |
| Claude Code | `claude mcp add --transport http wemember https://app.wemember.ai/mcp`, or install the [plugin](https://github.com/wemember-ai/plugin) |
| Codex | `codex mcp add wemember --url https://app.wemember.ai/mcp`, or install the [plugin](https://github.com/wemember-ai/plugin) |
| Cursor | Install the [plugin](https://github.com/wemember-ai/plugin) from a team marketplace |
| Other MCP clients | Add `https://app.wemember.ai/mcp` as a remote (Streamable HTTP) MCP server |

You need a Wemember account.

### Links

- [wemember.ai](https://wemember.ai)
- [Wemember plugin](https://github.com/wemember-ai/plugin): setup, what the plugin sends and stores, and how to turn it off
- [Security policy](https://github.com/wemember-ai/.github/blob/main/SECURITY.md)
