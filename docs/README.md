# /docs — Reference Material for the Spotzer Sales Script

Drop any relevant files here so Claude can pick them up at the start of a new chat without you having to re-paste context.

## What to put here

- **Product info** — pricing sheets, package details, plan comparisons, feature lists
- **Customer info** — Telenet customer lists, segment notes, account history exports
- **Call material** — recordings transcripts, objection logs, real-call notes, win/loss reasons
- **Brand & messaging** — tone of voice, approved language, do-not-say lists
- **Process docs** — sign-up flow, salesforce screenshots, approval call scripts
- **Competitor info** — what other providers in the Belgian SMB market are doing
- **Anything else** that would help Claude give better answers about the script

## Suggested file types

- `.md` — best for notes, lists, structured info (Claude reads these natively)
- `.txt` — fine for plain notes or transcripts
- `.pdf` — Claude can read these directly
- `.csv` / `.xlsx` — for customer lists or pricing tables
- `.png` / `.jpg` — screenshots, designs, reference images

## How to use in a new chat

At the start of a conversation, just say:
> "Check the /docs folder for relevant context"

Or point to a specific file:
> "Use /docs/pricing-2026.pdf as the source for pricing"

## Suggested subfolders (optional)

Create these as needed — no need to make them all upfront:

```
docs/
├── product/         # Pricing, package details, product specs
├── customers/       # Customer lists, segment notes
├── calls/           # Transcripts, real-call learnings
├── brand/           # Tone of voice, messaging guidelines
├── process/         # Sign-up flow, internal process docs
└── reference/       # Anything else (competitor info, market data)
```
