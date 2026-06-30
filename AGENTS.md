# AGENTS.md

Shared project guidance for coding agents. This repo holds GitHub organization/profile content, so keep changes conservative and easy to review.

## Project Shape

- Organization profile content lives in `profile/README.md`.
- Prefer Markdown and repository metadata changes over adding tooling.

## Operating Style

- Think before editing. Identify the audience and the exact rendered surface that will change.
- Keep copy concise, specific, and durable.
- Do not add broad automation or workflow files unless the user explicitly asks.

## Code Quality Bar

- Clean content means clear headings, direct language, working links, and no unnecessary decoration.
- DRY shared wording only when there is real repeated policy or brand language.
- Keep interfaces simple: Markdown content should render correctly on GitHub without custom build steps.

## Testability And Review

- Verify Markdown structure, links, and relative paths after editing.
- If generated assets or badges are introduced, document their source and expected update path.
- Avoid network-dependent badges or embeds unless the user wants them.

## Commands

- No default build or test command is defined.
