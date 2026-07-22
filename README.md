# Vegeta (Dragon Ball Z) — OpenPeon Sound Pack

Prince of all Saiyans voice notifications for [peon-ping](https://github.com/PeonPing/peon-ping) — audible cues for Claude Code, Codex, IDEs, and any AI agent. Stop babysitting your terminal. Employ the Prince.

> "Now I'm going to show you what true power really is."

## Install

Once this pack is listed in the [OpenPeon registry](https://github.com/PeonPing/registry), install it with:

```bash
peon pack install vegeta_dbz
```

Or install directly from this repo:

```bash
peon pack install alexlupu3/openpeon-vegeta-dbz
```

## What plays when

| Category           | When it plays                         | Example line |
| ------------------ | ------------------------------------- | ------------ |
| `session.start`    | Session starts (`$ claude`)           | "Let's go" |
| `task.acknowledge` | Claude acknowledges a task            | "So be it" |
| `task.complete`    | Claude finishes and is idle           | "It's over 9000!" |
| `task.error`       | Something fails                       | "So you still think I'm bluffing?" |
| `input.required`   | Claude needs tool approval            | "Is this what you want?" |
| `resource.limit`   | Resource limits hit                   | "I come to tell you, your time is up" |
| `user.spam`        | User spams prompts (3+ in 10 seconds) | "Didn't anyone teach you any manners?" |

Each category holds several clips; peon-ping picks one at random, so it stays fresh.

## Contents

41 voice clips, MP3, all under 1 MB (≈3 MB total). See [`openpeon.json`](openpeon.json) for the full mapping.

## Credits

- Voice: Vegeta, from *Dragon Ball Z* / *Dragon Ball Super*. Christopher Sabat (English dub).
- Pack assembled by [Alex Lupu](https://github.com/alexlupu3).

## License

Pack manifest, structure, and tooling are released under the [MIT License](LICENSE).

The audio clips are voice lines from *Dragon Ball Z* / *Dragon Ball Super*, © Toei Animation / Funimation / their respective rights holders. They are included here for non-commercial, fan/hobbyist use only. This project is not affiliated with or endorsed by the rights holders. If you own the rights and want a clip removed, open an issue.
