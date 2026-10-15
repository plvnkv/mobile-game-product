# Mobile Game Product

A Codex skill that turns mobile game ideas into clear product documentation for developers and AI agents.

## What it does

- Guides discovery one question at a time; no completed input form is required.
- Covers gameplay, UX, visual direction, technology constraints, MVP scope, and monetization.
- Uses Expo + React Native as the default stack while respecting explicit alternatives.
- Discusses the idea in your preferred language and writes final project documents in English.
- Reviews assumptions, consistency, player journeys, and acceptance criteria before handoff.
- Stops at product documentation, without implementing code or creating programming plans.

## Install

Clone this repository into your Codex skills directory:

```sh
git clone https://github.com/plvnkv/mobile-game-product.git "${CODEX_HOME:-$HOME/.codex}/skills/mobile-game-product"
```

If the destination already exists, review it before replacing anything.

## Use

Invoke `$mobile-game-product` in Codex and describe your game idea. You may supply complete, partial, or no initial details; the skill asks for meaningful missing information.

Example:

> Use $mobile-game-product to help me define a mobile puzzle game with short daily sessions. I have not decided on monetization yet.

By default, product documents are saved under `docs/product/` in your project. Existing documentation structures are respected.

See [SKILL.md](SKILL.md) for the complete workflow.
