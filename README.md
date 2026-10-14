# ui-ux: a Claude Code skill with the UI/UX laws that matter

The 15 most practical laws from [Laws of UX](https://lawsofux.com), Nielsen's 10 heuristics,
Don Norman's interaction principles and hard accessibility numbers, written as rules an
agent can apply while building or reviewing an interface.

Each law has: the rule, what to do in code, and the most common violation.
It also includes a pre-build question list, a review checklist and a refusal list for dark patterns.

## Install

```sh
git clone https://github.com/P1tak4s/ui-ux-skill.git
cp -r ui-ux-skill/ui-ux ~/.claude/skills/
```

Then in Claude Code: `/ui-ux` or just ask for a UI build or UX review; the skill triggers on its own.

## What is inside

Jakob, Hick (+ Choice Overload), Fitts, Cognitive Load / Miller / Chunking, Doherty Threshold,
Gestalt grouping, Von Restorff, Tesler, Postel, Peak-End, Goal-Gradient, Zeigarnik,
Serial Position, Aesthetic-Usability, Pareto.

Left out on purpose (overlap or rarely change a decision): Occam's Razor, Parkinson's Law,
Flow, Prägnanz, Cognitive Bias as a general category.

## License

MIT
