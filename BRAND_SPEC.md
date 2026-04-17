# Vibrant Wellness Brand Spec — V2.0

Machine-readable complete brand specification. Source: Brand Book V2.0 (April 2026) + live.standards.site/vibrant-wellness/.

---

## Identity

```
name:           Vibrant Wellness
short_name:     Vibrant
version:        V2.0
date:           April 2026
positioning:    "Vibrant Wellness is the precision lab that enables provider-led personalized medicine."
tagline:        "Clarity for providers. Confidence for patients."
```

---

## Colors

### Core Palette

```
reflex_blue:
  hex:      #0142E2
  rgb:      1, 66, 226
  cmyk:     100 / 71 / 0 / 11
  pantone:  2728 C
  usage:    primary brand color, CTAs, on-color backgrounds
  a11y:     white on reflex_blue = AAA

lab_coat_white:
  hex:      #F3F3F3
  rgb:      243, 243, 243
  cmyk:     0 / 0 / 0 / 5
  pantone:  White C
  usage:    primary background
  a11y:     black on lab_coat_white = AAA

ink_black:
  hex:      #161616
  rgb:      22, 22, 22
  cmyk:     0 / 0 / 0 / 91
  pantone:  Black C
  usage:    primary text, dark backgrounds, logo on light
  note:     NEVER use #000000. Always use #161616.
  a11y:     white on ink_black = accessible

silver_foil:
  hex:      N/A (metallic specialty)
  usage:    premium print only
```

### Zoomer Colors

```
nutrient:
  hex:      #FFD54B
  rgb:      255, 213, 75
  cmyk:     0 / 16 / 71 / 0
  pantone:  122 C
  a11y:     black on nutrient = AAA

gut:
  hex:      #F1B669
  rgb:      241, 182, 105
  cmyk:     0 / 24 / 56 / 5
  pantone:  1355 C
  a11y:     black on gut = AAA

cardio:
  hex:      #FF490D
  rgb:      255, 73, 13
  cmyk:     0 / 71 / 95 / 0
  pantone:  1655 C
  a11y:     black on cardio = AA

cellular:
  hex:      #FF6686
  rgb:      255, 102, 134
  cmyk:     0 / 60 / 47 / 0
  pantone:  1777 C
  a11y:     black on cellular = AAA

hormone:
  hex:      #D7A0EA
  rgb:      215, 160, 234
  cmyk:     8 / 32 / 0 / 8
  pantone:  529 C
  a11y:     black on hormone = AAA

foundation:
  hex:      #BCD0D9
  rgb:      188, 208, 217
  cmyk:     8 / 32 / 0 / 15
  pantone:  5455 C
  a11y:     black on foundation = AAA

immune:
  hex:      #81E4FF
  rgb:      129, 228, 255
  cmyk:     49 / 11 / 0 / 0
  pantone:  Blue 0821 C
  a11y:     black on immune = AAA

neural:
  hex:      #3A85FF
  rgb:      58, 133, 255
  cmyk:     77 / 48 / 0 / 0
  pantone:  2727 C
  a11y:     black on neural = AA

toxin:
  hex:      #67E78D
  rgb:      103, 231, 141
  cmyk:     55 / 0 / 39 / 9
  pantone:  353 C
  a11y:     black on toxin = AAA

food:
  hex:      #00B591
  rgb:      0, 181, 145
  cmyk:     100 / 0 / 20 / 29
  pantone:  3275 C
  a11y:     black on food = AAA
```

---

## Typography

```
primary_typeface:
  name:         ABC Oracle
  foundry:      Dinamo (ABC Dinamo)
  fallback_web: Inter
  fallback_app: Arial
  usage:        headlines, body copy, all long-form text

secondary_typeface:
  name:         GT Pressura Mono
  foundry:      Grilli Type
  fallback_web: Roboto Mono
  fallback_app: Arial (or Courier New for monospaced)
  usage:        small headers, buttons, data labels, UI elements
```

