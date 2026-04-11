# No-Slop Writing

A writing skill that eliminates AI-generated slop from business communication.

## What This Is

A system prompt and writing guardrail that catches the 13 most common patterns making AI-written text obvious. Paste it into Claude, ChatGPT, or any LLM. Your output comes out clean.

## The 13 Anti-Patterns It Catches

1. "Delve into" and "Unpack"
2. "This signals that" and "This underscores"
3. "Navigate the complexities" and "ever-changing landscape"
4. "Synergies," "leverage our learnings," "holistic approach"
5. Stacking vague abstractions into one sentence
6. Transition word addiction (Moreover, Furthermore, Additionally)
7. Bold word: colon: explanation bullet points
8. Corporate therapist voice
9. The neat little bow conclusion
10. Says everything, means nothing
11. Forced negation ("not this but that") on repeat
12. Staccato repetitions ("not this, or this, or this but that")
13. Excessive adverbs ("quietly underscores," "powerfully demonstrates")

## Regional Variants

This repo uses **Australian English**. An American English version is at [github.com/Speedrunlab/no-slop-writing](https://github.com/Speedrunlab/no-slop-writing).

## Installation

**Claude:** Save `SKILL.md` to your `.claude/skills/` directory or `/mnt/skills/user/no-slop-writing/`. Claude applies the rules automatically.

**ChatGPT:** Copy the content of `SKILL.md` and paste it into Settings > Personalisation > Custom Instructions.

**Any LLM:** Include the file as a system prompt. Works with OpenRouter, Anthropic API, OpenAI API, Google AI, or any OpenAI-compatible endpoint.

## Examples

See the `examples/` folder for a before-and-after comparison showing the skill in action.

## Credits

Inspired by an internal memo on AI writing patterns shared by Leila Hormozi of Acquisition.com. Built by [Speedrun AI Labs](https://speedrunlab.ai), Sydney, Australia.

## Licence

MIT


---

## Part of the Speedrun AI Labs Skill Library

This skill is part of the open-source skill library at [speedrunlab.ai](https://www.speedrunlab.ai).

Other skills:
- [/deep-audit](https://github.com/Speedrunlab/deep-audit) — four-phase code auditor with evidence standards
- [/no-slop-writing](https://github.com/Speedrunlab/no-slop-writing) — eliminates AI-speak from generated text (American English)
- [/no-slop-writing-au](https://github.com/Speedrunlab/no-slop-writing-au) — same, Australian English edition
- [/read-before-write](https://github.com/Speedrunlab/read-before-write) — forces AI agents to read files before editing them
