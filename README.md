# Claude Developer Practice — quizmill practice pack

**Unofficial** practice for the **Claude Certified Developer – Foundations (CCDV-F)** exam. Not
affiliated with or endorsed by Anthropic.

This is a learning pack for [quizmill](https://github.com/quizmill/quizmill).
The pack is pure JSON; the engine turns it into an installable, offline-first
practice app.

## What's in it

**53 questions** (45 single-answer, 8 "select TWO") from
Matthew Purcell's [CCDV-F full practice question set](https://www.linkedin.com/feed/update/urn:li:activity:7484728794990354432/). It matches the live exam's item count, weighted to the
exam blueprint, with his rationale on every answer. The app offers it as the paper
"CCDV-F practice exam"; the domains below are also practised one by one.

| Domain | Weight | Questions |
|---|---|---|
| Agents and Workflows | 14.7% | 8 |
| Applications and Integration | 33.1% | 17 |
| Claude Code | 3.1% | 2 |
| Eval, Testing, and Debugging | 2.6% | 1 |
| Model Selection and Optimization | 16.8% | 9 |
| Prompt and Context Engineering | 11% | 6 |
| Security and Safety | 8.1% | 4 |
| Tools and MCPs | 10.6% | 6 |

His advice: 120 minutes for the whole set, the live exam's time limit, and
aim for about 75% in every domain.

## Run it

```
npx quizmill run quizmill/pack-claude-cert-developer
```

## Checking the pack

```
npx quizmill validate .
```

See [NOTICE.md](NOTICE.md) for attribution.
