# Mel brand guidelines

Mel brand guidelines: logo, color, gradients, pattern, typography, iconography, Mel in motion, buttons, motion and interactions, assistant accents.

Screens: 11. Each screen has a static HTML page (`/screens/brand/<File>.html`), a PNG (`/screens/brand/png/<File>.png`) and its raw design source (`/source/brand/<File>.dc.html`).
Tokens and components: see `/design-system/README.md`. Copy shown is real UI copy unless it says placeholder.

## Boards

Designer notes:

- **Mel brand guidelines · Mint**

### Cover
`Main` · 1440×900 · [HTML](/screens/brand/Main.html) · [PNG](/screens/brand/png/Main.png)

```text
mel
Brand guidelines

How Mel looks, moves, and sounds. Use this kit for the website, the product, social, and anything else that carries the Mel name.

MINT DIRECTION · V1 · OCTOBER 2026
01
Logo
02
Color
03
Gradients
04
Pattern
05
Typography
06
Iconography
07
Mel in motion
08
Buttons
09
Interactions
10
Assistants
```

Accessible labels: Mel; Mel, idle

### 01 · Logo
`Logo` · 1440×1280 · [HTML](/screens/brand/Logo.html) · [PNG](/screens/brand/png/Logo.png)

```text
MEL BRAND · 01
Logo

The Mel mark is the rounded shape with a living dot at its center. Wherever motion is possible, the dot gently pulses, like Mel is ready. Pair it with the lowercase wordmark, and never retype or redraw either one.

mel
Primary lockup · Mel Green mark with Deep Teal wordmark
Mark on Deep Teal
Reversed mark on Mel Green
App icon and favicon
mel
Wordmark only
mel
On Cloud
mel
On Deep Teal: white wordmark
mel
On the Morning gradient
CLEAR SPACE
mel
Keep clear space equal to twice the dot’s width on every side.
MINIMUM SIZE
mel
Lockup 80px wide. Mark alone 16px. Below 24px, the dot stays still.
DON'T
mel
Recolor it
mel
Stretch it
mel
Add effects
Rotate the mark
```

Accessible labels: Mel

### 02 · Color
`Color` · 1440×1440 · [HTML](/screens/brand/Color.html) · [PNG](/screens/brand/png/Color.png)

```text
MEL BRAND · 02
Color

Crisp white leads. Deep Teal carries the words, Mel Green signals Mel at work, and tints are used sparingly. No purple and no bright blue.

CORE
Deep Teal
#0E2B30 · 14 43 48
Headlines, body text, primary buttons, dark panels.
Mel Green
#12A867 · 18 168 103
The Mel mark, icons, live and active states. Not for small text.
White
#FFFFFF · 255 255 255
The main page background.
SUPPORTING
Green Text
#0B7A4D · 11 122 77
Accent words and links on light.
Mint
#3DDC97 · 61 220 151
Accents on dark, dots, glows.
Mint Pale
#BDEED4 · 189 238 212
Label pills, focus rings.
Mint Mist
#E2F5EA · 226 245 234
Icon tiles, soft cards.
Sky Mist
#E8F1F6 · 232 241 246
Second soft card tint.
Cloud
#F3F9F6 · 243 249 246
Section and hero grounds.
Slate
#4A5E61 · 74 94 97
Secondary text.
Teal 2
#173B41 · 23 59 65
Hover on dark buttons, panels.
Night
#08191C · 8 25 28
Pressed states, deepest panels.
Line
#DCE8E4 · 220 232 228
Dividers and borders.
PROPORTION
Mostly crisp white. Deep Teal for type and a few panels, tints only as accents, Mel Green in small, meaningful doses.
ACCESSIBLE PAIRS
Aa
Deep Teal on White
14.9:1 · AAA
Aa
White on Deep Teal
14.9:1 · AAA
Aa
Green Text on White
5.4:1 · AA
Aa
Deep Teal on Mel Green
4.8:1 · AA
Aa
Slate on White
6.9:1 · AA
Aa
Deep Teal on Mint Pale
11.6:1 · AAA
Aa
White on Mel Green
3.1:1 · AA large
```

### 03 · Gradients
`Gradients` · 1440×986 · [HTML](/screens/brand/Gradients.html) · [PNG](/screens/brand/png/Gradients.png)

