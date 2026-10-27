# ux-laws — a Claude Code skill

Applies ~65 laws and principles of UX (Fitts, Hick, Jakob, Miller, Tesler, Postel, Peak-End, Von Restorff, Zeigarnik, all Gestalt laws, cognitive load, progressive disclosure, information scent, affordances, behavioural biases), plus Nielsen's 10 heuristics and John Maeda's 10 Laws of Simplicity, to design or review an interface.

## What it does

- **Audit mode** — for a screenshot, URL, component or flow: name the user's job, find symptoms, map them to laws via a symptom → law table, report the top findings as *what / law / fix / cost*.
- **Design mode** — nine questions to answer before drawing a screen (the one thing, how many choices, conventions, memory load, order, grouping, where complexity goes, response time, the ending).
- **Collisions** — where laws pull against each other (Hick vs Tesler, Jakob vs Von Restorff, Fitts vs Proximity…).

## Files

| File | Contents |
|---|---|
| `SKILL.md` | Workflow, symptom → law map, design questions, collisions |
| `references/perception.md` | Gestalt, emphasis, hierarchy, scanning, attention (17) |
| `references/cognition.md` | Memory, load, chunking, order, mental models, biases (16) |
| `references/decisions.md` | Choices, conventions, complexity, persuasion (19) |
| `references/interaction.md` | Targets, speed, feedback, affordances, errors, progress (12) |
| `references/heuristics.md` | Nielsen's 10 heuristics |
| `references/simplicity.md` | Maeda's 10 Laws of Simplicity + a simplification pass |

## Install

```sh
git clone https://github.com/ivstefano/ux-laws ~/.claude/skills/ux-laws
```

Then in Claude Code ask to review a screen, or type `/ux-laws`.

## Sources

The core 30 follow the selection on [lawsofux.com](https://lawsofux.com) by Jon Yablonski; additions come from Gestalt psychology, Don Norman, Jakob Nielsen, Kahneman, Cialdini and John Maeda. All descriptions are original summaries.

## License

MIT
