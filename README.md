# skill-authoring

Two agent skills for keeping your other skills sharp — vendored from [dzhng/skills](https://github.com/dzhng/skills) (MIT):

| Skill | What it does |
|---|---|
| [write-skills](skills/write-skills/SKILL.md) | Create or revise agent skills: triggers, leading words, progressive disclosure, information hierarchy, and the failure modes to prune (premature completion, embargo, sediment, war stories, no-ops). |
| [eval-skills](skills/eval-skills/SKILL.md) | Eval a skill against golden cases — blind runs in fresh context-free subagents, a separate judge grading against a bar (not a checklist), and gap-driven edits. |

They pair: `eval-skills` finds the gaps, `write-skills` carries the principles every fix obeys. Both complement interactive skill-creation tooling (e.g. Anthropic's skill-creator) — these carry the judgment layer, not the eval harness.

## Install

```bash
npx skills add avivsinai/skill-authoring -g
```

Or via the [avivsinai marketplace](https://github.com/avivsinai/skills-marketplace) for Claude Code:

```
/plugin marketplace add avivsinai/skills-marketplace
/plugin install skill-authoring@avivsinai-marketplace
```

## Provenance

Authored by [David Zhang](https://github.com/dzhng) in [dzhng/skills](https://github.com/dzhng/skills); vendored with attribution under MIT, with light adaptations: routing-focused descriptions (clear boundary vs skill-creator) and three small clarity/licensing fixes (inputs-to-settle framing, package-README scope, license-notice preservation). Packaging by [Aviv Sinai](https://github.com/avivsinai).

## License

MIT — see [LICENSE](LICENSE) (preserves upstream copyright).
