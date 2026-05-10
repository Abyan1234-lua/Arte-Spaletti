# FORMAT: Social Ad (Instagram / Facebook / LinkedIn)

Use this template for: paid social ads, organic social posts, Instagram feed ads,  
Facebook sponsored posts, LinkedIn sponsored content, brand awareness posts.

---

## PROMPT TEMPLATE

```
Professional social media advertisement, {{aspect_ratio}}, optimized for
{{platform}} feed, scroll-stopping visual design.

BACKGROUND: {{background_style}} — {{bg_description}}.
Color: {{bg_color_primary}} with {{bg_color_secondary}} secondary element.
Mood: {{mood}}. The background must be visually striking enough to stop a
social media scroll.

VISUAL HERO: {{hero_description}} as the focal point, positioned
{{hero_position}}, {{hero_style}} rendering, occupying {{hero_size}}% of frame.
{{hero_treatment}} for premium feel.

UPPER TEXT ZONE: Top {{upper_zone_height}}% of canvas — {{upper_zone_color}}
band or seamlessly blended overlay, clean readable area for hook headline.
May include generated headline text but must remain bold, clear, and easy to refine.

LOWER CONTENT ZONE: Bottom {{lower_zone_height}}% of canvas — {{lower_zone_color}}
panel, clean, divided into:
  - Left: space for body copy (2–3 lines, may be generated but editable)
  - Right: {{cta_bg_color}} pill or button shape for CTA, may include generated text

BRAND ANCHOR: {{brand_anchor_position}} — small {{logo_zone_color}} rectangle
or circle, clean space or simple placeholder mark for logo replacement.
Approximately 8% of canvas width.

QR CODE AREA (optional): Small square zone if needed — generate as visual
placeholder only.

TEXT HANDLING: If no text is provided, generate realistic marketing copy
(headline, value proposition, CTA) suitable for {{platform}}. All text must
be readable and easily replaceable.

COLOR PALETTE: {{primary_color}}, {{accent_color}}, {{neutral_color}}.

STYLE: {{style_directive}}, platform-native aesthetic for {{platform}},
high-quality commercial production, {{lighting_style}}, thumb-stopping
composition, balanced layout, editable-friendly structure, no watermark.

ASPECT RATIO: {{aspect_ratio}}
```

---

## SLOT REFERENCE


| Slot                        | Platform          | Example Values                                           |
| --------------------------- | ----------------- | -------------------------------------------------------- |
| `{{aspect_ratio}}`          | Instagram feed    | 1:1, 4:5                                                 |
| `{{aspect_ratio}}`          | Instagram Story   | 9:16                                                     |
| `{{aspect_ratio}}`          | Facebook/LinkedIn | 1.91:1                                                   |
| `{{platform}}`              | —                 | Instagram, Facebook, LinkedIn, TikTok                    |
| `{{background_style}}`      | —                 | lifestyle scene, studio, abstract gradient, flat color   |
| `{{bg_description}}`        | —                 | soft gradient blend, blurred environment, clean backdrop |
| `{{bg_color_primary}}`      | —                 | brand main color, dark neutral, white                    |
| `{{bg_color_secondary}}`    | —                 | accent highlight, gradient tone                          |
| `{{mood}}`                  | —                 | aspirational, urgent, warm, professional, playful        |
| `{{hero_description}}`      | —                 | person using product, product flat lay, lifestyle moment |
| `{{hero_position}}`         | —                 | center, right-biased, full bleed                         |
| `{{hero_style}}`            | —                 | lifestyle photography, clean studio, documentary         |
| `{{hero_size}}`             | —                 | 60, 70, 80                                               |
| `{{hero_treatment}}`        | —                 | color graded, high contrast, soft blur background        |
| `{{upper_zone_height}}`     | —                 | 20, 25, 30                                               |
| `{{upper_zone_color}}`      | —                 | transparent fade, flat dark overlay, white band          |
| `{{lower_zone_height}}`     | —                 | 25, 30                                                   |
| `{{lower_zone_color}}`      | —                 | white, brand primary, dark                               |
| `{{cta_bg_color}}`          | —                 | brand accent, black, white                               |
| `{{brand_anchor_position}}` | —                 | top-left, top-right, bottom-left                         |
| `{{logo_zone_color}}`       | —                 | white, transparent, brand color                          |
| `{{primary_color}}`         | —                 | brand main color                                         |
| `{{accent_color}}`          | —                 | highlight color                                          |
| `{{neutral_color}}`         | —                 | white, grey, black                                       |
| `{{style_directive}}`       | —                 | modern lifestyle photography, bold graphic design        |
| `{{lighting_style}}`        | —                 | golden hour, studio even light, dramatic side light      |


---

## PLATFORM-SPECIFIC NOTES (UPDATED)

### Instagram Feed (1:1 or 4:5)

-   
Keep key elements within center 80% (safe crop)  

-   
Strong single focal point  

-   
Avoid clutter — prioritize clarity  


### Instagram Story / Reel Cover (9:16)

-   
Top 15% and bottom 20% = UI-safe zones  

-   
Use large, bold readable text  

-   
Full-bleed visuals work best  


### Facebook / LinkedIn (1.91:1)

-   
Use left-right composition balance  

-   
More conservative, professional tone for LinkedIn  

-   
Avoid overly dense layouts  


---

## CANVA EDITING ZONES (UPDATED FOR MAGIC LAYERS)


| Zone               | Location       | What to do in Canva                |
| ------------------ | -------------- | ---------------------------------- |
| Logo               | Brand anchor   | Replace placeholder with real logo |
| Hook headline      | Upper zone     | Refine headline                    |
| Body copy          | Lower left     | Adjust messaging                   |
| CTA                | Lower right    | Replace CTA text + add link        |
| Hashtags           | Bottom (Story) | Add or refine                      |
| QR code (optional) | Small corner   | Replace with real QR               |
| Cleanup            | Entire layout  | Fix alignment, spacing, artifacts  |


