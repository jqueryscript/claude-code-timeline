# Claude Code Timeline

A concise, reverse-chronological record of the Claude Code releases and product changes that changed how developers use it. It focuses on major model choices, supported surfaces, configuration, automation, and availability milestones.

**Last updated:** August 21, 2026

## 2026

| Date | Milestone | What changed |
| --- | --- | --- |
| August 20 | Authenticated plugin sources and runner controls | Plugin marketplaces could mint headers for catalog and same-origin archive fetches, while self-hosted runners gained graceful shutdown and proxy authorization settings. |
| August 13 | Default subagent forking and GitLab workflows | Forked subagents inherited the current conversation and prompt cache by default, while non-teammate agents ran in the background. Named sessions gained direct `@` messaging, and GitLab support expanded across marketplaces and worktree merge-request flows. |
| August 7 | Self-hosted environments and cross-session messaging | Team and Enterprise users could run web, mobile, and desktop sessions on their own machines or containers. Sessions on macOS and Linux also gained cross-device discovery and messaging, and plugins could install from SHA-256-pinned HTTPS archives. |
| August 4 | Focus view and safer isolated work | VS Code gained Focus view. Linux and WSL sandboxes added credential-file masking, `/fork` sessions received their own worktrees, and background sessions gained clearer Git handoff rules. |
| July 24 | Claude Opus 5 and workflow controls | Opus 5 became the default Opus model. Claude Code also added Dynamic workflow-size settings, the `DirectoryAdded` Hook, sandbox network allowlisting, and deeper nested-subagent delegation. |
| July 10 | Auto Mode reaches general availability | Auto Mode moved from preview to general availability, subject to plan and provider limits. |
| June 30 | Claude Sonnet 5 | A new Sonnet model arrived for coding, tool use, agents, and professional work. |
| June 9 | Claude Fable 5 and Claude Mythos 5 | Anthropic announced higher-tier model lines with different access policies. |
| June 2 | Dynamic workflows | Claude Code could compose task-specific multi-agent workflows in preview. |
| May 28 | Claude Opus 4.8 | Anthropic released an Opus update for coding and longer agent work. |
| May 13 | VS Code Remote Control | The VS Code extension gained `/remote-control` support. |
| May 11 | Agent View and `/goal` | Agent View showed session status, and `/goal` added persistent completion conditions. |
| April 14 | Desktop redesign | Desktop added a session sidebar, flexible layouts, an integrated terminal, and a file editor. |
| April 14 | Routines | Claude Code web infrastructure gained scheduled, API-triggered, and GitHub-event automation in preview. |
| March 24 | Auto Mode preview | A classifier-backed permission mode opened in research preview. |
| March 19 | Channels | `--channels` let selected MCP servers push messages into an active session. |
| March 5 | Named Remote Control sessions | Remote Control sessions gained optional names. |
| February 26 | Auto memory | Claude Code began saving useful session context as auto memory. |
| February 25 | Remote Control expansion | More Claude Code accounts received Remote Control access. |
| February 20 | Desktop preview, review, and merge | Claude Code Desktop added app previews, pull-request review, auto-fix, auto-merge, and surface handoff. |
| February 20 | Claude Code Security | A limited security-review product began finding vulnerabilities and proposing patches. |
| February 5 | Claude Opus 4.6 and agent teams | Opus 4.6 launched, and agent teams entered research preview. |

## 2025

| Date | Milestone | What changed |
| --- | --- | --- |
| December 8 | Claude Code in Slack | `@Claude` could turn Slack channel or thread context into a Claude Code web session. |
| November 24 | Claude Opus 4.5 | Anthropic released an Opus model for coding, agents, computer use, and longer tasks. |
| November 18 | Cloud dispatch and richer agent configuration | Background work could move to Claude Code on the web, and custom agents gained more configuration options. |
| October 31 | Plugins and marketplaces | Plugins could package commands, agents, Skills, Hooks, MCP configuration, and related setup. |
| October 27 | Plan subagent | Plan Mode gained a dedicated planning subagent. |
| October 20 | Claude Code on the web | Browser-based cloud coding sessions opened for connected GitHub repositories. |
| September 29 | Claude Sonnet 4.5 | A new Sonnet model arrived for coding, agents, and computer use. |
| August 20 | Team and Enterprise controls | Business plans gained Claude Code seats and administrative controls. |
| August 5 | Claude Opus 4.1 | Anthropic released a coding-focused Opus update. |
| July 30 | Agent model settings | Custom agents could specify their own model. |
| July 28 | SessionStart Hook and agent mentions | Sessions could run startup Hooks, and custom agents could be invoked with `@` mentions. |
| July 24 | Custom Subagents | `/agents` added a way to define specialized agents for focused work. |
| June 30 | Hooks | Lifecycle Hooks let projects run checks and commands around Claude Code actions. |
| June 18 | Remote MCP servers | Claude Code gained OAuth-based connections to hosted MCP servers. |
| May 22 | Claude Opus 4 and Claude Sonnet 4 | New Claude 4 coding and agent models became available alongside the general-availability release. |
| May 22 | Claude Code general availability | Claude Code left research preview with VS Code, JetBrains, and GitHub Actions support. |
| February 24 | Claude Code research preview | Anthropic introduced the terminal coding agent with Claude 3.7 Sonnet. |

## 2024

| Date | Milestone | What changed |
| --- | --- | --- |
| November 25 | Model Context Protocol announced | MCP established the tool and data connection standard that Claude Code later adopted. |

## More on ScriptByAI

- [Full Claude Code Timeline](https://www.scriptbyai.com/claude-code-timeline/)
- [Claude Timeline](https://www.scriptbyai.com/anthropic-claude-timeline/)
- [Claude Code Resource List](https://www.scriptbyai.com/claude-code-resource-list/)
- [Claude Code Commands Cheat Sheet](https://www.scriptbyai.com/claude-code-commands-cheat-sheet/)
- [Best Agent Skills](https://www.scriptbyai.com/best-agent-skills/)
- [MCP Servers](https://www.scriptbyai.com/mcp/)

## Related GitHub Projects

- [Awesome Claude Code](https://github.com/jqueryscript/awesome-claude-code): a curated directory of Claude Code tools, IDE integrations, frameworks, and resources.
- [Claude Code Slash Commands Cheatsheet](https://github.com/jqueryscript/Claude-Code-Slash-Commands-Cheatsheet): a practical reference for Claude Code commands.
- [Anthropic Claude Timeline](https://github.com/jqueryscript/anthropic-claude-timeline): the wider history of Claude models, products, and developer-platform milestones.
- [Awesome Agent Skills](https://github.com/jqueryscript/awesome-agent-skills): a curated collection of Agent Skills for coding agents and AI workflows.

