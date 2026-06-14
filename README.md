# RIA Systems — Claude Code plugins

Marketplace catalog for [Claude Code](https://claude.com/claude-code) plugins maintained by [RIA Systems](https://github.com/riasistemas), a verified Meta Tech Provider.

## Available plugins

| Plugin | What it does | Repo |
| --- | --- | --- |
| [`whatsapp`](https://github.com/riasistemas/claude-channel-whatsapp) | Connect a WhatsApp Business number to Claude Code via the official Cloud API. Reply, react, transcribe audio, manage pairing/allowlist. | `riasistemas/claude-channel-whatsapp` |
| [`instagram`](https://github.com/riasistemas/claude-channel-instagram) | Connect an Instagram Business account to Claude Code via the official Graph API. Read and reply to comments. | `riasistemas/claude-channel-instagram` |
| [`hermes-tweet`](https://github.com/Xquik-dev/hermes-tweet) | Use Hermes Agent for X/Twitter research, profile and tweet lookup, and opt-in posting workflows. | `Xquik-dev/hermes-tweet` |

## Installation

Add this catalog as a plugin marketplace **once**:

```
/plugin marketplace add riasistemas/claude-plugins
```

Then install plugins individually:

```
/plugin install whatsapp@riasistemas
/plugin install instagram@riasistemas
/plugin install hermes-tweet@riasistemas
/reload-plugins
```

Each plugin lives in its own repository — releases, issues, and pull requests are tracked there. This catalog only points at them.

## Submitting issues

For plugin-specific bug reports or feature requests, please open an issue **on the plugin's repository**, not this one. Quick links:

- [`whatsapp` issues](https://github.com/riasistemas/claude-channel-whatsapp/issues)
- [`instagram` issues](https://github.com/riasistemas/claude-channel-instagram/issues)
- [`hermes-tweet` issues](https://github.com/Xquik-dev/hermes-tweet/issues)

For catalog-level issues (e.g. a plugin missing from this list), open an issue here.

## License

Each plugin is independently licensed. This catalog itself is published under Apache-2.0.
