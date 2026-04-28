Will Connect — Design System Skill
Read this file completely before generating anything.
Every design decision must trace back to this document.
Do not invent, assume, or default to generic patterns.
---
SECTION 1 — WHAT WILL CONNECT IS
Will Connect is a learning systems business.
It makes applied reasoning visible inside online education.
It is a system — not a platform, not a SaaS tool.
Positioning (use verbatim when required):
"Not a dashboard. A system that converts learning behaviour → actionable decisions."
The business answers three questions in everything it produces:
How well are members executing?
Where are they struggling?
What should the creator do about it?
If an output does not serve at least one of these — rewrite it.
---
SECTION 2 — ROUTING
Before building anything, check these files first.
Do not guess. Do not default. Read the file.
Colours and usage rules  → /_brand/palette.md
Typography rules          → /_brand/typography.md
Voice and tone            → /_brand/voice.md
Copy rules                → /_brand/copy-rules.md
Logo SVG file             → /_brand/logo-mark.svg
Reusable components       → /components/
If a file does not exist for a decision you need to make — flag it.
Do not fill the gap with a generic default.
---
SECTION 3 — DESIGN NON-NEGOTIABLES
Colour logic — two contexts
The brand has a core palette and a landing page palette.
Use the correct set for the correct context.
LANDING PAGE (default context for web outputs):
Background primary:  #F8F6F7  (warm white) — default page background
Background surface:  #EDE6ED  (plum tint) — cards, section alternates
Text primary:        #190C19  (deep plum) — all headlines and body
Text secondary:      #6B4D6B  (plum mid) — supporting copy, labels
Accent:              #C6A96B  (muted gold) — CTA, highlights, borders — use sparingly
Dividers:            #E2CFA0  (gold mid) — horizontal rules between sections
BRAND / DARK MODE (slides, dark backgrounds, dark contexts):
Background:  #190C19  (deep plum)
Text:        #F8F6F7  (warm white)
Accent:      #C6A96B  (muted gold)
Hard rules (apply to both contexts):
Never use gold (#C6A96B) as a background colour
Logo always rendered as SVG ellipses — never text only
No generic SaaS visual patterns
No gradients
No rounded corners beyond 2px on structural elements
(exception: animation panels — see Section 5)
No startup hype language in any copy — ever
---
SECTION 4 — TYPOGRAPHY
Primary — Open Sauce One
Use for: headlines, display text, brand statements, CTAs
Weight: Bold for impact statements / Regular for subheadings
Never substitute with: Cormorant Garamond, DM Sans, Inter, Roboto,
or any AI-default font pairing
Secondary — Aileron
Use for: body copy, labels, overlines, supporting text
Weight: SemiBold for labels / Light or Regular for body
Never substitute with: Open Sans, Inter, Roboto, or system fonts
Overlines and section labels
Font: Aileron
Size: 11px
Letter-spacing: 0.12em
Colour: #C6A96B (muted gold)
Case: ALL CAPS
Usage: sparingly — one per section maximum, as a section marker only
Data and numerical displays
Font: JetBrains Mono
Use for: any stat, score, percentage, or numerical callout
Colour: #C6A96B (gold) in landing page context
Font loading note
Open Sauce One is not available on Google Fonts.
Source from fontsource.org or self-host via @font-face.
Aileron is available via direct download — self-host only.
Do not substitute these fonts because they are unavailable in a tool.
Flag the issue and resolve it correctly.
---
SECTION 5 — ANIMATION AND MOTION SYSTEM
Core storytelling mechanic
The page uses rounded rectangle panels as the primary visual unit.
This references instructional design and learning system architecture —
the shapes learning is visualised in.
Panels connect together as the user scrolls, building a narrative sequence.
Not isolated sections. A story assembling in real time.
Each panel reveals, then a connecting element links it to the next —
a thin gold line drawing between them, or a soft fade-through overlap.
The page demonstrates the product thinking through its own design.
Panel specification
Shape:   rounded rectangles, border-radius 12–16px
Surface (light context):  #EDE6ED at 60% opacity — frosted, warm
Surface (dark context):   #190C19 at 50% opacity — frosted, deep
Effect:  backdrop-filter blur — 8–12px — frosted glass quality
Entry:   fade up + slight scale 0.96→1 on scroll entry
Duration: 0.6s ease-out
Connected panels stagger: 0.15s between each
Connecting elements between panels
Thin gold line (#C6A96B) draws between panels as scroll progresses
Or: soft fade overlap — next panel begins appearing as previous completes
Creates the feeling of a system assembling — not a page loading
Never a hard cut between sections — always a connecting moment
Additional motion rules
Numbers and stats: count up from 0 on viewport entry
Section headings: 0.8s fade — slightly slower, feels considered
Dashboard panels: each bar or component reveals independently, 0.15s stagger
All scroll triggers via Intersection Observer API — no scroll libraries
Never use
Bounce or spring animations
Parallax scrolling
Auto-playing video
Snap scrolling or scroll-jacking
Hard cuts between sections
---
SECTION 6 — COPY RULES
These are absolute. No exceptions.
No em dashes — use a comma, full stop, or restructure the sentence
No exclamation marks anywhere on the page
No "platform" — always "system"
No "AI-powered" or any AI framing
No "revolutionary", "game-changing", "next-level"
No "Execution Gap Intelligence" in public-facing copy — internal use only
No "I help" framing in any content
No bullet points with icons in narrative sections
No passive construction where active works
No three consecutive sentences starting with "I"
No scene-setting before making a point — first sentence does the work
Specific beats vague at all times: "6 weeks, one module" not "a short engagement"
Precise language over broad claims — always
Also never use these words
intersection, leverage (as a verb), synergy, unlock, journey,
transformative, game-changer, seamlessly, holistic, robust,
deep dive, cutting-edge, innovative, passionate about
---
SECTION 7 — VOICE
Core identity
Write like a founder who has thought more clearly about this problem
than anyone else in the market.
Not a startup trying to impress. Not performing expertise.
Grounded, present, genuinely in service of the reader.
Human before professional.
The writing sounds like a real person who knows their craft.
The seven principles behind the voice
Learner-first, ego-last
The reader's reality comes before credentials.
Put their problem before the product. Always.
Three-part clarity
Where they are winning, where they are stuck, what they do next.
Always that progression. Never skip to the solution.
Vulnerability plus intention equals authority
Human and grounded at the same time.
Nothing to prove and everything to offer.
This is what opens people up.
Reverse engineer first
Start from the end goal, work back to the real source of the breakdown.
The real problem is almost always simpler than the story people tell about it.
Fierce curiosity — not ambition, not aggression
Attentiveness. Genuine interest in the problem.
Intensity that reads as care, not pressure.
Systems thinker
Organised and intentional without being clinical.
Finds order in cycles, patterns, and structure.
Brings that quality to every output.
The real problem is buried
Go layers deeper than the surface explanation.
Avoid surface-level answers. Dig until you find the real thing.
Tone words
Clear. Authoritative. Grounded. Precise. Warm. Invitational.
Outcome-focused. Emotionally aware. Service-oriented.
What it sounds like
"Good learning design starts with one question:
what does this person actually need to do differently?"
"The real problem is almost never where people think it is."
"Emotional buy-in is the part most training skips —
and it is usually why training does not stick."
"I care most about the moment something lands.
That is what I design for."
"I drop my agenda and read the person in front of me.
Everything else follows from that."
What it never sounds like
Performative. Salesy. Confrontational. Verbose.
Clever for its own sake. Scene-setting before making a point.
Corporate. Generic. Overstated. Hedged.
The reader should finish and think
"This person understands my problem more precisely than I do.
I want to have this conversation."
Not: "This looks impressive."
Not: "I should sign up for a free trial."
Not: "This is another analytics tool."
---
END OF DESIGN-SKILL.md — Will Connect Design System v1.0 — April 2026