```text
MEL BRAND · 03
Gradients

Soft light, not loud color. Gradients stay low-contrast and are mostly used as glows and washes behind content.

Hero wash
Light hero and large surfaces. Mint top-left, sky bottom-right.
Morning
Cards, feature panels and social backgrounds.
Mint glow
Blurred glow behind the Ask box or the Mel mark. Never behind body text.
Deep Teal
Dark panels and bands, with a faint mint light in one corner.
Signal
Progress, highlights and tiny accents. Never behind text.
Sky
Quiet section transitions.
Do keep washes subtle and let white dominate.
Do put the Mint glow behind Mel and the Ask box only.
Don't set text on Signal or on the brightest part of a glow.
```

### 04 · Pattern
`Patterns` · 1440×1240 · [HTML](/screens/brand/Patterns.html) · [PNG](/screens/brand/png/Patterns.png)

```text
MEL BRAND · 04
Pattern

One pattern: a fine dot grid. It adds a quiet, technical texture without competing with content. Use one per surface.

White
Dots · 12% Deep Teal
The default. Heroes and product panels.
Cloud
Dots · 12% Deep Teal
Quiet section backgrounds.
Mint Mist
Dots · 22% Mel Green
Behind Mel and feature cards.
Sky Mist
Dots · 10% Deep Teal
Secondary cards and panels.
Deep Teal
Dots · 24% Mint
Dark bands, quotes and calls to action.
Mel Green
Dots · 28% White
Small accents only, like social tiles.
GRID 12PX
DOT 1.4PX
SOFT EDGE 0.2PX
ONE COLOR, LOW OPACITY
Do keep it faint enough that text on top stays easy to read.
Do fade it out or crop it to part of a surface, like the right half of a hero.
Don't enlarge the dots, mix colors or layer it with other textures.
background-image: radial-gradient(circle, rgba(14,43,48,0.12) 1.4px, transparent 1.6px); background-size: 12px 12px;
```

### 05 · Typography
`Typography` · 1440×1424 · [HTML](/screens/brand/Typography.html) · [PNG](/screens/brand/png/Typography.png)

```text
MEL BRAND · 05
Typography

Mona Sans for everything: headlines, body, and labels. Headlines are set light and open, and small labels are uppercase and tracked out.

Aa
Mona Sans
The only typeface · Google Fonts
Aa
300 · Light
Aa
400 · Regular
Aa
500 · Medium
Aa
600 · Semibold
Aa
700 · Bold
ABCDEFGHIJKLMNOPQRSTUVWXYZ abcdefghijklmnopqrstuvwxyz 0123456789 $%&@
AA
Labels
Mona Sans 500 · uppercase · +1px tracking
MEL CAPABILITIES
MEET MEL · YOUR REAL ESTATE AI
11 SENT · SCHEDULED · 5 TO CALL
Display
Mona Sans 400 · 96 / 1.02 · -0.03em
AI for real estate.
Heading 1
Mona Sans 400 · 64 / 1.04 · -0.03em
Every lead followed up.
Heading 2
Mona Sans 500 · 44 / 1.08 · -0.025em
What Mel does for you.
Heading 3
Mona Sans 500 · 28 / 1.15 · -0.02em
Mel Client Experience
Body large
Mona Sans 400 · 20 / 1.55
Mel follows up with your leads, makes your marketing, and handles the paperwork, often before you even ask.
Body
Mona Sans 400 · 17 / 1.55
Every new lead gets a personal reply, day or night. Review anything first, or let Mel send it on its own.
Small
Mona Sans 500 · 14 / 1.45
Replied to Jordan R. in 40s · Booked Saturday at 10:00
```

### 06 · Iconography
`Iconography` · 1440×1022 · [HTML](/screens/brand/Iconography.html) · [PNG](/screens/brand/png/Iconography.png)

```text
MEL BRAND · 06
Iconography

Every icon lives inside the Mel shape. Glyphs are simple, rounded line drawings: one weight, round caps, no fills except small dots.

Campaigns
Design Studio
CRM
Client Experience
Documentation
Compliance
Commissions
Calendar
Voice
Working
Ask Mel
Location
ANATOMY
120 grid · glyph area 76 · 5px stroke at full size, round caps and joins
ON DARK
SIZES
24px
32px
48px
72px
GLYPH ONLY · INLINE UI
Use bare glyphs in Deep Teal or currentColor inside buttons, menus and tables. Use the tile version everywhere else.
```

### 07 · Mel in motion
`MelMotion` · 1440×1248 · [HTML](/screens/brand/MelMotion.html) · [PNG](/screens/brand/png/MelMotion.png)

