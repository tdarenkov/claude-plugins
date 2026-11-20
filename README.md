# tdarenkov's Claude Code plugins

I'm tdarenkov. My focus is on making AI more frictionless and easier for people to use, building on the AI tools that already exist. These are the Claude Code plugins I build for my own daily work, published in case they help you too.

## Install

```bash
claude plugin marketplace add tdarenkov/claude-plugins
```

| Plugin | What it does | Install |
| --- | --- | --- |
| [parallel-kit](https://github.com/tdarenkov/parallel-kit) | [Parallel](https://parallel.ai), set up for agents: a router to the right Parallel tool, lookups that keep web pages out of your context, briefs and your yes before any paid run, and a guard so subagents can search but never spend. | `claude plugin install parallel-kit@tdarenkov`, then run `/parallel-kit:setup` in a session |

## Updating

Updates are not automatic. To take the latest:

```bash
claude plugin marketplace update tdarenkov
claude plugin update <plugin>@tdarenkov
```

Then `/reload-plugins`, or start a new session.

Changes: [CHANGELOG.md](CHANGELOG.md). License: [MIT](LICENSE).
