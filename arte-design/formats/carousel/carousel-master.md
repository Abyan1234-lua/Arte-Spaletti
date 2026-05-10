# FORMAT: Carousel — Master Logic

Use this template for: Instagram carousel posts, LinkedIn carousel documents,
educational swipe posts, product feature carousels, step-by-step guides,
listicle carousels, brand storytelling sequences.

---

## CAROUSEL OVERVIEW

A carousel is a **sequence of visually consistent slides** that tells a story,
teaches a concept, or presents information progressively.

ARTE-DESIGN generates **one GPT Image prompt per slide**, all sharing a unified
visual system so the carousel looks cohesive when swiped through.

---

## BEFORE BUILDING SLIDES: ESTABLISH THE SYSTEM

Before writing any individual slide prompt, define the **Carousel Visual System**
that all slides must share:

```
CAROUSEL VISUAL SYSTEM
──────────────────────
Canvas: {{canvas_size}} — all slides identical dimensions
Background: {{bg_color}} — same across all slides
Left accent bar: {{accent_bar_color}} — thin vertical stripe, left edge, all slides
Bottom brand strip: {{brand_strip_color}} — same flat band, bottom of every slide
Font zone style: {{text_zone_style}} — same treatment for text areas
Icon style: {{icon_style}} — same icon visual language
Color palette: {{primary}} / {{secondary}} / {{accent}}
Slide counter zone: Bottom-right, flat {{counter_bg}} circle, same position all slides
```

This system is declared ONCE then applied to every slide prompt.

---

## SLIDE COUNT LOGIC

| Carousel Type | Recommended Slides |
|---|---|
| Educational / How-to | 5–8 slides |
| Product feature showcase | 4–6 slides |
| Listicle (Top N tips) | N+2 slides (hook + tips + CTA) |
| Brand story / About us | 5–7 slides |
| Event recap | 6–10 slides |
| Testimonial collection | 4–6 slides |

Default if user doesn't specify: **5 slides**

---

## SLIDE SEQUENCE STRUCTURE

### Standard 5-Slide Sequence:
```
Slide 1: Hook         → load: slides/hook-slide.md
Slide 2: Content A    → load: slides/content-slide.md
Slide 3: Highlight    → load: slides/highlight-slide.md
Slide 4: Content B    → load: slides/content-slide.md
Slide 5: CTA          → load: slides/cta-slide.md
```

### Extended 7-Slide Sequence:
```
Slide 1: Hook
Slide 2: Content A
Slide 3: Content B
Slide 4: Highlight (stat or quote)
Slide 5: Content C
Slide 6: Content D
Slide 7: CTA
```

---

## OUTPUT STRUCTURE FOR CAROUSELS

```
╔══════════════════════════════════════════╗
  ARTE-DESIGN — CAROUSEL OUTPUT
  Topic: [topic]
  Platform: [platform]
  Slides: [count]
  Style: [preset]
╚══════════════════════════════════════════╝

── CAROUSEL VISUAL SYSTEM ────────────────
[Declare all shared variables here]

── SLIDE 1 / [count] — HOOK ──────────────
[Full GPT Image prompt]

── SLIDE 2 / [count] — CONTENT ──────────
[Full GPT Image prompt]

── SLIDE 3 / [count] — HIGHLIGHT ────────
[Full GPT Image prompt]

[...continue per slide...]

── CANVA EDITING NOTES ───────────────────
[Per-slide editing instructions]
```

---

## CANVA CONSISTENCY RULES FOR CAROUSELS

1. **Lock the left accent bar** — same width, same color, same position every slide
2. **Lock the bottom strip** — same height, same color, logo position consistent
3. **Lock slide counter position** — always bottom-right, same size circle
4. **Keep background identical** — same hex, same texture across all slides
5. **Text zone proportions** — headline zone same relative size per slide
6. **Icon style** — if using icons, same style (outline, filled, illustrated) throughout
7. **Typography** — user applies same font family to all slides in Canva

---

## SLOT REFERENCE (SYSTEM LEVEL)

| Slot | Example Values |
|---|---|
| `{{canvas_size}}` | 1080x1080px, 1080x1350px |
| `{{bg_color}}` | white #FFFFFF, navy #1E3A5F, black #050505 |
| `{{accent_bar_color}}` | brand blue, gold, coral |
| `{{brand_strip_color}}` | brand primary, dark navy, black |
| `{{text_zone_style}}` | flat white panel, transparent overlay, solid colored block |
| `{{icon_style}}` | thin outline circles, flat filled shapes, emoji-style |
| `{{primary}}` | brand primary hex |
| `{{secondary}}` | supporting color hex |
| `{{accent}}` | highlight color hex |
| `{{counter_bg}}` | white, accent color, brand primary |
