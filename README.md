# Formalization Game

A prototype game that teaches how to formalize mathematics in Lean 4. Each level pairs an English statement with a Lean formalization. You find where they differ, or certify that they match.

Inspired by the [Natural Number Game](https://github.com/leanprover-community/NNG4), which teaches proving. This game teaches the step before: stating.

## Run it

Open `index.html` in a browser. It is a single self-contained page with no build step.

## What's in it

- A world map of 8 worlds; 6 are playable, 2 are planned.
- 13 hand-written levels covering ℕ subtraction, numeral defaulting, junk values, connectives, quantifiers and ranges.
- Probes that plug a value into both statements and show whether they agree.
- Hints for wrong clicks, and a field guide that collects each level's pattern.

Nothing runs Lean yet. Level verdicts are written by hand.
