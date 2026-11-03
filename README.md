<div align="center">

# Hi, I'm Anh 👋

**Software engineer · CS @ University of Melbourne · open-source contributor**

[![Website](https://img.shields.io/badge/orbyn.dev-0b0b0f?style=flat-square&logo=safari&logoColor=white)](https://orbyn.dev/)
[![Orbyn](https://img.shields.io/badge/Orbyn-planner-6d5dfc?style=flat-square)](https://github.com/kinqsradiollc/Orbyn)
[![Orbyn Engineering](https://img.shields.io/badge/Orbyn_Engineering-workbench-0ea5e9?style=flat-square)](https://github.com/kinqsradio/orbyn-engineering)
[![Skills](https://img.shields.io/badge/Fullstack_Skills-library-22c55e?style=flat-square)](https://github.com/kinqsradio/orbyn-fullstack-skills)

</div>

I build tools for working *with* coding agents, and I contribute to the editor many of us live in.

## 🔧 Open source: VS Code

I'm an active contributor to [microsoft/vscode](https://github.com/microsoft/vscode), mostly in the remote and ports layer, where small rules decide whether a forwarded port opens as HTTP or HTTPS.

- Merged: [Fix `requireLocalPort` for range, regex, and host-and-port rules](https://github.com/microsoft/vscode/pull/344185)
- Merged: [Preserve inherited port protocol for exact-port attributes](https://github.com/microsoft/vscode/pull/344764)
- In review: folding range providers, proxied Claude session environments, remote uninstall batches

My habit on every PR: a regression test that fails on the old code, and a before/after check in a source-built Code - OSS, not just a green suite.

## 🚀 What we maintain

| Project | What it is |
| --- | --- |
| [**Orbyn**](https://github.com/kinqsradiollc/Orbyn) | A planner for tasks, calendars, projects and documents, with an AI assistant and web, desktop and mobile clients. |
| [**Orbyn Engineering**](https://github.com/kinqsradio/orbyn-engineering) | A Rust desktop and web workbench that wraps coding CLIs (Claude Code, Codex) in Orbyn skills. |
| [**Orbyn Fullstack Skills**](https://github.com/kinqsradio/orbyn-fullstack-skills) | Our portable skill set and harness for Codex and Claude Code: architecture, APIs, TypeScript, UX, CI, evals. |

## 🧠 How we think about the harness

A model is only as useful as the harness around it. Our skill set is built on a few beliefs:

1. **Skills are small, owned and versioned.** One skill, one owner, one job. Routing beats a giant prompt, and nothing loads unless the task needs it.
2. **The harness decides cost, not the vibe.** Tiers, delegation limits and effort are resolved per repository before work starts. The strongest model plans and reviews, cheaper ones implement and scout.
3. **Prove it against an answer the worker can't change.** Tasks are graded with original tests, and a host failure is never scored as a model failure.
4. **Respect the target.** We work inside someone else's repo by its rules. Skills are never installed into it, and its own instructions win.
5. **Memory is explicit.** Lessons are saved only when you ask or approve. Never silently, never secrets, and always treated as a hint to check against the code.
6. **Disclose everything.** Every PR states the tools, exact models, effort and sources used. Trust comes from receipts.

## 🔮 Where we think autonomy is going

- **Autonomy will be bounded, not unlimited.** The useful agents are the ones with clear scopes, budgets and a way to stop. Permission design will matter as much as model quality.
- **Verification is the bottleneck, not generation.** Writing code is getting cheap. Knowing it's right isn't. The winners will invest in evals, answer keys and independent review.
- **Parallel work needs isolation.** Many agents on one checkout is a recipe for collisions. Worktrees, ownership rules and merge discipline are the new version control etiquette.
- **The human moves up a level.** Less typing, more deciding: setting intent, reviewing evidence and owning what ships.
- **Open ecosystems beat walled ones.** Skills that port across hosts and models, and that people can inspect, will outlast any single vendor's agent.

## 📬 Say hi

Interested in agent harnesses, skills or VS Code internals? Open an issue or a PR on any of the repos above, or find me at [orbyn.dev](https://orbyn.dev/).

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=kinqsradio&show_icons=true&hide_border=true&count_private=true" height="150" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kinqsradio&layout=compact&hide_border=true" height="150" alt="Top languages" />

</div>