```text
MEL BRAND · 07
Mel in motion

Mel is always a living dot. At rest it breathes slowly, and every other state changes only what happens at the center. Motion is gentle, never bouncy, and stops for reduced-motion users.

Idle · logo
IDLE
The resting mark. The dot breathes with a slow, soft ring and the shape floats gently.
Float 4px · ring 13→30px · 3.2s
Ready
READY
When Mel is active, the pulse gets a little stronger and quicker.
Ring 13→34px · 2.4s loop
Listening
LISTENING
Rings draw in toward the dot, like sound arriving.
Rings 40→15px · 1.8s · staggered 0.6s
Working
THINKING
Three dots step through while Mel drafts or searches.
Bounce 8px · 1.2s · 0.15s stagger
Speaking
SPEAKING
Voice bars move with Mel’s voice or a reply streaming in.
Bars 0.9s · 0.11s stagger
Done
DONE
The dot opens into a check when a task is complete.
Grow + draw check · 0.6s, then hold
Needs you
ATTENTION
Deep Teal shape, blinking mint dot and badge: something waits for your OK.
Blink 0.9s · use sparingly
Paused
OFFLINE
Quiet gray mark when Mel is off or disconnected.
Static
Easing: ease-in-out for loops, ease-out (0.2, 0.8, 0.2, 1) for one-time transitions.
Sequence: Ready → Listening → Working → Speaking or Done. Return to Ready after 2 seconds.
Reduced motion: show each state as a still frame: dot, rings, three dots, bars, and check.
```

Accessible labels: Mel, idle; Mel, ready; Mel, listening; Mel, thinking; Mel, speaking; Mel, done; Mel, attention; Mel, offline

### 08 · Buttons
`Buttons` · 1440×974 · interactive prototype (snapshot) · [HTML](/screens/brand/Buttons.html) · [PNG](/screens/brand/png/Buttons.png)

```text
MEL BRAND · 08
Buttons

Pill-shaped, confident and calm. Deep Teal is the default action, Accent is for Mel-specific actions like Ask, and every button shows a clear mint focus ring.

DEFAULT
HOVER
PRESSED
FOCUS
DISABLED
LOADING
Primary
Start free trial
Start free trial
Start free trial
Start free trial
Start free trial
Secondary
Book a demo
Book a demo
Book a demo
Book a demo
Book a demo
Accent
Ask Mel
Ask Mel
Ask Mel
Ask Mel
Ask Mel
Text link
Learn more
Learn more
Learn more
Learn more
Learn more
SIZES
Large
56px · 17px text
Medium
48px · 16px text
Small
36px · 14px text
ON DARK
Book a demo
Learn more
ICON BUTTON · ASK SEND
DEFAULT
HOVER
FOCUS
DISABLED
TRY IT · LIVE HOVER, PRESS AND KEYBOARD FOCUS
Start free trial
Book a demo
Ask Mel
Book a demo
Learn more
```

### 09 · Motion & interactions
`Motion` · 1440×1826 · interactive prototype (snapshot) · [HTML](/screens/brand/Motion.html) · [PNG](/screens/brand/png/Motion.png)

