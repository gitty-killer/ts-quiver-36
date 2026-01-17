# ts-quiver-36

A small TypeScript tool that computes text statistics for quiver.

## Goal
- Provide quick text metrics for quiver documents.
- Report top word frequencies for fast inspection.

## Usage
ts-node index.ts data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Notes
- Only ASCII letters and digits are treated as word characters.
