# hormozi-playbook

A Claude skill that applies Alex Hormozi's frameworks ($100M Offers, Leads, Money Models, Scaling Roadmap) to Brendan's ventures, Moozy first.

## Layout
- `SKILL.md` — the skill: modes, frameworks, scorecard, guardrails. Keep it short.
- `references/` — loaded on demand:
  - `templates.md` — output shapes per mode, plus a worked Moozy example
  - `money-models-leads.md` — attraction/upsell/downsell/continuity menus, lead magnets, rule of 100
  - `scaling-roadmap.md` — all stages 0-9 verified from Acquisition.com guides
  - `ventures.md` — facts about each venture (fill the TODOs)
- `tests/prompts.md` — sample requests and expected behavior; run after edits.
- `docs/AUDIT.md` — the 2026-11-04 source audit of the skill against the downloaded Acquisition.com files.

Source PDFs and archives are not stored here (see `.gitignore`). The roadmap guides come from `acquisition.com/hubfs/0-100M Scaling Course PDFs (v6)/` as `Your_ACQ_100MScalingRoadmap-Stage0N_.pdf` (Stage 0 is `...-Stage0_.pdf`).

## Open items
- Fill the TODO fields in `ventures.md`.
- Keep sensitive costs and pay data out of this repo.