```text
MEL BRAND · 09
Motion & interactions

Small, quick, and calm. Motion tells you Mel heard you and that something changed. Everything on this board is live, so hover, click, and tab through it.

MEL EASE
Quick start, soft landing
cubic-bezier(0.2, 0.8, 0.2, 1)
FAST
150ms
Hover, press, and focus rings.
BASE
240ms
Icon states, cards, and small swaps.
REVEAL
360ms
Expanding, fading up, and sliding in.
Join the waitlist
See Mel work
Hover, press, or press Tab to see the focus ring.
Hover, press, and focus
BUTTONS
Buttons lift slightly on hover, press in on click, and always show the mint focus ring for keyboard users.
hover 150ms · lift 1px · press scale 0.97 · 100ms
Click the box, then press send.
Ask box and send
ASK MEL
The box glows mint when focused. On send, the Mel icon turns into working dots, then a check.
focus glow 200ms · icon cross-fade 240ms · dots 1.2s loop
Idle
Listening
Working
Done
State changes
MEL ICON
Mel changes state by cross-fading the center only. The shape never moves.
cross-fade + scale 0.92→1 · 240ms
CRM ASSISTANT
An AI CRM that updates itself.
Mel updates your contacts after every call or interaction.
Replay scroll
Section reveal
ON SCROLL
Text fades up in order, then the device animation starts. Plays once, when 20% of the section is in view.
fade up 16px · 360ms · 80ms stagger · device at 240ms
Marketing Design
Hover this card
Is Mel for agents or brokerages?

Both. Brokerages add compliance and documents.

How do I get access?

Join the waitlist, or use an invite code from someone already on Mel.

Hover and expand
CARDS AND FAQ
Cards lift on hover. FAQ answers open smoothly, and the chevron turns.
card lift 3px · 200ms · expand + chevron 180° · 300ms
Join
You’re on the list.
Skip the wait with an invite code.
Reset
Submit and confirm
WAITLIST
The button shows a spinner, turns into a check, then the confirmation slides in.
spinner ≥ 600ms · check 240ms · confirm slide 360ms
SPEC FOR THE BUILD
INTERACTION
WHAT MOVES
DURATION
EASING
Button hover
background, lift 1px, shadow
150ms
Mel ease
Button press
scale 0.97
100ms
Mel ease
Focus ring
3px white + 3px Mint
150ms
Mel ease
Ask box focus
Mint border, 4px Mint glow at 22%
200ms
Mel ease
Mel icon state
cross-fade, scale 0.92 → 1
240ms
Mel ease
Section reveal
opacity 0 → 1, y 16px → 0, 80ms stagger
360ms
Mel ease, once
Device demos
start at 40% in view, pause off screen
1900ms / step
loop
Card hover
lift 3px, shadow, Pale Mint border
200ms
Mel ease
FAQ expand
height + opacity, chevron 180°
300ms
Mel ease
Waitlist submit
spinner, check, confirmation slides up 12px
600 / 240 / 360ms
Mel ease
CSS TOKENS
:root {
  --mel-ease: cubic-bezier(0.2, 0.8, 0.2, 1);
  --mel-fast: 150ms;
  --mel-base: 240ms;
  --mel-reveal: 360ms;
}
@media (prefers-reduced-motion: reduce) {
  * { transition-duration: 0.01ms !important;
      animation: none !important; }
}
RULES
Do use one easing everywhere, and let motion confirm what just happened.
Don’t bounce, overshoot, or move anything more than 16px.
Reduced motion: skip movement, keep color and opacity changes, and show device demos as still frames.
```

Accessible labels: Mel; Ask Mel; Send; Mel, idle; Mel, thinking; Mel, done; Mel, listening; Email

### 10 · Assistants
`Assistants` · 1440×1856 · [HTML](/screens/brand/Assistants.html) · [PNG](/screens/brand/png/Assistants.png)

```text
MEL BRAND · 10
Assistants

Each of the six assistants uses the Mel mark in its own accent color, with its name in a matching pill. Mel Green stays Mel’s own color, so the assistants always read as part of Mel.

MARKETING DESIGN ASSISTANT
Coral
Posts, flyers, emails, and newsletters.
Accent
#EE6A4C
Pill
#FDE6DF
Pill text
#9A3418
CRM ASSISTANT
Lagoon
Contacts, notes, and AI insights.
Accent
#0FA3B1
Pill
#D5F1F3
Pill text
#0A5F68
CAMPAIGN ASSISTANT
Honey
Outreach and follow-up at scale.
Accent
#E9A320
Pill
#FCEFD3
Pill text
#7A5200
CLIENT EXPERIENCE ASSISTANT
Rose
Your branded app and website.
Accent
#E0588A
Pill
#FBE2EB
Pill text
#9A2351
COMPLIANCE ASSISTANT
Harbor
Auditing, checklists, and document seats.
Accent
#4479B3
Pill
#E1EAF5
Pill text
#244B78
DOCUMENTATION ASSISTANT
Cocoa
Offers and agreements, started by voice.
Accent
#9C6B4F
Pill
#F3E8E1
Pill text
#6A3E26
THE FAMILY
MEL
CORAL
LAGOON
HONEY
ROSE
HARBOR
COCOA
SMALL · IN NAV, MENUS, AND CARDS
MARKETING DESIGN ASSISTANT
CRM ASSISTANT
CAMPAIGN ASSISTANT
CLIENT EXPERIENCE ASSISTANT
COMPLIANCE ASSISTANT
DOCUMENTATION ASSISTANT
Do use an accent only for its own assistant: its mark, its pill, and small highlights on its pages.
Do keep the white living dot and the same shape. Only the shape’s color changes.
Don’t use accents for body text, buttons, or backgrounds, and never mix two assistant colors in one place.
```

Accessible labels: Mel
