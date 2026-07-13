# EOS StoryTraffic Content Automation System

## What This Project Is
This project is a content automation system focused on identifying high-performing competitor stories, evaluating their engagement potential, and converting the strongest candidates into fully completed, high-quality story outputs. It is designed to support a repeatable editorial pipeline rather than one-off creative writing.

The workflow starts with scraping or collecting competitor content and associated metadata. Those inputs are then evaluated with LLM-assisted analysis and historical performance signals to rank stories by intrinsic hook strength, engagement potential, and suitability for adaptation. The system is explicitly constrained to evaluate and build from real scraped material rather than hallucinating fresh plot foundations during selection.

Once a story is selected, the project rewrites it into a stronger publishable version. That includes changing names and style where useful, rebuilding the opening into a higher-CTR Super Hook, and extending the story deeply enough to deliver a concrete, satisfying ending. Execution is episode-centric: each story adaptation lives inside its own `episodes/ep-XXX/` folder containing the script, intro materials, publishing metadata, traceability log, and final assets.

## Who It's For
- Internal content operators managing story sourcing, adaptation, and publishing preparation.
- Editorial or growth teams that need a repeatable pipeline for high-retention story content.
- AI-assisted production workflows where traceability, evaluation discipline, and output completeness matter.

## Key Goals
- Build a reliable workflow for scraping and organizing competitor story inputs.
- Rank candidate stories using source-grounded evaluation and engagement logic.
- Rewrite and extend selected stories without breaking their core narrative spine.
- Produce stronger hook-driven openings optimized for retention and virality.
- Ensure every final story has a concrete and comprehensive ending.
- Generate publish-ready raw materials, including a 10-second intro script and keyframe prompt.

## Constraints & Context
- Selection and ranking must be grounded in actual scraped source material.
- The system should not hallucinate entirely new plot foundations during evaluation.
- Rewriting may strengthen and reframe the hook, but must preserve the underlying narrative spine.
- Final outputs must be complete packages suitable for downstream publishing workflows.
- Per-episode production artefacts should stay bundled together so a single story can be reviewed, revised, and published without searching across unrelated root folders.
- Technical stack, scraping targets, and automation tooling are still TBD and should be documented as they become concrete.
