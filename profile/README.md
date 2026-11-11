# Entwining

Entwining builds tools for working with AI agents. Our projects grow out of everyday work with them. We’re interested in how people and agents share context, work through ideas, and learn from the process.

Human agency is part of that: understanding the work, contributing judgment, and shaping what happens next.

## Find and resume work

[Rexume](https://github.com/Entwining/rexume) reopens agent conversations in their Rex panes after the server restarts. It also returns worker results to the orchestrator.

[sessidx](https://github.com/Entwining/sessidx) searches local Claude Code, Codex, and Pi history. It also counts agent activity from session logs.

## Manage credentials and tool calls

[Maskey](https://github.com/Entwining/maskey) stores credentials in iCloud Keychain. Its `mk` command supplies them to commands as environment variables.

[Agent Guard](https://github.com/Entwining/agent-guard) checks Claude Code, Codex, and Pi tool calls on macOS. It blocks broad filesystem scans and recognizable credential reads.

[mods](https://github.com/Entwining/mods) provides Claude Code plugins built on function hooks. Its preallow plugin lets a model judge allow task steps in auto mode without the classifier.

## Extend and maintain the tools

[Pi Extensions](https://github.com/Entwining/pi-extensions) adds inline skill invocation, session IDs, tool-call guards, and a DeepSeek reasoning workaround to Pi. Each extension can be enabled independently.

[renovate-config](https://github.com/Entwining/renovate-config) shares dependency update rules across repositories. Its agent skill explains how to adapt the policy.

The [Homebrew tap](https://github.com/Entwining/homebrew-tap) installs Entwining tools on Apple Silicon macOS.

Use the [SVG logos or PNG avatars](https://github.com/Entwining/.github/blob/main/brand/README.md) when representing Entwining.

With support from OpenAI’s [Codex for Open Source](https://openai.com/form/codex-for-oss/) program.
