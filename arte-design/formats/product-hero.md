# FORMAT: Product Hero Poster

Use this template for: product advertisements, FMCG hero shots, beverage ads,  
skincare/beauty ads, food product posters, consumer goods campaigns.

Reference style: Volt Energy drink — dramatic product centerpiece with cinematic  
lighting, benefit callouts, and specs at bottom.

---

## PROMPT TEMPLATE



```
Commercial product advertisement poster, {{aspect_ratio}}, print-ready quality.

BACKGROUND: {{background_scene}} — {{mood}} atmosphere, {{lighting_style}} lighting,
{{texture_detail}} subtle texture. Background color palette: {{bg_color_primary}}
transitioning to {{bg_color_secondary}}.

HERO PRODUCT: {{product_description}} positioned {{product_position}} of frame,
{{product_style}} rendering, {{product_detail}} visible on packaging.
{{product_effect}} effect surrounding the product (e.g., water splash, smoke,
particles, glow). Product occupies approximately 55% of frame height.

HEADLINE ZONE: Top-{{headline_side}} quadrant — flat {{headline_bg_color}} area
with minimal texture, clean open space approximately 40% of canvas width,
designed for bold headline text. May include generated text but must remain
clear and easy to refine.

SUBHEADLINE AREA: Directly below headline zone — smaller flat area for
tagline or product promise. Text may be generated but must remain clean and
replaceable.

BENEFIT LIST ZONE: Left-center vertical strip — structured panel with
{{benefit_panel_color}} backing, three icon elements stacked vertically with
{{icon_color}} styling, each followed by short text or placeholder bars
representing product benefits.

BOTTOM INFO STRIP: Full-width bottom band, {{bottom_strip_color}} solid fill,
divided into two sections — left and right — for product details such as
variant, specs, or key stats. Text may be generated but must remain editable.

LOGO AREA: Top corner or center-top — may include a simple logo-like placeholder
or clean space, intended for replacement with real brand logo.

QR CODE AREA (optional): Small square zone if needed — generate as visual
placeholder only.

TEXT HANDLING: If no text is provided, generate realistic product marketing text
(headline, tagline, benefits, specs) appropriate to the product. All text must
be clean, readable, and easily replaceable.

COLOR PALETTE: Primary {{primary_color}}, accent {{accent_color}},
highlight {{highlight_color}}, text areas in flat {{text_zone_color}}.

STYLE: Ultra-realistic commercial photography, CGI-quality product rendering,
{{atmosphere}} mood, dramatic {{lighting_direction}} lighting with {{light_color}}
rim light, high contrast, deep shadows, photorealistic reflections on surface
beneath product, professional advertising photography, balanced composition,
editable-friendly structure, no watermark.

ASPECT RATIO: {{aspect_ratio}}
```

---

## SLOT REFERENCE


| Slot                      | Example Values                                               |
| ------------------------- | ------------------------------------------------------------ |
| `{{aspect_ratio}}`        | 3:4 portrait, 1:1 square, 4:5 portrait                       |
| `{{background_scene}}`    | dark wet surface, misty black void, concrete floor           |
| `{{mood}}`                | dramatic, intense, premium, energetic                        |
| `{{lighting_style}}`      | rim lighting, spotlight, studio dramatic                     |
| `{{texture_detail}}`      | water droplets, particle dust, smoke wisps                   |
| `{{bg_color_primary}}`    | deep black #050505, navy #0A1628                             |
| `{{bg_color_secondary}}`  | dark blue #0D2137, charcoal #1A1A2E                          |
| `{{product_description}}` | tall blue aluminum energy drink can with lightning bolt logo |
| `{{product_position}}`    | center-right, dead center, right-of-center                   |
| `{{product_style}}`       | photorealistic, glossy, matte, wet condensation              |
| `{{product_detail}}`      | label graphics, metallic finish, condensation droplets       |
| `{{product_effect}}`      | water splash explosion, neon glow halo, smoke ring           |
| `{{headline_side}}`       | left, right                                                  |
| `{{headline_bg_color}}`   | transparent-to-black gradient, flat dark area                |
| `{{benefit_panel_color}}` | semi-transparent dark, flat charcoal                         |
| `{{icon_color}}`          | electric blue, white, gold                                   |
| `{{bottom_strip_color}}`  | electric blue #0066FF, deep navy, brand accent               |
| `{{primary_color}}`       | deep black, dark navy                                        |
| `{{accent_color}}`        | electric blue #00AAFF, neon green #00FF88                    |
| `{{highlight_color}}`     | white #FFFFFF, silver #C0C0C0                                |
| `{{text_zone_color}}`     | flat dark panel, white flat area                             |
| `{{atmosphere}}`          | intense, premium, high-energy, bold                          |
| `{{lighting_direction}}`  | back-rim, top-down, side                                     |
| `{{light_color}}`         | cold blue, warm gold, white                                  |


---

## CANVA EDITING ZONES (UPDATED FOR MAGIC LAYERS)

After generating the image in GPT Image, edit in Canva:


| Zone               | Location                 | What to do in Canva                |
| ------------------ | ------------------------ | ---------------------------------- |
| Headline           | Top-left or top-right    | Replace/refine main headline       |
| Subheadline        | Below headline           | Adjust tagline                     |
| Benefit 1–3        | Left-center strip        | Edit feature points                |
| Bottom Left        | Bottom band left         | Update variant / flavor            |
| Bottom Right       | Bottom band right        | Update specs / stats               |
| Logo               | Top corner or center-top | Replace placeholder with real logo |
| QR code (optional) | Anywhere small           | Replace with real QR               |
| Cleanup            | Entire layout            | Remove artifacts, fix alignment    |


