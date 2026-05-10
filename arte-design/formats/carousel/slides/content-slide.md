# CAROUSEL SLIDE: Content Slide (Middle Slides)

Content slides deliver the actual value — information, steps, tips, features,
or story beats. They must feel visually consistent with the hook slide but
contain cleaner, more readable layouts for text-heavy content.

---

## PROMPT TEMPLATE

```
Social media carousel slide {{slide_number}} of {{total_slides}}, content slide,
{{canvas_size}}, {{platform}} format. Part of a cohesive {{style_preset}}
visual series — must match slide 1 background and system exactly.

BACKGROUND: Flat {{bg_color}} background — identical to all other slides in
this carousel. No variation. {{bg_pattern}} very subtle background pattern
if applicable, same as other slides.

LEFT ACCENT BAR: Thin vertical rectangle, {{accent_bar_width}}px wide,
full canvas height, left edge, flat {{accent_bar_color}} fill.
Identical to all other slides.

SLIDE NUMBER INDICATOR: Top-left area near accent bar — small flat
{{slide_num_bg}} rounded rectangle or pill shape, open interior for slide
number label. No text rendered.

CONTENT LAYOUT: {{layout_style}} — choose based on content type:

  LAYOUT A — "Icon + Text" (for tips, steps, features):
  Left zone: large flat {{icon_zone_color}} circle or square shape,
  {{icon_size}}% of canvas width, centered vertically at upper portion.
  Clean interior for icon or number overlay. Right zone: flat open area,
  {{text_zone_bg}}, multiple horizontal flat strips of varying width
  stacked vertically for headline + body copy rows. No text rendered.

  LAYOUT B — "Full Text Block" (for quotes, single insight):
  Center zone: large flat {{text_block_bg}} panel, {{text_block_size}}%
  canvas area, clean interior. Optional thin {{text_block_border}} border.
  Top of panel: small flat icon or decorative element placeholder.
  Interior: flat for text overlay. No text rendered.

  LAYOUT C — "Visual Left, Text Right" (for comparisons, examples):
  Left 45%: {{visual_element}} visual, {{visual_style}} treatment.
  Right 55%: flat {{text_right_bg}} panel, stacked horizontal text bars
  for headline + bullet points. No text rendered.

  LAYOUT D — "Step-by-step" (numbered list):
  Vertical stack of {{step_count}} flat horizontal rows, each row:
  flat {{step_number_bg}} circle on left with flat interior for step number,
  flat text bar extending right across remaining width. Alternating
  {{step_row_a}} and {{step_row_b}} subtle row background tints.
  No text rendered.

BOTTOM BRAND STRIP: Full-width bottom band, {{brand_strip_height}}px,
flat {{brand_strip_color}} fill. Left: logo zone placeholder. Right: flat
{{counter_bg}} circle for slide number. Identical to all slides.

SWIPE INDICATOR: Right edge center — small flat {{swipe_icon_color}} chevron
arrow pointing right. Present on all slides except last.

COLOR PALETTE: {{primary_color}}, {{accent_color}}, {{neutral_color}}.
No new colors introduced — strictly carousel system palette.

STYLE: Clean {{style_preset}} layout, optimized for text readability,
consistent with carousel system, no text rendered, no icons with embedded
text, no watermark.

CANVAS: {{canvas_size}}
```

---

## LAYOUT SELECTION GUIDE

| Content Type | Recommended Layout |
|---|---|
| Tips / Advice | Layout A (icon + text) |
| Key insight / Quote | Layout B (full text block) |
| Comparison / Example | Layout C (visual + text) |
| Steps / Process | Layout D (step-by-step) |
| Feature explanation | Layout A or C |
| Data / Statistics | Layout B with large number placeholder |

---

## SLOT REFERENCE

| Slot | Example Values |
|---|---|
| `{{layout_style}}` | LAYOUT A, B, C, or D |
| `{{icon_zone_color}}` | accent blue, gold, brand primary |
| `{{icon_size}}` | 25, 30 (% of canvas width) |
| `{{text_zone_bg}}` | white, very light bg color |
| `{{text_block_bg}}` | white panel, accent color |
| `{{text_block_size}}` | 70, 80 (% of canvas) |
| `{{text_block_border}}` | accent color thin border, none |
| `{{visual_element}}` | photo, illustration, icon graphic |
| `{{visual_style}}` | photorealistic, flat illustration |
| `{{text_right_bg}}` | white, very light |
| `{{step_count}}` | 3, 4, 5 |
| `{{step_number_bg}}` | accent color, brand primary |
| `{{step_row_a}}` | transparent |
| `{{step_row_b}}` | very subtle tint #F8F9FA |
| `{{slide_num_bg}}` | accent color, brand primary |
