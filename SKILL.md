---
name: professional-app-design-skill
description: >-
  Applies eight visual design principles (contrast, hierarchy, alignment, proximity,
  repetition, balance, white space, unity) to build and polish app UI with AI.
  Use when designing or refining screens, critiquing layouts, improving visual polish,
  art directing UI, reviewing screenshots, or when the user mentions vibe-coded
  design, sterile UX, or wants a more professional look.
---

# Professional App Design

## Core Mindset

Design is applied abstraction — a science, not mysticism. "Good design" is tangible: people know it when they see it. Agents assemble patterns well but are hard to steer because **design is not code**. Agents have no eyes; they can only prepare ingredients. Treat first-pass output as a base, not a finished product.

**Polish** is persistence and taste meeting the science of design. Do not settle for utilitarian, feature-first layouts that look like every other vibe-coded app.

When the user provides a screenshot, critique and revise against the checklist below. When building from scratch, apply the checklist before presenting output.

## The Eight Principles

Use these as a critique and iteration vocabulary:

| Principle | What to check |
|-----------|---------------|
| **Contrast** | Elements distinguishable via size, color, weight, or shape. One clear focal point. Without contrast, everything competes equally. |
| **Hierarchy** | Content ordered by importance. Headlines before body. Primary actions visually distinct from secondary. Eye follows intended path. |
| **Alignment** | Shared edges and axes create order. Strong alignment is invisible; its absence looks sloppy immediately. |
| **Proximity** | Related items grouped, unrelated separated. White space between groups replaces borders. |
| **Repetition** | Consistent colors, fonts, shapes, spacing. A unified system users learn quickly. |
| **Balance** | Visual weight distributed intentionally. Symmetrical = stable; asymmetrical = dynamic. Unbalanced feels off. |
| **White space** | Content has room to breathe. Negative space is active — it signals premium, calm, or cluttered. |
| **Unity** | Every element belongs. Emerges when the other seven principles agree. Nothing arbitrary. |

## Workflow

### Building new UI

1. **Clarify brand intent** — mood, audience, primary conversion goal (one sentence).
2. **Define a design system before layout** — one typeface family, one accent color, spacing scale, corner radius, button style. Lock these first.
3. **Establish hierarchy tiers** — e.g. (1) hero + primary CTA, (2) section labels, (3) content cards.
4. **Build with generous white space** — default to more breathing room than feels necessary.
5. **Run the critique checklist** (below) before shipping.
6. **Add nuance beyond utilitarian UX** — recap states, micro-copy, atmospheric details that reinforce brand (not bare forms and lists).

### Critiquing existing UI (with or without screenshot)

1. Score each principle: ✅ strong, ⚠️ needs work, ❌ failing.
2. Identify the single biggest upgrade (often white space or hierarchy).
3. Propose specific, implementable fixes — not vague "make it prettier."
4. Revise and re-score until no ❌ remain and ⚠️ are intentional.

## Critique Checklist

Copy and fill when reviewing any screen:

```
Visual Design Critique
- [ ] Contrast — Is there one clear focal point? Do CTAs stand out surgically?
- [ ] Hierarchy — Can you name 2–3 tiers? Does the eye move in business priority order?
- [ ] Alignment — Do elements share consistent edges/axes?
- [ ] Proximity — Are related items grouped with space between groups?
- [ ] Repetition — One type system, one accent, consistent shapes/spacing?
- [ ] Balance — Is weight distributed top-to-bottom with intention?
- [ ] White space — Does it breathe? Any cramped stacks or dense cards?
- [ ] Unity — Does every choice reinforce the same brand idea?
```

## Implementation Heuristics

When translating principles to code/CSS:

- **Contrast**: One primary CTA style. Secondary actions quieter (outline, ghost, lower saturation). Avoid competing accent colors.
- **Hierarchy**: Use size steps (e.g. 2× between headline and body), weight, and color opacity — not four similar text sizes.
- **Alignment**: Pick one content width and margin system; align all sections to it.
- **Proximity**: Section padding ≥ 2× internal card padding. Separate hero from browse content.
- **Repetition**: Extract tokens (`--accent`, `--radius`, `--space-*`) and reuse; never one-off colors per component.
- **Balance**: Hero or primary content gets commanding space; supporting content anchors without dominating.
- **White space**: Increase padding/margin before adding borders or backgrounds to separate content.
- **Unity**: Photography treatment, accent hue, and corner radius should match across the screen.

## Anti-Patterns (Utilitarian AI Design)

Reject or upgrade these defaults:

- Feature lists with no brand atmosphere or emotional hook
- Multiple competing accent colors (blue icons + orange text + unrelated photo treatments)
- Dense card stacks with no section breathing room
- Every pixel "working" — cluttered wellness/productivity apps that feel anxious
- Bare checkout/booking flows with no recaps or reassurance
- Template layouts with content poured in — inconsistent type, spacing, and imagery

Treat agent output as **V1**. Polish to **V2** using the principles.

**Calibration reference:** Read [v1-v2-reference.png](v1-v2-reference.png) and [examples.md](examples.md) before critiquing hero + experiences + bottom-nav layouts. FIRE + FLOE V1 (blocky stack, dense copy, blue/orange accents) → V2 (full-bleed hero, Book now CTA, horizontal cards, floating pill nav) is the target quality gap.

## Output Format

When critiquing, use this structure:

```markdown
## Visual design review

**Brand intent:** [one line]
**Biggest issue:** [principle name + one sentence]

### Principle scores
| Principle | Score | Notes |
|-----------|-------|-------|
| Contrast | ⚠️ | ... |
...

### Recommended changes (priority order)
1. [Specific change + why]
2. ...

### Design system to lock
- Type: ...
- Accent: ...
- Spacing: ...
- Radius: ...
```

When implementing fixes, state which principles each change addresses.

## Additional Resources

- **Reference image:** [v1-v2-reference.png](v1-v2-reference.png) — side-by-side V1 vs V2 (FIRE + FLOE wellness app)
- **Case study:** [examples.md](examples.md) — per-principle analysis and transformation checklist
