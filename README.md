<div align="center">

```
╭─────────────────────────────────────────────────────────────────────────────────────────────────╮
│ ● ● ●                                  claude-power-mods                                        │
├─────────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                                 │
│  ██████╗  ██████╗ ██╗    ██╗███████╗██████╗     ▄███▀  ███╗   ███╗ ██████╗ ██████╗ ███████╗██╗  │
│  ██╔══██╗██╔═══██╗██║    ██║██╔════╝██╔══██╗   ███▀    ████╗ ████║██╔═══██╗██╔══██╗██╔════╝██║  │
│  ██████╔╝██║   ██║██║ █╗ ██║█████╗  ██████╔╝  ██████▀  ██╔████╔██║██║   ██║██║  ██║███████╗██║  │
│  ██╔═══╝ ██║   ██║██║███╗██║██╔══╝  ██╔══██╗    ▄██▀   ██║╚██╔╝██║██║   ██║██║  ██║╚════██║╚═╝  │
│  ██║     ╚██████╔╝╚███╔███╔╝███████╗██║  ██║   ▄█▀     ██║ ╚═╝ ██║╚██████╔╝██████╔╝███████║██╗  │
│  ╚═╝      ╚═════╝  ╚══╝╚══╝ ╚══════╝╚═╝  ╚═╝   ▀       ╚═╝     ╚═╝ ╚═════╝ ╚═════╝ ╚══════╝╚═╝  │
│                                                                                                 │
│  > /reload-plugins                                                                              │
│  [████████████████████████████] 100%  ·  8 mods loaded  ·  superpowers ON                       │
│                                                                                                 │
╰─────────────────────────────────────────────────────────────────────────────────────────────────╯
  git · worktrees · dashboard · artifacts · swarm · flow · terminal · mod-manager
```

**Extra panes, commands, and superpowers for Claude Code.**

Each mod below adds something Claude Code doesn't ship with: a git panel, a live session dashboard, a swarm of agents, a real terminal, and more. Pick the ones you want, then follow the link for install steps.

</div>

---

## 🌿 Git

- ![git-mod](https://img.shields.io/badge/git--mod-v0.5.0-F05032?logo=git&logoColor=white) **[git-mod](https://github.com/netgfx/claude-git-mod)**: a `/git` side panel with your branch header, staged and unstaged files, and stashes, always one glance away.
- ![worktrees-manager-mod](https://img.shields.io/badge/worktrees--manager--mod-v0.2.1-F05032?logo=git&logoColor=white) **[worktrees-manager-mod](https://github.com/netgfx/claude-worktrees-mod)**: run several git worktrees in parallel without them stepping on each other. Each gets its own color, task, branch, and port block.

## 📊 Session monitoring

- ![session-dashboard](https://img.shields.io/badge/session--dashboard-v0.2.1-8A2BE2) **[session-dashboard](https://github.com/netgfx/claude-session-dashboard-mod)**: a live pane for your current session. Watch prompt-cache state, tool calls, errors, and background work tick by.

## 🗂️ Artifacts / assets

- ![local-artifacts](https://img.shields.io/badge/local--artifacts-v0.3.1-2EA44F) **[local-artifacts](https://github.com/netgfx/claude-artifact-mod)**: every image, PDF, spreadsheet, and video your session produces, listed in a pane. Click one and it opens in your default app.

## 🤖 Agents

- ![swarm-mod](https://img.shields.io/badge/swarm--mod-v0.3.1-FF8C00) **[swarm-mod](https://github.com/netgfx/claude-swarm-mod)**: run a swarm of agents from one side pane. Spawn them, watch their state and token use, answer their approvals, and message them.

## 🧭 Code understanding

- ![flow-explainer-mod](https://img.shields.io/badge/flow--explainer--mod-v0.1.0-0EA5E9) **[flow-explainer-mod](https://github.com/netgfx/claude-flow-explainer)**: turn a scenario, a question, or a diff into a guided, step-by-step walk through the code. Great for reviewing AI-written code or learning an unfamiliar codebase.

## 💻 Terminal

- ![terminal-mod](https://img.shields.io/badge/terminal--mod-v0.2.0-111111?logo=gnometerminal&logoColor=white) **[terminal-mod](https://github.com/netgfx/claude-terminal-mod)**: a real terminal pane. `/trm` drops your shell into the workspace folder, with full-screen apps and colors that just work.

## 🧩 Mod management

- ![mod-manager](https://img.shields.io/badge/mod--manager-v0.2.2-DB2777) **[mod-manager](https://github.com/netgfx/claude-mod-manager)**: a `/mod-manager` pane for your installed mods. Update, enable, disable, or uninstall them, and add new marketplaces from a GitHub or GitLab URL.

---

## ⚡ Quick start

Each mod is a Claude Code plugin. Open the mod's repo for its exact install command. Most follow this pattern inside Claude Code:

```
/plugin marketplace add netgfx/<mod-repo>
/plugin install <mod>@<marketplace>
/reload-plugins
```

## 📜 License

This list is licensed under the [MIT License](LICENSE). Each mod's license lives in its own repo.
