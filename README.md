# Claude Code timeline

A maintained reference to the public release history of [Claude Code](https://www.anthropic.com/claude-code), Anthropic's AI coding tool.

**Last updated:** July 21, 2026

## Quick facts

- **Research preview:** February 24, 2025
- **General availability:** May 22, 2025
- **Latest major milestone:** Auto Mode reached general availability on July 10, 2026.
- **Scope:** Claude Code product releases, supported surfaces, configuration, automation, and model changes that affected Claude Code. This is not a complete history of Claude models or Claude consumer apps.

## Timeline

### 2024

| Date | Milestone | Status | What changed |
| --- | --- | --- | --- |
| November 25 | Model Context Protocol announced | Announced | MCP established the tool and data connection standard that Claude Code later adopted. |

### 2025

| Date | Milestone | Status | What changed |
| --- | --- | --- | --- |
| February 24 | Claude Code research preview | Preview | Anthropic introduced the terminal coding agent with Claude 3.7 Sonnet. |
| May 22 | Claude Code general availability | Generally available | Claude Code left research preview. Anthropic also announced VS Code, JetBrains, and GitHub Actions support. |
| May 22 | Claude Opus 4 and Claude Sonnet 4 | Released | New Claude 4 coding and agent models became available alongside the general-availability release. |
| June 18 | Remote MCP servers | Released | Claude Code gained OAuth-based connections to hosted MCP servers. |
| June 30 | Hooks | Released | Lifecycle hooks let projects run checks and commands around Claude Code actions. |
| July 24 | Custom Subagents | Released | `/agents` added a way to define specialized agents for focused work. |
| July 28 | SessionStart Hook and agent mentions | Expanded | Sessions could run startup hooks, and custom agents could be invoked with `@` mentions. |
| July 30 | Agent model settings | Expanded | Custom agents could specify their own model. |
| August 5 | Claude Opus 4.1 | Released | Anthropic released a coding-focused Opus update. |
| August 20 | Team and Enterprise controls | Expanded | Business plans gained Claude Code seats and administrative controls. |
| September 29 | Claude Sonnet 4.5 | Released | A new Sonnet model arrived for coding, agents, and computer use. |
| October 20 | Claude Code on the web | Preview | Browser-based cloud coding sessions opened for connected GitHub repositories. |
| October 27 | Plan subagent | Expanded | Plan Mode gained a dedicated planning subagent. |
| October 31 | Plugins and marketplaces | Released | Plugins could package commands, agents, Skills, Hooks, MCP configuration, and related setup. |
| November 18 | Cloud dispatch and richer agent configuration | Expanded | Background work could move to Claude Code on the web, and custom agents gained more configuration options. |
| November 24 | Claude Opus 4.5 | Released | Anthropic released an Opus model for coding, agents, computer use, and longer tasks. |
| December 8 | Claude Code in Slack | Preview | `@Claude` could turn Slack channel or thread context into a Claude Code web session. |

### 2026

| Date | Milestone | Status | What changed |
| --- | --- | --- | --- |
| February 5 | Claude Opus 4.6 and agent teams | Released / Preview | Opus 4.6 launched, and agent teams entered research preview. |
| February 20 | Desktop preview, review, and merge | Expanded | Claude Code Desktop added app previews, pull-request review, auto-fix, auto-merge, and surface handoff. |
| February 20 | Claude Code Security | Preview | A limited security-review product began finding vulnerabilities and proposing patches. |
| February 25 | Remote Control expansion | Expanded | More Claude Code accounts received Remote Control access. |
| February 26 | Auto memory | Expanded | Claude Code began saving useful session context as auto memory. |
| March 5 | Named Remote Control sessions | Expanded | Remote Control sessions gained optional names. |
| March 19 | Channels | Preview | `--channels` let selected MCP servers push messages into an active session. |
| March 24 | Auto Mode | Preview | A classifier-backed permission mode opened in research preview. |
| April 14 | Desktop redesign | Released | Desktop added a session sidebar, flexible layouts, an integrated terminal, and a file editor. |
| April 14 | Routines | Preview | Claude Code web infrastructure gained scheduled, API-triggered, and GitHub-event automation. |
| May 11 | Agent View and `/goal` | Preview / Released | Agent View showed session status, and `/goal` added persistent completion conditions. |
| May 13 | VS Code Remote Control | Expanded | The VS Code extension gained `/remote-control` support. |
| May 28 | Claude Opus 4.8 | Released | Anthropic released an Opus update for coding and longer agent work. |
| June 2 | Dynamic workflows | Preview | Claude Code could compose task-specific multi-agent workflows. |
| June 9 | Claude Fable 5 and Claude Mythos 5 | Released / Restricted | Anthropic announced higher-tier model lines with different access policies. |
| June 30 | Claude Sonnet 5 | Released | A new Sonnet model arrived for coding, tool use, agents, and professional work. |
| July 10 | Auto Mode general availability | Generally available | Auto Mode moved from preview to general availability, subject to plan and provider limits. |

## How to read the timeline

- **Preview** means Anthropic made a feature available to a limited audience or under research-preview terms.
- **Generally available** means Anthropic released the feature more broadly. Plan, provider, administrator, or regional limits can still apply.
- **Expanded** means Anthropic widened an existing capability, added a supported surface, or added a material workflow control.
- A model appears here only when it changed the practical Claude Code experience. For the complete model chronology, see the [Claude Timeline](https://www.scriptbyai.com/anthropic-claude-timeline/).

## Repository contents

| File | Purpose |
| --- | --- |
| [`README.md`](README.md) | A concise, GitHub-friendly version of the timeline. |
| [`article.html`](article.html) | The full WordPress block HTML article. |
| [`SEO.md`](SEO.md) | Search metadata, internal-link mapping, and update guidance. |

## Update policy

This repository adds an event when an official Anthropic source documents a durable change to Claude Code capability, availability, supported surfaces, project configuration, automation, or model choice.

Each update should include an exact date, an availability label, and an official Anthropic announcement, documentation page, release note, or repository source. Routine bug fixes and minor version increments do not belong in this timeline unless they change how you use Claude Code.

## Related resources

- [Full Claude Code Timeline article](https://www.scriptbyai.com/claude-code-timeline/)
- [Claude Timeline](https://www.scriptbyai.com/anthropic-claude-timeline/)
- [Claude Code Resource List](https://www.scriptbyai.com/claude-code-resource-list/)
- [Claude Code Commands Cheat Sheet](https://www.scriptbyai.com/claude-code-commands-cheat-sheet/)
- [Best Agent Skills](https://www.scriptbyai.com/best-agent-skills/)
- [MCP Servers](https://www.scriptbyai.com/mcp/)

## Contributing

If you spot an omission or an incorrect date, open an issue or pull request with the relevant official Anthropic source. Please do not add product rumors, UI strings, or third-party reports as timeline evidence.

## Disclaimer

This is an independent reference maintained by ScriptByAI. It is not affiliated with or endorsed by Anthropic.
