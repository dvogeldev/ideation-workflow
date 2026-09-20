# Stage 05 — Strategy & Delivery Plan

Take the prioritized and classified list from Stage 04 and produce an actionable delivery strategy. For Clief Notes beginner engagement, prefer **article briefs** for teaching-shaped ideas. For MWP-track build items, outline the workspace. For Software-track items, outline the technical approach. Align everything to a content calendar that reinforces the channel.

## Inputs

| Source | File/Location | Section/Scope | Why |
|--------|--------------|---------------|-----|
| Previous stage | `../04-prioritization/output/` | Most recent priorities file (full) | Ranked and classified ideas |
| Previous stage | `../01-intake/output/` | Most recent idea cards (full) | Original detail for deliverable specs |
| Config | `../../_config/mwp-fit-checklist.md` | Full file | MWP workspace requirements |
| Shared | `../../shared/channel-alignment.md` | Full file | Pillars, audience, goals |
| Shared | `../../shared/voices/README.md` | Full file | Owner → brand voice mapping |
| Reference | `references/delivery-templates.md` | Full file | Strategy document format |
| Reference | `references/article-brief-template.md` | Full file | Beginner article brief format |

## Process

1. Read priorities from `../04-prioritization/output/`
2. Split items into **teaching-shaped** (article-first) vs **build-shaped** (MWP/software)
3. For each **teaching-shaped** item (starting from highest priority):
   - Produce an article brief using `article-brief-template.md`
   - Assign a tentative owner and voice file from `shared/voices/`
   - Note pillar, engagement hook, and draft-by suggestion
4. For each **MWP-track** build item (starting from highest priority):
   - Outline the workspace: how many stages, what each stage does, what the pipeline transforms
   - Note which content pillar it feeds and what channel content the build process would generate
   - Estimate scope: can it be built with the workspace-builder, or does it need custom design?
   - Note what community value it delivers and how it would be handed off
5. For each **Software-track** item (starting from highest priority):
   - Outline the technical approach: what needs to be built, what stack, what integrations
   - Note whether any MWP components could handle part of the workflow
   - Estimate scope and key technical decisions
6. For **Hybrid** items: split into MWP portion and software portion with clear boundaries
7. Sequence the delivery order:
   - Article quick wins first (high beginner impact, low effort)
   - Then heavier articles or MWP builds
   - Group items that share a pillar or can be published as a series
8. Map deliverables to a content plan and confirm each assigned article names exactly one voice file
9. **[Checkpoint]** Present strategy to user / mod team
   - Validate delivery sequence and owners
   - Confirm content plan alignment
   - Approve or adjust scope for top priorities
10. Incorporate feedback
11. Run audit checks
12. Save to output/

## Checkpoint

| After Step | Agent Presents | Human Decides |
|------------|---------------|---------------|
| 9 | Full strategy: article briefs (with owners/voices), MWP outlines, software specs, delivery sequence, content plan | Validate sequence, assign owners, adjust scope, approve top priorities |

## Audit

| Check | Pass Condition |
|-------|---------------|
| Full coverage | Every item from Stage 04's top priorities has a delivery outline |
| Article briefs | Every teaching-shaped top item has: pillar, owner, voice file, outline, engagement hook |
| Single voice | No article brief references more than one voice file |
| MWP workspace specs | Every MWP-track build item has: stage count, stage purposes, pipeline transformation, scope estimate |
| Software specs | Every Software-track item has: technical approach, stack, key decisions |
| Delivery sequence | Items are ordered with rationale (not just priority score — considers dependencies and quick wins) |
| Content mapping | At least the top 5 deliverables have associated content plan entries |
| Thesis reinforcement | Strategy explicitly notes which deliverables demonstrate the MWP/ICM thesis |

## Outputs

| Artifact | Location | Format |
|----------|----------|--------|
| Delivery strategy | `output/[batch-slug]-strategy.md` | Markdown with article backlog/briefs, workspace outlines, software specs, delivery sequence, content plan |
