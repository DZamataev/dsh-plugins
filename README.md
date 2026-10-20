# dsh-plugins

Local plugin bundles for [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) (DSH).

| Bundle | What it does |
|---|---|
| [provider-limits](provider-limits/) | Remaining quota of TeamClaude, codex-lb, and OpenCode Go provider routes, plus upstream status, in a pill under the composer. |

## Install

Each directory is a self-contained bundle. Install it into the current profile from inside DSH (ask the agent to run `plugin_manager install_bundle` with the absolute bundle path), or link it into a profile as a local directory bundle.
