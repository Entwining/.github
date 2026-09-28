# Human in the Loop

LoopHubs is where I share useful tools that came out of working with AI coding agents.

`agent-guard` is a macOS pre-tool guard for Claude Code, Codex, and Pi. Broad filesystem searches can reach other apps' data under `~/Library` and trigger repeated permission prompts. The guard blocks these scans and recognizable credential reads before execution, then points to a safe alternative. It checks only tool calls routed through a registered hook.

Install with Homebrew:

```sh
brew install loophubs/tap/agent-guard
```

Then register the guard with your agent and verify that it blocks a test call. The [setup guide](https://github.com/LoopHubs/agent-guard/blob/main/docs/setup.md) covers both.

Built together with Claude Code, Codex, and Pi.

This project is supported by OpenAI's [Codex for Open Source](https://openai.com/form/codex-for-oss/) program.
