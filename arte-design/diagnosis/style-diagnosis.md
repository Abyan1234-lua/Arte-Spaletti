# Style Diagnosis Engine

When the user provides no brand assets, this file guides ARTE-DESIGN to
auto-assign all visual variables based on business type, format, and intent.

---

## DIAGNOSIS MATRIX

### Step 1 — Identify Business Category

| Business Type | Keywords | Assigned Style Preset |
|---|---|---|
| Tech / SaaS / AI | software, app, platform, digital, AI, startup | `tech-modern` |
| Food & Beverage | restaurant, café, food, drink, menu, kuliner | `warm-organic` |
| Health & Wellness | gym, fitness, health, skincare, beauty, spa | `clean-energy` |
| Corporate / Finance | consulting, finance, law, insurance, bank | `corporate-clean` |
| Fashion / Luxury | fashion, boutique, jewelry, luxury, premium | `luxury-minimal` |
| Youth / Lifestyle | music, event, party, festival, streetwear | `bold-playful` |
| Education / Course | course, class, webinar, seminar, training | `academic-trust` |
| Product / FMCG | consumer product, beverage, energy, snack | `cinematic-dark` or `clean-bright` |
| Real Estate | property, apartment, villa, housing | `luxury-minimal` |
| NGO / Social | community, nonprofit, awareness, campaign | `warm-organic` |

---

### Step 2 — Map Style Preset to Visual Variables

#### `tech-modern`
- Background: Deep navy or matte black, subtle grid or circuit texture
- Palette: #0A0F2C (base), #00C2FF (accent), #FFFFFF (text)
- Typography mood: Sharp, geometric, condensed sans-serif
- Lighting: Cool blue rim light, soft glow
- Atmosphere: Futuristic, minimal, precise

#### `warm-organic`
- Background: Warm cream, linen texture, or soft bokeh kitchen/nature scene
- Palette: #3B2F2F (base), #E8A87C (accent), #F5EFE6 (highlight)
- Typography mood: Rounded sans-serif or soft serif
- Lighting: Warm golden hour, diffused natural light
- Atmosphere: Cozy, inviting, artisanal

#### `clean-energy`
- Background: White or very light grey, minimal texture
- Palette: #FFFFFF (base), #00B894 (accent), #2D3436 (text)
- Typography mood: Modern sans-serif, airy spacing
- Lighting: Bright studio, soft shadow
- Atmosphere: Fresh, vibrant, healthy

#### `corporate-clean`
- Background: White or light grey, subtle geometric shapes
- Palette: #1A2B5F (base), #2563EB (accent), #FFFFFF (text)
- Typography mood: Professional serif or strong sans-serif
- Lighting: Neutral even studio
- Atmosphere: Trustworthy, structured, authoritative

#### `luxury-minimal`
- Background: Deep charcoal, matte black, or soft champagne
- Palette: #1C1C1C (base), #C9A84C (gold accent), #F5F0EB (text)
- Typography mood: Thin serif, elegant tracking
- Lighting: Directional side light, deep shadows
- Atmosphere: Exclusive, quiet luxury, timeless

#### `bold-playful`
- Background: Vivid gradient or high-contrast solid color
- Palette: #FF3CAC (base), #FBFF12 (accent), #2B2D42 (contrast)
- Typography mood: Bold display, expressive, oversized
- Lighting: Vibrant, flat, or pop-art inspired
- Atmosphere: Energetic, youthful, loud

#### `academic-trust`
- Background: Clean white or soft blue-grey
- Palette: #1E3A5F (base), #3B82F6 (accent), #FFFFFF (text)
- Typography mood: Clean sans-serif, structured hierarchy
- Lighting: Neutral, even, professional
- Atmosphere: Credible, approachable, educational

#### `cinematic-dark`
- Background: Near-black with dynamic particle/smoke/water effects
- Palette: #050505 (base), brand color as neon accent, #FFFFFF (text)
- Typography mood: Heavy condensed sans-serif
- Lighting: High-contrast dramatic rim/spot light
- Atmosphere: Intense, premium, powerful

#### `clean-bright`
- Background: Pure white or pastel, very clean
- Palette: White base + product's own dominant color
- Typography mood: Friendly rounded sans-serif
- Lighting: Bright even studio
- Atmosphere: Fresh, accessible, commercial

---

### Step 3 — Assign Canvas Size by Platform

| Platform | Dimensions | Orientation |
|---|---|---|
| Instagram Post | 1080 x 1080px | Square |
| Instagram Story / Reel | 1080 x 1920px | Portrait |
| Instagram Carousel | 1080 x 1080px per slide | Square |
| Facebook Post | 1200 x 630px | Landscape |
| LinkedIn Post | 1200 x 627px | Landscape |
| LinkedIn Carousel | 1080 x 1080px per slide | Square |
| Print Poster (A3) | 2480 x 3508px | Portrait |
| Web Banner | 1920 x 600px | Landscape |
| YouTube Thumbnail | 1280 x 720px | Landscape |

If user does not specify platform, default to **1080 x 1080px** for social,
**800 x 1200px** for print/poster formats.

---

### Step 4 — Output Diagnosis Summary

Before generating the prompt, briefly state the diagnosis to the user:

```
🎨 ARTE-DESIGN DIAGNOSIS
Business type: [detected type]
Style preset: [assigned preset]
Palette: [primary] / [accent] / [text]
Canvas: [dimensions]
Atmosphere: [1-line description]

Generating your prompt now...
```
