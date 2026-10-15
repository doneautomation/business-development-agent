# Business Development Agent

An open-source business development skill for small service businesses. It helps you find prospects, score them against a qualification rubric, and draft outreach. It is built as a set of stages you can run on their own or together.

> Status: early structure. Frameworks and templates are placeholders until filled in.

## What it does

| Stage | Purpose | Folder |
|---|---|---|
| Attract | Plan content and posts that bring prospects to you | `skills/attract/` |
| Prospect | Scan job boards and listings, score leads, pick an offer | `skills/prospect/` |
| Engage | Reply to threads, post in communities, run events | `skills/engage/` |
| Close | Proposal, deposit, and handoff to delivery | `skills/close/` |

## Setup

1. Copy `config/config.example.yaml` to `config/config.yaml`.
2. Fill in your offers, pricing bands, qualification thresholds, and tools.
3. Keep `config/config.yaml` out of version control (it is in `.gitignore`).

## Principles

- Lead with outcomes, not tools.
- Qualify before you pitch.
- Never invent results, testimonials, or client names.
- Every draft is reviewed by a human before it is sent.

## License

MIT. See `LICENSE`.

## Contact

Built and maintained by [Done Automation](https://doneautomation.com).

- Questions or customization help: open a GitHub issue on this repo, or visit [doneautomation.com](https://doneautomation.com).
- Bug reports and improvements: pull requests are welcome (see `CONTRIBUTING.md`).
