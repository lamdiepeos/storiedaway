# EOS StoryTraffic Content Automation System

This workspace is organized around an episode-centric production flow. Global ingestion and ranking live at the root, while each produced story gets its own self-contained folder under `episodes/`.

## Workflow

1. Collect competitor material into `sources/`.
2. Evaluate and rank candidates in `evaluation/`.
3. Create or duplicate an `episodes/ep-XXX/` folder for each selected story.
4. Execute rewriting, hook optimization, ending expansion, segmented story packaging, intro generation, metadata prep, and output packaging inside that episode folder.

## Directory Map

```text
./
├── sources/       <- Global scraped inputs and metadata
├── evaluation/    <- Cross-story ranking logic and review artifacts
└── episodes/      <- One folder per production-ready story episode
```

## Episode Package Rule

Each `episodes/ep-XXX/` folder should contain the full working set for one story:

- `source-reference.txt`
- `[story-slug]-full-story.txt`
- `[story-slug]-part-1.txt` through `[story-slug]-part-N.txt`
- `video-intro.md`
- `publish-metadata.md`
- `generation-process.md`
- `outputs/`

Do not split a single episode's deliverables across unrelated root folders.
