# CAROUSEL SLIDE: Highlight Slide

The highlight slide breaks the rhythm of content slides with a visually
punchy, single-focus slide — a big stat, a bold quote, a key number, or
a dramatic visual moment. It re-engages viewers who might be losing interest.

---

## PROMPT TEMPLATE

```
Social media carousel slide {{slide_number}} of {{total_slides}}, highlight/
callout slide, {{canvas_size}}, {{platform}} format. Part of cohesive
{{style_preset}} visual series.

BACKGROUND: {{highlight_bg_treatment}} — this slide's background may be
more visually distinct than content slides, while still using the carousel
palette. Options: inverted colors (dark bg if other slides are light),
full accent color background, or dramatic visual. Specifically: {{bg_choice}}.

LEFT ACCENT BAR: Same as all other slides — thin vertical rectangle,
{{accent_bar_width}}px, full height, left edge, flat {{accent_bar_color}}.
Even if background is inverted, bar remains same color for consistency.

CENTRAL FOCUS ELEMENT: {{highlight_type}} treatment:

  TYPE A — "Big Stat" (number-focused):
  Large flat {{stat_circle_color}} circle or geometric shape, centered,
  approximately 50% canvas width. Interior completely flat open space for
  oversized number/percentage overlay. Below circle: flat narrower open
  strip for stat description. Above circle: flat label strip. No text.

  TYPE B — "Pull Quote" (text-focused):
  Centered flat {{quote_panel_color}} panel, approximately 75% canvas width,
  60% canvas height. Top: flat decorative {{quotemark_color}} large quotation
  mark shape. Interior: multiple flat horizontal text bars of varying widths
  for multi-line quote. Bottom: thin divider line + flat attribution bar.
  No text rendered.

  TYPE C — "Visual Callout" (image-focused):
  Dramatic full-bleed or large centered visual element: {{callout_visual}}.
  {{callout_visual_style}} treatment. Overlay: flat {{overlay_panel_color}}
  semi-transparent lower band with open text zone. Striking, editorial quality.

  TYPE D — "Comparison Split" (contrast):
  Canvas split into two equal halves by thin {{split_line_color}} center line.
  Left half: {{left_bg}} background, flat label zone at top.
  Right half: {{right_bg}} background (contrasting), flat label zone at top.
  Center split: thin divider line or "VS" badge placeholder circle.

BOTTOM BRAND STRIP: Full-width, {{brand_strip_height}}px, flat
{{brand_strip_color}} fill — identical to all other slides.
Logo placeholder left, slide counter circle right. No text.

STYLE: High visual impact, {{mood}} energy, this slide should feel like
a "wow moment" in the sequence, {{contrast_level}} contrast,
no text rendered, no watermark.

CANVAS: {{canvas_size}}
```

---

## WHEN TO USE EACH TYPE

| Situation | Type |
|---|---|
| You have a compelling statistic | Type A — Big Stat |
| You have a powerful client quote or insight | Type B — Pull Quote |
| You want a visual wow moment | Type C — Visual Callout |
| You're comparing two things | Type D — Comparison Split |

---

## SLOT REFERENCE

| Slot | Example Values |
|---|---|
| `{{highlight_bg_treatment}}` | inverted (dark), full accent color, dramatic visual |
| `{{bg_choice}}` | deep navy #1E3A5F, brand accent solid, black #050505 |
| `{{highlight_type}}` | Type A, B, C, or D |
| `{{stat_circle_color}}` | white, accent color, contrasting bright |
| `{{quote_panel_color}}` | white, off-white, very light |
| `{{quotemark_color}}` | accent color, brand primary, gold |
| `{{callout_visual}}` | dramatic product shot, lifestyle scene, abstract |
| `{{callout_visual_style}}` | cinematic, editorial, high contrast |
| `{{overlay_panel_color}}` | dark semi-transparent, brand color 80% opacity |
| `{{left_bg}}` | white, light |
| `{{right_bg}}` | brand primary, dark, accent color |
| `{{split_line_color}}` | white, accent |
| `{{mood}}` | powerful, inspirational, urgent, confident |
| `{{contrast_level}}` | maximum, high, bold |
