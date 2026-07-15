# Generation Process

## Episode ID
- `ep-009-marriage-behind-half-open-door`

## Input and Source Handling
- Read local capture `ep9_1378901077588504.json` without modifying it.
- Used the two captured story fields embedded in the valid leading JSON object.
- Ignored an unrelated suffix after the closing JSON object that prevents strict whole-file parsing.
- Recorded but did not browse or consult the external continuation link.
- Treated comments as audience/context signals only.

## Source Facts Preserved
- Quiet house, amber bedside lamp, old floorboards, barefoot wife in a white pajama top, half-open wooden door, husband on the bed beside his silver-haired mother.
- Husband's statements about pretending and waking his wife; mother's warnings to lower his voice.
- Door confrontation, initial false-love admission, mother's claim that the wife needed stability and the house, husband's claim that his love became real, and the hidden reason for the marriage.

## Editorial Decisions and Generated Expansion
- Renamed the wife, husband, and mother as Claire Arden, Adrian Vale, and Sylvia Vale.
- Grounded Claire's vulnerability in a documented-in-story crash recovery while preserving her agency and avoiding a helpless resolution.
- Explained the marriage as part of a fraudulent trust-control plan rather than leaving the motive vague.
- Required Adrian to admit complicity, provide evidence, accept annulment and criminal consequences, and rebuild without treating later love as an excuse.
- Extended the ending through asset recovery, institutional safeguards, a legal clinic, gradual trust repair, independent legal protections, and a freely chosen second marriage.

## Structure and Length Intent
- Four sequential parts with unique ALL-CAPS first-line titles.
- Each part targets 500-1,000 words and favors the upper half without filler.
- Full story has a distinct ALL-CAPS title and reproduces the four finalized parts in order.
- Final part closes with the exact marker `THE END`.

## Trailer and Image Logic
- Trailer restricted to the first 15 seconds of finalized Part 1.
- Five spoken lines copied verbatim from Part 1.
- Keyframe is the exact frozen hallway/guest-room state before Adrian moves or speaks.
- Independent cover uses the truthful Part 2 case-and-phone confrontation rather than expanding the keyframe.
- Generated both primary images with the built-in image-generation workflow, then inspected the episode-root files at original detail.
- Keyframe final: `marriage-behind-half-open-door-keyframe.png`, 941x1672 portrait, stored directly at the episode root.
- Website hook cover final: `marriage-behind-half-open-door-cover-photo.jpg`, normalized to 1920x1080 landscape at high JPEG quality and stored directly at the episode root.
- The cover used the keyframe as a strict character, wardrobe, room, and lighting reference while depicting the distinct truthful Part 2 phone-and-case confrontation.

## QA Record
- Source traceability and malformed-suffix handling: Passed
- ALL-CAPS titles and renamed-character consistency: Passed
- Per-part word counts: Passed at 768, 821, 786, and 815 words
- Full/part equivalence: Passed; 3,196-word full story matches all four parts
- Exact `THE END`: Passed
- Part 1 trailer dialogue: Passed; five exact lines occur once in Part 1 and once in the prompt
- Prompt format: Passed; exactly two required sections and a 93-word keyframe prompt
- Keyframe continuity, visual inspection, and episode-root file presence: Passed
- Cover hook fidelity, 1920x1080 dimensions, visual inspection, and episode-root file presence: Passed
- Asset completeness: Passed
