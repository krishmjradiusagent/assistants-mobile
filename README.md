# Assistants mobile · Mel design handoff

Static export of the Mel mobile designs for developers (iOS Swift, Android Kotlin).

- `index.html` – browse every screen (open in a browser, or the Vercel link).
- `spec/*.md` – per-flow specs with designer notes and the exact on-screen copy. Start here, or paste into ChatGPT.
- `screens/<flow>/<Screen>.html` – static HTML snapshot of each screen. `screens/<flow>/png/` – PNG of each screen.
- `design-system/` – Radius Mobile design system: `README.md`, decisions, `tokens.json` (source of truth for colour, type, spacing), `components/<Name>/README.md`, `previews/<Name>.html`.
- `source/` – raw design source (`.dc.html`, Claude Design format). Reference only; needs the Claude runtime to run.
- `llms.txt` – index for AI assistants.

Flows: `assistants` (Mel chat, onboarding, CRM, Marketing, Campaign, Client Experience, SMS/email/WhatsApp), `voice` (voice mode, minimised bubble, iOS background states), `brand` (Mel brand guidelines).

Rules: use tokens, not hex from screenshots. Interactive prototypes are frozen at their first state. Voice copy is placeholder until approved.
