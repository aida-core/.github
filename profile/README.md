# AIDA — Agentic Intelligence Digital Assistant

> Build a Claude Code experience that's actually *yours* — without reinventing the plumbing every time.

AIDA is an open framework for extending [Claude Code](https://claude.com/claude-code) with consistent, composable patterns. Instead of every team rebuilding scaffolding, configuration, and session memory from scratch, AIDA gives you the foundation — and a marketplace of plugins that build on it.

## What you get

- **Extension scaffolding** — guided templates for agents, skills, and plugins so they share conventions out of the box
- **Multi-level configuration** — user-level defaults, project-level overrides, environment auto-detection
- **Structured session context** — *mementos* that capture rich project state, scoped per-project or per-user, so Claude Code starts every session informed
- **Health & diagnostics** — built-in self-checks, troubleshooting, and feedback channels
- **One-line install** — everything ships through the AIDA marketplace; opt into the plugins you want

## Get started

```bash
# Add the AIDA marketplace (one-time)
/plugin marketplace add aida-core/aida-marketplace

# Install the foundation plugin
/plugin install aida-core@aida

# Configure AIDA for your project
/aida config
```

Full guides live in the [`aida-core-plugin`](https://github.com/aida-core/aida-core-plugin) repo.

## What's in the org

| Repo | Purpose |
|---|---|
| [`aida-marketplace`](https://github.com/aida-core/aida-marketplace) | The plugin marketplace — canonical list of AIDA plugins |
| [`aida-core-plugin`](https://github.com/aida-core/aida-core-plugin) | Foundation plugin: scaffolding, config, mementos, health |
| *more plugins coming* | SDLC tooling, release management, and more — see [open issues](https://github.com/aida-core/aida-core-plugin/issues) |

## Why we're building this

Every team customizes Claude Code the same way: a folder of half-documented prompts, a `CLAUDE.md` that drifts, agents copy-pasted between projects, no shared vocabulary. That works — until you want to share, reuse, or upgrade.

AIDA's bet is that the *plumbing* — the boring parts — should be standardized so the *interesting* parts (the agents, skills, and workflows that solve your real problems) become portable, shareable, and built on each other. The goal is a Claude Code experience where extending the assistant feels less like wiring shell scripts and more like installing a package.

## Vision

A healthy ecosystem of plugins, built on consistent foundations, that lets every team start from "configure" instead of "from scratch." Plugins compose. Conventions are shared. Upgrades are predictable. Your customizations follow you between projects and survive across Claude Code versions.

## Contributing

Bug reports, feature requests, and PRs are welcome — each plugin lives in its own repo under this org, so file issues there.

- [Contributing guide](https://github.com/aida-core/.github/blob/main/CONTRIBUTING.md)
- [Code of Conduct](https://github.com/aida-core/.github/blob/main/CODE_OF_CONDUCT.md)
- [Security policy](https://github.com/aida-core/.github/blob/main/SECURITY.md)
- [Support](https://github.com/aida-core/.github/blob/main/SUPPORT.md)

## License

AIDA repos are MPL-2.0 licensed unless otherwise noted in the individual repo.