### Type Scale

```
small_header:
  typeface:     GT Pressura Mono
  weight:       Regular
  size:         14pt
  line_height:  100%
  case:         ALL CAPS
  tracking:     wide

headline:
  typeface:     ABC Oracle
  weight:       Medium
  size:         90pt
  line_height:  85%
  case:         Sentence case
  tracking:     approx -40pts (see tracking rules)

body:
  typeface:     ABC Oracle
  weight:       Book
  size:         16-22px (20pt typical)
  line_height:  140%
  case:         Sentence case

button:
  typeface:     GT Pressura Mono
  weight:       Regular
  size:         14pt
  line_height:  100%
  case:         ALL CAPS
```

### Typesetting Rules

```
kerning:            always Optical
tracking_default:   0 (at 12-16pt)
tracking_headline:  -40pts (typical)
tracking_large:     -70pts (at 150pt)
word_spacing:       do not adjust defaults
column_length:      50-75 characters per line (~11 words)
justification:      always left-aligned
centered_allowed:   short expressive headlines only
hyphenation:        avoid; permitted judiciously
leading_headline:   85%
leading_body:       140%
```

---

## Logo

```
components:
  - primary_logo     (brandmark + wordmark combined)
  - brandmark        (icon only)
  - wordmark         (text only, "VIBRANT" all-caps)

approved_colors:
  - ink_black (#161616) on light backgrounds
  - white on dark/colored backgrounds
  - NEVER in any other color

clearspace_primary:   50px all sides
clearspace_brandmark: height of capital T in wordmark
clearspace_wordmark:  width of brandmark at 50px

minimum_digital:      100px wide
minimum_print:        1 inch wide

cobranding_separator: 1.5pt solid vertical stroke
cobranding_spacing:   2x brandmark width
```

---

## Zoomer System

```
total_zoomers: 10

tiers:
  critical (The Drivers):
    - CardioZoomer (#FF490D)
    - NeuralZoomer (#3A85FF)
  functional (The Levers):
    - GutZoomer (#F1B669)
    - HormoneZoomer (#D7A0EA)
    - CellularZoomer (#FF6686)
    - ImmuneZoomer (#81E4FF)
  environmental (The Controllables):
    - ToxinZoomer (#67E78D)
    - FoodZoomer (#00B591)
    - NutrientZoomer (#FFD54B)
  foundational (The Guide):
    - FoundationZoomer (#BCD0D9)

naming_format:  [System]Zoomer (camelCase, one word)
```

---

## Layout

```
margin_formula:     shortest_side * 4% to 9%
margin_portrait:    6%
margin_landscape_s: 9%
margin_landscape_l: 5%

grid:               4-5 vertical columns
alignment:          left (primary), centered (short headlines only)
photography:        dominant, can be full-bleed

iconography_grid:   5x5
icon_style:         simplified, slightly abstract
icon_edges:         mix of rounded and square; lines end straight; start from one central dot
```

---

## Photography Categories

```
artful_scientific:
  treatment:    black and white only
  background:   black
  humans:       none
  mood:         contemplative, artful

micro_scientific:
  treatment:    selective color
  background:   light/white
  humans:       gloved hands only
  mood:         clean, ordered

precision_lab:
  treatment:    cool tones, both light and dark
  background:   both
  humans:       minimal
  mood:         futuristic, systematic

clinician_patient:
  treatment:    warm natural color
  background:   natural environments
  humans:       central
  mood:         human, trusting
```

---

## Brand Voice

```
positioning:  "Vibrant Wellness is the precision lab that enables provider-led personalized medicine."
tagline:      "Clarity for providers. Confidence for patients."

voice_attributes:
  - Direct about complex science
  - Clear without oversimplifying
  - Confident without hype
  - No corporate cushioning
  - No jargon walls

primary_audience:   providers
secondary_audience: patients (always accessed through provider relationship)
```
