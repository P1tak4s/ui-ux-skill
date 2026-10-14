# ui-ux: one Claude Code skill for UI, UX and motion design

A single skill that covers the whole job of designing and building interfaces: choosing a
direction, typography, color, layout, components and states, UX copy, motion and animation,
UX laws, accessibility, AI-slop avoidance and a scored review method.

It is written so one skill is enough for any project, instead of loading separate taste,
design-critique, UX-rules and animation skills that overlap and contradict each other.
Where the source skills disagreed (exit easing, reduced motion, eyebrow labels, default fonts),
this skill picks one rule and states it.

## Install

```sh
git clone https://github.com/P1tak4s/ui-ux-skill.git
cp -r ui-ux-skill/ui-ux ~/.claude/skills/
```

Then ask Claude Code to build, redesign or review any UI, or run `/ui-ux`.

## Structure

```
ui-ux/
  SKILL.md                 operating manual: rules, workflow, quality floor, key numbers
  references/
    direction.md           brief reading, dials, product presets, design systems, redesign rules
    typography.md          scale, families, measure, details, loading
    color.md               strategies, OKLCH tokens, contrast, dark mode, data viz
    layout.md              spacing, grids, density, responsive, mobile, safe areas
    components.md          states, buttons, forms, nav, overlays, tables, empty/error, UX copy
    motion.md              when to animate, durations, easing, springs, patterns, perf, reduced motion
    polish.md              radius, depth, icons, images, interaction details
    anti-slop.md           visual, layout, copy and motion tells of generated UI
    laws.md                15 UX laws, Nielsen heuristics, Norman principles
    review.md              personas, scoring, severity, pre-ship checklist, hardening
```

`SKILL.md` stays short; Claude loads a reference file only when the task needs it.

## Credits

Rules here are rewritten and merged in my own words from these excellent open-source projects
and references. If you want the original depth, star and use them directly:

- [pbakaus/impeccable](https://github.com/pbakaus/impeccable) (Apache-2.0): direction contracts, surface modes, craft floor, critique scoring
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) (MIT): design dials, product presets, AI-slop tells, pre-flight checklist
- [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) (MIT): UX rules, forms, navigation, charts
- [emilkowalski/skills](https://github.com/emilkowalski/skills) (MIT): motion frequency gate, easing curves, interruptibility
- [kylezantos/design-motion-principles](https://github.com/kylezantos/design-motion-principles) (MIT): motion audit, anti-patterns, reduced motion
- [LottieFiles/motion-design-skill](https://github.com/LottieFiles/motion-design-skill) (MIT): motion personalities, durations, choreography
- [jakubkrehel/make-interfaces-feel-better](https://github.com/jakubkrehel/make-interfaces-feel-better) (MIT): concentric radius, optical alignment, micro-details
- [ibelick/ui-skills](https://github.com/ibelick/ui-skills) (MIT): baseline UI rules, motion performance
- [anthropics/skills](https://github.com/anthropics/skills): frontend-design direction thinking
- [vercel-labs/web-interface-guidelines](https://github.com/vercel-labs/web-interface-guidelines) (MIT): interface guidelines
- [Laws of UX](https://lawsofux.com) by Jon Yablonski, Nielsen Norman Group, Don Norman, WCAG 2.2

## License

MIT
