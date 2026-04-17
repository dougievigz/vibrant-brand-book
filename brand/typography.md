# Typography

## Primary Typeface: ABC Oracle

Clean, modern, and uncomplicated. Aligns with the wordmark and brand ethos. Used for headlines and body copy.

**Foundry:** Dinamo (ABC Dinamo)
**Fallback (Google Fonts):** Inter
**Fallback (other programs):** Arial

### Available Weights (Trial fonts in `/assets/fonts/`)
| Weight | Style | File |
|---|---|---|
| Thin | Regular | ABCOracle-Thin-Trial.otf |
| Thin | Italic | ABCOracle-ThinItalic-Trial.otf |
| Light | Regular | ABCOracle-Light-Trial.otf |
| Light | Italic | ABCOracle-LightItalic-Trial.otf |
| Book | Regular | ABCOracle-Book-Trial.otf |
| Book | Italic | ABCOracle-BookItalic-Trial.otf |
| Regular | Regular | ABCOracle-Regular-Trial.otf |
| Regular | Italic | ABCOracle-RegularItalic-Trial.otf |
| Medium | Regular | ABCOracle-Medium-Trial.otf |
| Medium | Italic | ABCOracle-MediumItalic-Trial.otf |
| Bold | Regular | ABCOracle-Bold-Trial.otf |
| Bold | Italic | ABCOracle-BoldItalic-Trial.otf |
| Heavy | Regular | ABCOracle-Heavy-Trial.otf |
| Heavy | Italic | ABCOracle-HeavyItalic-Trial.otf |
| Black | Regular | ABCOracle-Black-Trial.otf |
| Black | Italic | ABCOracle-BlackItalic-Trial.otf |
| Ultra | Regular | ABCOracle-Ultra-Trial.otf |
| Ultra | Italic | ABCOracle-UltraItalic-Trial.otf |

---

## Secondary Typeface: GT Pressura Mono

Modern with slightly rounded edges. Monospaced. Complements ABC Oracle. Used for small headers, buttons, data labels, and UI elements.

**Foundry:** Grilli Type
**Fallback (Google Fonts):** Roboto Mono
**Fallback (other programs):** Arial (monospaced context: Courier New acceptable)

### Available Weights (Trial fonts in `/assets/fonts/`)
| Weight | Style | File |
|---|---|---|
| Light | Regular | GT-Pressura-Mono-Light-Trial.otf |
| Light | Italic | GT-Pressura-Mono-Light-Italic-Trial.otf |
| Text | Regular | GT-Pressura-Mono-Text-Trial.otf |
| Text | Italic | GT-Pressura-Mono-Text-Italic-Trial.otf |
| Regular | Regular | GT-Pressura-Mono-Regular-Trial.otf |
| Regular | Italic | GT-Pressura-Mono-Regular-Italic-Trial.otf |
| Medium | Regular | GT-Pressura-Mono-Medium-Trial.otf |
| Medium | Italic | GT-Pressura-Mono-Medium-Italic-Trial.otf |
| Bold | Regular | GT-Pressura-Mono-Bold-Trial.otf |
| Bold | Italic | GT-Pressura-Mono-Bold-Italic-Trial.otf |
| Black | Regular | GT-Pressura-Mono-Black-Trial.otf |
| Black | Italic | GT-Pressura-Mono-Black-Italic-Trial.otf |

---

## Fallback Fonts (in `/assets/fonts/`)
| Font | Purpose |
|---|---|
| Inter-VariableFont.ttf | ABC Oracle fallback (Google Fonts programs) |
| Arial.ttf | ABC Oracle fallback (standard programs) |
| Arial-Bold.ttf | ABC Oracle Bold fallback |

---

## Typesetting Hierarchy

### Small Header
- **Typeface:** GT Pressura Mono
- **Weight:** Regular
- **Size:** 14pt
- **Line height:** 100%
- **Case:** ALL CAPS
- **Letter spacing:** Wide (tracked out)

### Headline
- **Typeface:** ABC Oracle
- **Weight:** Medium
- **Size:** 90pt
- **Line height:** 85%
- **Case:** Sentence case
- **Tracking:** Approximately -40pts at this scale (see tracking rules below)

### Body
- **Typeface:** ABC Oracle
- **Weight:** Book
- **Size:** 16-22px (20pt typical)
- **Line height:** 140%
- **Case:** Sentence case

### Button
- **Typeface:** GT Pressura Mono
- **Weight:** Regular
- **Size:** 14pt
- **Line height:** 100%
- **Case:** ALL CAPS

---

## Typesetting Rules

### Kerning
- Always set to **Optical**
- Large headlines may require manual kerning refinement

### Tracking
- Default: **0** (optimal at 12-16pt)
- As type gets larger, reduce tracking
- Typical headline adjustment: **-40pts**
- At 150pt: **-70pts**
- Rule: The bigger the point size, the more tightening needed

### Word Spacing
- Do NOT adjust the default word spacing settings

### Leading (Line Height)
- General rule: Leading > Word spacing > Tracking (visually)
- Headlines: **85%**
- Body: **140%**
- Smaller type needs more leading. Larger type needs less.

### Column Length
- **50-75 characters per line** (approximately 11 words in English)
- Justification: **Always left-aligned** (centered only for short expressive headlines)
- Hyphenation: Avoid. Judiciously permitted if omitting creates odd rags.
- Rag: Discrete tracking adjustments and occasional forced returns permitted to keep text neat

### Usage Summary
- **ABC Oracle** = headlines, body copy, all long-form text
- **GT Pressura Mono** = small headers, buttons, data labels, UI elements, category tags
