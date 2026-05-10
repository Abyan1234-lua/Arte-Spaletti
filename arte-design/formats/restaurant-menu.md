# FORMAT: Restaurant Menu / Food Menu Board

Use this template for: restaurant menus, café menu boards, food stall menus,  
catering menus, digital menu displays, printed food menus, bar menus.

---

## PROMPT TEMPLATE



```
Professional restaurant menu design, {{aspect_ratio}}, {{menu_format}} layout.

BACKGROUND: {{background_style}} — {{bg_description}}.
Color: {{bg_color_primary}} dominant. Texture: {{bg_texture}} subtle surface
texture (linen, paper grain, wood grain, marble, concrete). Overall mood:
{{mood}} and inviting.

HEADER ZONE: Top {{header_height}}% of canvas — {{header_color}} band or
textured area. Clean space for restaurant name/logo. Decorative
{{header_decoration}} element (thin rule lines, botanical illustration, simple
icon) in {{decoration_color}}, minimal and elegant. May include generated
title/logo placeholder but must remain clean and replaceable.

FOOD HERO IMAGE: {{food_position}} — {{food_description}} photographed from
{{camera_angle}}, {{food_styling}} food styling, {{food_lighting}} lighting,
occupying {{food_size}}% of canvas. Photorealistic, appetizing, high-quality
food photography aesthetic.

MENU CATEGORY ZONES: {{category_count}} rectangular sections arranged in
{{category_layout}}, each with:
  - Thin {{category_divider}} decorative top border/separator
  - {{category_header_color}} header area for category title
  - {{item_count}} rows using alternating {{item_row_color_a}} and
    {{item_row_color_b}} strips for menu item layout
  - May include generated category names and menu items, but must remain
    clean and easy to edit

PRICE COLUMN: Right-aligned structured column within each menu item row,
{{price_col_width}}% of row width, subtle {{price_separator}} line separating
name from price. Prices may be generated but must remain editable.

FOOTER ZONE: Bottom {{footer_height}}% — {{footer_color}} band, space for
contact info, address, social handles, website. Thin decorative
{{footer_line}} rule line at top edge. Text may be generated but must remain
replaceable.

ACCENT ELEMENTS: Small {{accent_style}} decorative illustrations
(herbs, leaves, cutlery, simple food icons) placed at {{accent_placement}},
{{accent_color}} color, low opacity, non-distracting.

LOGO AREA: Header zone or corner — may include a simple placeholder mark or
clean space, intended for replacement with real restaurant logo.

QR CODE AREA (optional): Small square zone for digital menu or ordering —
generate as visual placeholder only.

TEXT HANDLING: If no text is provided, generate realistic menu content
(category names, dish names, short descriptions, prices) appropriate to
{{cuisine_style}}. All text must be readable and easily replaceable.

COLOR PALETTE: {{primary_color}}, {{secondary_color}}, {{accent_color}}.

STYLE: {{cuisine_style}} restaurant aesthetic, {{print_quality}} quality,
elegant food design, inviting warmth, {{era_style}} visual style,
balanced composition, editable-friendly structure, no watermark.

ASPECT RATIO: {{aspect_ratio}}
```

---

## SLOT REFERENCE


| Slot                        | Example Values                                                 |
| --------------------------- | -------------------------------------------------------------- |
| `{{aspect_ratio}}`          | A4 portrait, A3 landscape, 1:1, 4:5                            |
| `{{menu_format}}`           | single-page, two-column, trifold-style                         |
| `{{background_style}}`      | warm cream, dark wood, marble white                            |
| `{{bg_description}}`        | aged cream paper texture, dark walnut wood surface             |
| `{{bg_color_primary}}`      | cream #FDF8F0, charcoal #1C1C1C, white #FFFFFF                 |
| `{{bg_texture}}`            | linen, aged paper, fine grain, marble                          |
| `{{mood}}`                  | rustic warm, elegant dark, fresh bright, artisanal             |
| `{{header_height}}`         | 15, 20                                                         |
| `{{header_color}}`          | warm brown #4A2C1A, black #000000, deep green #1B4332          |
| `{{header_decoration}}`     | botanical leaf border, thin double rule lines, wheat motif     |
| `{{decoration_color}}`      | gold #C9A84C, cream, muted terracotta                          |
| `{{food_position}}`         | top-right, center-top, full-width bleed top                    |
| `{{food_description}}`      | signature pasta dish with herbs, artisan coffee with latte art |
| `{{camera_angle}}`          | overhead flat lay, 45-degree angle, eye-level close-up         |
| `{{food_styling}}`          | rustic editorial, clean minimal, abundant generous             |
| `{{food_lighting}}`         | warm natural window light, moody dark studio, bright airy      |
| `{{food_size}}`             | 30, 40, 50                                                     |
| `{{category_count}}`        | 3, 4, 5                                                        |
| `{{category_layout}}`       | 2-column grid, single column, 3-column                         |
| `{{category_divider}}`      | gold rule, leaf motif, simple line                             |
| `{{category_header_color}}` | warm brown, forest green, black                                |
| `{{item_count}}`            | 4, 5, 6                                                        |
| `{{item_row_color_a}}`      | transparent, very light cream                                  |
| `{{item_row_color_b}}`      | slightly off-white, very subtle warm tint                      |
| `{{price_col_width}}`       | 15, 20                                                         |
| `{{price_separator}}`       | dotted line, dashed, solid thin                                |
| `{{footer_height}}`         | 10, 12                                                         |
| `{{footer_color}}`          | matches header color, dark band                                |
| `{{footer_line}}`           | gold, white, accent color                                      |
| `{{accent_style}}`          | botanical, culinary, minimal icon                              |
| `{{accent_placement}}`      | section corners, between categories                            |
| `{{accent_color}}`          | gold, muted terracotta, sage green                             |
| `{{cuisine_style}}`         | Italian trattoria, modern café, fine dining, street food       |
| `{{print_quality}}`         | print-ready 300dpi, digital display                            |
| `{{era_style}}`             | modern minimal, vintage bistro, contemporary                   |


---

## CANVA EDITING ZONES (UPDATED FOR MAGIC LAYERS)


| Zone               | Location         | What to do in Canva                     |
| ------------------ | ---------------- | --------------------------------------- |
| Restaurant name    | Header zone      | Replace/refine title                    |
| Logo               | Header corner    | Replace placeholder with real logo      |
| Category titles    | Category headers | Adjust naming                           |
| Menu items         | Item rows        | Edit dishes + descriptions              |
| Prices             | Price column     | Update pricing                          |
| Footer info        | Footer band      | Replace contact details                 |
| Special badge      | Near hero image  | Add/remove promos like “Chef’s Special” |
| QR code (optional) | Corner area      | Replace with real QR                    |
| Cleanup            | Entire layout    | Fix spacing, alignment, artifacts       |


