will-connect-design-system
This repository is the single source of truth for all Will Connect design assets,
brand rules, and system files.
It is built to be read by Claude Design (CDes), Claude Code, or any AI agent
that can navigate a folder structure and read markdown files.
Read this file first. Then follow the routing below.
---
What This Repository Is
A structured design system that gives any AI tool everything it needs
to produce accurate, on-brand Will Connect outputs — without being re-briefed each session.
It contains:
Brand rules (colour, typography, voice, copy)
The design system skill file (how to use all of the above)
Reusable components (built once, referenced always)
The Will Connect logo mark (SVG)
Font files (self-hosted — Open Sauce One and Aileron)
It does not contain:
Product logic or diagnostic scoring rules (see main Claude project)
Pitch deck content (see main Claude project)
X content arc (see main Claude project)
---
Folder Structure
```
will-connect-design-system/
│
├── README.md                    ← You are here. Read first.
│
├── _skills/
│   └── DESIGN-SKILL.md          ← Master skill. Read before generating anything.
│
├── _brand/
│   ├── palette.md               ← All hex codes and usage rules
│   ├── typography.md            ← Font stack, sizes, weights, loading rules
│   ├── voice.md                 ← Tone, principles, what it sounds like
│   ├── copy-rules.md            ← Absolute copy rules — no exceptions
│   └── logo-mark.svg            ← Will Connect logo SVG (gold ellipses)
│
├── assets/
│   └── fonts/
│       ├── OpenSauceOne-Bold.woff2
│       ├── OpenSauceOne-Regular.woff2
│       ├── Aileron-SemiBold.woff2
│       └── Aileron-Light.woff2
│
├── components/
│   ├── nav.html                 ← Navigation bar (logo + CTA)
│   ├── hero.html                ← Hero section
│   ├── stat-card.html           ← Gold stat cards with count-up animation
│   ├── domain-card.html         ← Five domain cards (Structure/Entry/Risk/Volume/Emotional)
│   ├── output-card.html         ← 01/02/03 numbered output cards
│   ├── cep-dashboard.html       ← Community Execution Profile dashboard mockup
│   └── footer.html              ← Footer
│
└── pages/
    └── landing-v1.html          ← Complete landing page (populated after first build)
```
---
How to Use This Repository
In Claude Design (CDes)
Go to Design Systems → Create New
Link this GitHub repository
CDes will read DESIGN-SKILL.md and all _brand/ files
The design system will generate from these files
Start any new project by selecting the Will Connect design system
In Claude Code
Open a new session pointed at this folder
Type: /init or instruct Claude to read README.md first
Claude will navigate the folder structure using the paths above
Reference components by path — do not rebuild what already exists
In any other AI tool
Feed DESIGN-SKILL.md as the primary context file
Reference _brand/ files as needed for specific decisions
The skill file routes everything — start there
---
Non-Negotiables (repeat for emphasis)
Fonts: Open Sauce One (primary) + Aileron (secondary) — never substitute
Colours: follow palette.md exactly — no deviations
Logo: always the SVG ellipses from /_brand/logo-mark.svg — never text only
Voice: read voice.md before writing a single word
Copy rules: read copy-rules.md — these are absolute
---
Version
Design System v1.0 — April 2026
Owner: Steve Willis — Will Connect
Repository: github.com/willwillis888/will-connect-design-system
