# V1 → V2 Reference Case Study

**Reference image:** [v1-v2-reference.png](v1-v2-reference.png)

Side-by-side mockups of the same app — **FIRE + FLOE**, a wellness brand offering sauna and cold plunge on Bainbridge Island. V1 is typical agent output; V2 is the same screen after applying the eight principles. Read the image when calibrating critiques for hero + experiences + bottom-nav layouts.

## Visual Overview

### V1 (left) — utilitarian base

- **Hero:** Rectangular photo block (people in water). Centered bold wordmark "FIRE + FLOE", tagline, and orange location text stacked on the image.
- **Content:** "Our Experiences" section with one large vertical card — B&W sauna photo, title, orange category tag, dense paragraph of body copy.
- **Nav:** Full-width dark bar, four icons. Home highlighted in **blue**; checkout cart in orange.
- **Feel:** Blocky vertical stack, text-heavy, mixed photo treatments, no primary CTA. Reads like a template with content poured in.

### V2 (right) — polished professional

- **Hero:** Full-bleed nighttime sauna photo. Wordmark top-left; profile icon top-right. Centered flame logo, concise tagline, white **"Book now"** pill CTA.
- **Content:** "Experiences" label + **horizontal scrolling** color photo cards. Title + price only ("$32/person") — no paragraph on the card.
- **Nav:** Floating semi-transparent **pill** bar. Home active state in **warm orange** with subtle glow. "Cart" instead of "Checkout."
- **Feel:** Immersive, premium, calm. Visual storytelling over dense copy. Clear conversion path.

## Per-Principle Analysis

### Contrast

**V1:** B&W card photo clashes with warm color hero. Blue nav highlight, orange location text, orange cart — multiple accents, no single focal point.

**V2:** One white "Book now" pill on dark atmospheric background — the only obvious primary action. Orange nav state is warm and quiet; doesn't compete with the CTA.

**Takeaway:** Use contrast surgically for the one action that matters most.

### Hierarchy

**V1:** Wordmark, tagline, location, "Our Experiences," card title, and body paragraph all compete.

**V2:** Three crisp tiers:
1. Hero atmosphere + tagline + Book now
2. "Experiences" section label
3. Cards (name + price)

Eye path: mood → conversion → browse.

**Takeaway:** Name tiers explicitly before coding. Cut card copy to what browse mode needs.

### Alignment

**V1:** Acceptable for a simple single-column layout — no major alignment errors.

**V2:** Same lateral alignment structure; adds top bar (wordmark left, profile right) without breaking the grid.

**Takeaway:** Alignment is often fine in simple UIs. Invest polish budget elsewhere.

### Proximity

**V1:** Tagline, location, and wordmark crammed on hero. Hard cut from hero into a dense single card.

**V2:** Hero owns brand + mood only. Experiences live below with clear separation. Cards are compact peers in a horizontal row.

**Takeaway:** Separate concerns with vertical space and section breaks, not more chrome.

### Repetition

**V1:** Mixed weights, blue + orange accents, B&W vs color photography, rectangular hero block vs rounded nothing else.

**V2:** One type family, consistent rounded pills (CTA, nav bar, card corners), warm orange as sole accent, full-color photography throughout.

**Takeaway:** Lock tokens first: `--accent`, `--radius-pill`, photo treatment, nav shape.

### Balance

**V1:** Bottom-heavy — one giant text-dense card dominates; hero feels truncated.

**V2:** Asymmetrical balance — commanding hero top, CTA as visual fulcrum, horizontal cards anchor the bottom without overwhelming.

**Takeaway:** Distribute weight top-to-bottom with intention.

### White Space

**V1:** Biggest failure. Text on photo, dense card, four-icon nav — every pixel working. Feels anxious, not restorative.

**V2:** Dark space around logo, CTA, section label, and between cards. Breathing room *is* the brand promise.

**Takeaway:** When in doubt, add space before adding structure. Remove copy before adding UI.

### Unity

**V1:** Generic wellness template.

**V2:** Nighttime hero, warm orange, rounded pills, horizontal scroll, consistent margins — all say quiet, premium, nature-based contrast therapy.

**Takeaway:** Unity emerges when the other seven principles agree.

## V1 → V2 Transformation Checklist

Use when upgrading agent output to professional polish:

```
Structure
- [ ] Full-bleed hero (not rectangular photo block)
- [ ] Primary CTA on hero ("Book now" pill)
- [ ] Horizontal card carousel (not one vertical text-heavy card)
- [ ] Floating pill nav (not full-width bar)

Content
- [ ] Card shows title + price only (move description to detail screen)
- [ ] Tagline shortened to one line on hero
- [ ] Location moved off hero or de-emphasized

System
- [ ] One accent color (warm orange) — drop blue nav highlight
- [ ] Consistent photo treatment (full color throughout)
- [ ] Rounded pills reused for CTA, nav, and cards
- [ ] Profile/account affordance in header (signals real app, not demo)
```

## Beyond Layout: Booking UX Nuance

The initial booking flow was bare and utilitarian. V2-level polish also means booking recaps throughout checkout — reassurance and continuity, not just form fields. Feature-complete ≠ conversion-ready.
