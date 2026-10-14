# Startup Autopsy

**A Claude skill that checks your startup before it dies.**

Most dead startups died of the same handful of causes, and the warning signs were usually there early. Startup Autopsy reads your whole plan (idea, numbers, website, team, hiring) and checks it against those causes, the way a doctor checks symptoms against known diseases.

## What you get

- **A survival score out of 100**, broken down across 8 categories (demand, unit economics, runway, team, competition, go-to-market, legal, timing)
- **Your most likely cause of death**, with the line in your plan that points to it and roughly when it would hit
- **Graveyard twins**: 2-3 real dead startups that look like yours, what killed them, and how you differ
- **What to avoid**, ranked most dangerous first, each with a concrete fix
- **What's working**, so you know what to keep
- **Your next 30 days**: 3-5 testable actions that would raise the score

## How it works

1. **You give it your plan.** Paste it, attach a deck or doc, share your website URL, describe your team and hiring plan. Whatever you have.
2. **It tests your plan against the causes of death.** The checklist is built from CB Insights' analysis of 111 founder post-mortems (no market need, ran out of cash, got outcompeted, wrong team, pricing, and the rest), with the early warning signs and real companies that died of each one.
3. **It looks for startups like yours that already died.** With web search on, it checks startup failure databases such as the [vcbacked.co startup graveyard](https://www.vcbacked.co/startup-graveyard) (2,000+ shut-down venture-backed startups) for companies in your industry.
4. **It writes the report**, honest and specific. No cheerleading, no cruelty.

The score is a structured opinion, not a prediction. It's there to show you the risks while you can still fix them.

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download [`startup-autopsy.zip`](./startup-autopsy.zip) (click it, then the download button).
2. Make sure **Code execution and file creation** is on in **Settings > Capabilities**.
3. Go to **Customize > Skills**, click **+**, then **Create skill > Upload a skill**, and upload the zip.

Full guide: [Use Skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude)

### Claude Code

Copy the `startup-autopsy` folder into your skills folder:

```bash
git clone https://github.com/Stazkun01/Startup-Autopsy.git
mkdir -p ~/.claude/skills
cp -r Startup-Autopsy/startup-autopsy ~/.claude/skills/
```

Docs: [Claude Code skills](https://code.claude.com/docs/en/skills)

## Use it

Just ask, in any chat:

> Run a startup autopsy on my plan: [paste your plan, attach your deck, or drop your website]

Or anything like "roast my startup", "will this work?", "what could kill us?". In Claude Code you can also type `/startup-autopsy`.

The more you give it (real numbers, team, website), the sharper the report. Missing pieces get marked as unknown instead of guessed.

## What's inside

```
startup-autopsy/
├── SKILL.md                      # how the audit runs, the scoring, the report format
└── references/
    └── failure-patterns.md       # the causes of death, warning signs, real examples, fixes
```

## License

MIT. Use it, fork it, improve it. If it saves your company, tell me about it.
