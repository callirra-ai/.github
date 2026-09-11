# Contributing to Callirra repositories

Thanks for helping. This guide is the default for repositories in this
organization; the [prompt atlas](https://github.com/callirra-ai/gpt-image-2-5-prompt-atlas/blob/main/CONTRIBUTING.md)
has a more specific one for prompt submissions.

## Prompt libraries (prompt atlas, `awesome-*`)

- One prompt per entry, **shipped together with the frame it produced** — a prompt without its output is not reviewable.
- Prompts in English, self-contained, and free of third-party trademarks you do not own.
- When a prompt was collected from the community, credit the original author and link the source.
- Prefer a small, reviewable pull request over a bulk dump; these lists are curated, not exhaustive.
- Video entries: keep clips short, and use the repository's existing folder structure (prompt file + preview asset).

## Code (CLI, MCP server, agent skill)

- Open an issue first for anything larger than a bug fix.
- Node 22+ for the CLI/MCP packages, Python 3.10+ for the skill.
- Keep dependencies minimal; never commit API keys, tokens, cookies or customer data.
- Run the package's own checks before opening a pull request (`pnpm test`, `pnpm typecheck`).
- Bug reports: include the command you ran, the version (`npm ls -g @callirra/cli`), and the full error output with secrets redacted.

## House rules

- English only. Be specific: what you expected, what happened, how to reproduce it.
- No marketing, pricing or feature-request debates in issues — mail support@callirra.com instead.
- We may close contributions that do not follow the structure above; it is not personal.
