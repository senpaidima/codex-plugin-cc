# Changelog

## 1.0.6

- Update the pinned companion default model from `gpt-5.5` to `gpt-5.6-sol` (OpenAI's flagship Sol tier, released 2026-07-09); default reasoning effort stays `xhigh`.
- Add `sol` model alias (`sol` -> `gpt-5.6-sol`) and accept `ultra` as a reasoning-effort value.
- Merge upstream v1.0.6 hardening: run git through `runCommand` with `shell: false` so repository-derived arguments never pass through a shell on Windows; `runCommand` now honors an explicit `options.shell`.

## 1.0.5

- Pin the companion runtime defaults to `gpt-5.5` and `xhigh`.
- Rename internal prompting guidance from GPT-5.4 to GPT-5.5.

## 1.0.0

- Initial version of the Codex plugin for Claude Code
