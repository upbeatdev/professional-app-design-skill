# Professional App Design Skill

An Agent Skill for bringing professional visual design quality to AI-built apps.

## Reference

This skill is based on the following article by Expo:

**[How to apply professional design principles in AI app development](https://expo.dev/blog/how-to-apply-professional-design-principles-in-ai-app-development)**

The eight visual design principles from the article (contrast, hierarchy, alignment, proximity, repetition, balance, white space, unity) and the V1 → V2 transformation approach are codified in this skill.

## What it does

AI agents tend to produce feature-focused, functional but sterile interfaces. This skill helps the agent:

- Lock in a design system before laying out new UI
- Critique existing screens against the eight principles
- Transform V1 (raw output) into V2 (polished, professional)
- Improve visual quality when a screenshot is provided

## Files

| File | Description |
|------|-------------|
| `SKILL.md` | Main skill — principles, checklist, workflow, output format |
| `examples.md` | FIRE + FLOE V1/V2 case study and transformation checklist |
| `v1-v2-reference.png` | Side-by-side V1 vs V2 reference image |

## Installation

### Personal (all projects)

```bash
git clone https://github.com/upbeatdev/professional-app-design-skill.git ~/.cursor/skills/professional-app-design-skill
```

### Project-scoped (shared with the repo)

```bash
git clone https://github.com/upbeatdev/professional-app-design-skill.git .cursor/skills/professional-app-design-skill
```

## Usage

Trigger the skill in Cursor by:

- Invoking it directly: `@professional-app-design-skill`
- Asking naturally: "polish this screen", "critique this UI", "make this look less vibe-coded"

The agent reads `v1-v2-reference.png` first to calibrate against the FIRE + FLOE quality gap.

## Eight Principles (summary)

1. **Contrast** — One clear focal point; CTA stands out surgically
2. **Hierarchy** — Content ordered by importance; the eye follows the intended path
3. **Alignment** — Shared edges and axes create order
4. **Proximity** — Related items grouped; unrelated ones separated
5. **Repetition** — Consistent color, type, shape, and spacing system
6. **Balance** — Visual weight distributed with intention
7. **White space** — Content breathes; signals premium, calm, or clutter
8. **Unity** — Every element reinforces the same brand idea

## License

MIT (update as needed)

## Acknowledgments

- [Expo](https://expo.dev) — for [How to apply professional design principles in AI app development](https://expo.dev/blog/how-to-apply-professional-design-principles-in-ai-app-development)
