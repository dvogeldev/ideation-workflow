# Contributing

This fork of the ideation workflow is tuned for **Clief Notes** beginner engagement: an admin and two moderators turn community stuck points into ranked **beginner ICM article** briefs.

Upstream template: [banbury-cheese/ideation-workflow](https://github.com/banbury-cheese/ideation-workflow).

## Who this is for

| Role | How you help |
|------|----------------|
| **Clief Notes mods** | Run batches, edit stage outputs, assign article briefs in your brand voice |
| **Community members** | Suggest beginner topics, share stuck points, improve rubrics/examples |
| **Upstream contributors** | Prefer PRs that improve ICM stage contracts generally; fork-specific Clief Notes copy lives in `shared/` and this CONTRIBUTING |

## Quick path for mods

1. Collect raw input (Skool comments, DMs, Discord questions, competition confusion).
2. Open the workspace in Claude Code (or your usual agent) and run `intake`.
3. Review each stage output before continuing — edit freely; the next stage reads what you leave.
4. At Stage 05, prefer **article briefs** for teaching-shaped ideas (see `stages/05-strategy/references/article-brief-template.md`).
5. Assign top briefs across the three of you — each brief names one owner and one file in `shared/voices/`.
6. Park the rest.

See `docs/MODS.md` for cadence and `examples/sample-beginner-batch/` for a synthetic run.

## Brand voices

Do not commit voice docs that shouldn't be public without agreement. Placeholders live in `shared/voices/`. Each article loads **only** its owner's voice file.

## What to contribute

**High value**
- Clearer beginner examples in `examples/`
- Stronger stage `references/` (extraction, clustering, scoring) that stay ICM-faithful
- Article brief / content-calendar improvements in Stage 05
- Fixes to broken links or leftover placeholders

**Ask first**
- Changes to scoring weights in `_config/evaluation-criteria.md` (mod-team decision)
- Rewrites of `shared/channel-alignment.md` pillars
- Adding application code (Blazor, apps, etc.) — this repo is markdown ICM by design

## PR checklist

- [ ] No new `{{placeholders}}` left behind
- [ ] Stage contracts still have Inputs / Process / Outputs (and Checkpoint/Audit where present)
- [ ] Examples labeled synthetic if not from a real community batch
- [ ] Article briefs reference at most one voice file
- [ ] LICENSE remains MIT

## License

By contributing, you agree your contributions are licensed under the MIT License.
