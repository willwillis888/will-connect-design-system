Will Connect — Typography
Version 1.0 — April 2026
Reference this file for every font decision.
Do not substitute. Do not default to AI font pairings.
---
FONT STACK
Primary — Open Sauce One
Role: Headlines, display text, brand statements, CTAs
Weights in use: Bold (700) for impact statements / Regular (400) for subheadings
Character: Geometric, modern, slightly rounded. Distinctive without being decorative.
Source: fontsource.org — self-host via @font-face
Google Fonts: NOT available — do not attempt to load from Google Fonts
Secondary — Aileron
Role: Body copy, labels, overlines, supporting text
Weights in use: SemiBold (600) for labels / Light (300) or Regular (400) for body
Character: Clean neutral sans. Legible at small sizes. Pairs without competing.
Source: Direct download — self-host only
Google Fonts: NOT available — do not attempt to load from Google Fonts
Mono — JetBrains Mono
Role: Any numerical display, stats, scores, percentages, data callouts
Weight: Regular (400)
Colour: #C6A96B (Muted Gold) in landing page context
Source: fonts.google.com/specimen/JetBrains+Mono — Google Fonts available
---
TYPE SCALE (landing page)
Element	Font	Size (desktop)	Size (mobile)	Weight	Colour
Display headline	Open Sauce One	64px	36px	700	#190C19
Section heading	Open Sauce One	40px	28px	400	#190C19
Subheading	Open Sauce One	28px	22px	400	#190C19
Body	Aileron	18px	16px	300	#190C19
Supporting body	Aileron	16px	14px	300	#6B4D6B
Overline / label	Aileron	11px	11px	600	#C6A96B
Data / stat display	JetBrains Mono	48px	32px	400	#C6A96B
Caption / footnote	Aileron	12px	12px	300	#6B4D6B
---
OVERLINES AND SECTION LABELS
These appear at the top of each major section. Used sparingly — one per section only.
Font: Aileron SemiBold
Size: 11px
Letter-spacing: 0.12em
Case: ALL CAPS
Colour: #C6A96B (Muted Gold)
Usage: section marker only — not decorative, not repeated
---
LINE HEIGHT AND SPACING
Display headlines: line-height 1.1
Body copy: line-height 1.8 — generous, readable, considered
Labels / overlines: line-height 1.4
Generous vertical space between sections — let ideas breathe
Never compress spacing to fit more content — cut content instead
---
FONT LOADING — CRITICAL
Open Sauce One and Aileron are not on Google Fonts.
Both must be self-hosted.
@font-face implementation:
```css
@font-face {
  font-family: 'Open Sauce One';
  src: url('/fonts/OpenSauceOne-Bold.woff2') format('woff2');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Open Sauce One';
  src: url('/fonts/OpenSauceOne-Regular.woff2') format('woff2');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Aileron';
  src: url('/fonts/Aileron-SemiBold.woff2') format('woff2');
  font-weight: 600;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Aileron';
  src: url('/fonts/Aileron-Light.woff2') format('woff2');
  font-weight: 300;
  font-style: normal;
  font-display: swap;
}
```
Font files live in: /assets/fonts/
---
WHAT NEVER HAPPENS
Cormorant Garamond — AI default, not Will Connect
DM Sans — AI default, not Will Connect
Inter — too generic
Roboto — too generic
Open Sans — too generic
Arial or system fonts — never
Any Google Fonts substitution for Open Sauce One or Aileron
Mixing fonts outside this stack without explicit approval
