# RIA Systems — Claude Code plugins

Marketplace catalog for [Claude Code](https://claude.com/claude-code) plugins maintained by [RIA Systems](https://github.com/riasistemas), a verified Meta Tech Provider.

## Available plugins

| Plugin | What it does | Repo |
| --- | --- | --- |
| [`whatsapp`](https://github.com/riasistemas/claude-channel-whatsapp) | Paste a WhatsApp conversation and get a reply drafted, a lead read and a next step. Skills only, works on every Claude app. | `riasistemas/claude-channel-whatsapp` |
| [`whatsapp-local`](https://github.com/riasistemas/claude-channel-whatsapp/tree/local) | WhatsApp channel for Claude Code with your own Meta app: inbound messages, replies through the official Cloud API, pairing and allowlists. The local channel that shipped as `whatsapp` up to v0.1.10. | `riasistemas/claude-channel-whatsapp` (branch `local`) |
| [`instagram`](https://github.com/riasistemas/claude-channel-instagram) | Paste an Instagram DM or comment and get a reply drafted, a lead read and a next step. Skills only, works on every Claude app. | `riasistemas/claude-channel-instagram` |
| [`instagram-local`](https://github.com/riasistemas/claude-channel-instagram/tree/local) | Instagram channel for Claude Code with your own Meta app: inbound comments and DMs, replies through the official Instagram API. The local channel that shipped as `instagram` up to v0.3.5. | `riasistemas/claude-channel-instagram` (branch `local`) |

## Installation

Add this catalog as a plugin marketplace **once**:

```
/plugin marketplace add riasistemas/claude-plugins
```

Then install plugins individually:

```
/plugin install whatsapp@riasistemas
/plugin install whatsapp-local@riasistemas
/plugin install instagram@riasistemas
/plugin install instagram-local@riasistemas
/reload-plugins
```

Each plugin lives in its own repository — releases, issues, and pull requests are tracked there. This catalog only points at them.

## Submitting issues

For plugin-specific bug reports or feature requests, please open an issue **on the plugin's repository**, not this one. Quick links:

- [`whatsapp` issues](https://github.com/riasistemas/claude-channel-whatsapp/issues)
- [`instagram` issues](https://github.com/riasistemas/claude-channel-instagram/issues)

For catalog-level issues (e.g. a plugin missing from this list), open an issue here.

## License

Each plugin is independently licensed (currently all Apache-2.0). This catalog itself is published under the same.
