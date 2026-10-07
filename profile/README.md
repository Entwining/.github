# Entwining

Open-source tools for people and AI to build together.

The name comes from *entwine*, meaning to weave together. These projects grow out of day-to-day work with coding agents, and help make that work easier to follow and build on.

We care about human agency: helping people understand the work and take an active part in shaping it.

## Projects

### [Agent Guard](https://github.com/Entwining/agent-guard)

A macOS guard that checks tool calls before execution in Claude Code, Codex, and Pi. It blocks broad filesystem scans that can reach other apps' data under `~/Library` and trigger repeated permission prompts, along with recognizable credential reads. It only covers calls routed through a registered hook.

Install with Homebrew, then [register the hook and verify it](https://github.com/Entwining/agent-guard/blob/main/docs/setup.md):

```sh
brew install entwining/tap/agent-guard
```

### [sessidx](https://github.com/Entwining/sessidx)

Find past Claude Code, Codex, and Pi sessions, inspect what happened, and count commands, tool failures, and denials. sessidx uses a rebuildable SQLite index and leaves the source logs unchanged. The index contains session data, so keep it private.

```sh
brew install entwining/tap/sessidx
```

See the [README](https://github.com/Entwining/sessidx#use) for usage and the [CLI reference](https://github.com/Entwining/sessidx/blob/main/docs/cli.md) for the full command contract.

The Homebrew packages target Apple Silicon macOS.

Built with Claude Code, Codex, and Pi.

Agent Guard is supported by OpenAI's [Codex for Open Source](https://openai.com/form/codex-for-oss/) program.
