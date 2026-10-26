# Noice Tech skills

From “what if” to “it’s live.”

## Install

Requires a GitHub CLI version with `gh skill`:

```sh
gh skill install noice-tech/skills --all
```

Choose your agent when prompted. If installing individual skills, install `show-me` alongside `pr`.

## Usage

Invoke skills through your agent's skill commands. Agents can also select `pr` when you ask for commit, push, or pull request work. The other skills disable automatic selection on agents that support the included settings. Those settings do not restrict tool use or file access.

GitHub workflows require Git and an authenticated `gh`.

## Credits

MIT licensed.

- Lazy Ladder comes from Noice Pi and was inspired by [Ponytail](https://github.com/DietrichGebert/ponytail). It is not affiliated with Ponytail.
- Show-me comes from [humanlayer/skills](https://github.com/humanlayer/skills). See its [license](skills/show-me/LICENSE).
- Unslop comes from [backnotprop/pstack](https://github.com/backnotprop/pstack). See its [license](skills/unslop/LICENSE).
