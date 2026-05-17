# Contributing to Lumi

Thanks for helping improve Lumi.

## What helps most

Lumi benefits most from contributions that improve:
- native macOS feel
- rendering stability
- panel ergonomics
- keyboard-first workflow quality
- release quality and documentation

## Before you start

Please:
1. check whether an issue already exists
2. keep changes focused and incremental
3. avoid mixing product redesigns with bug fixes
4. note any UX tradeoffs clearly in the PR

## Development basics

```bash
swift build
swift run Lumi
```

Open the project in Xcode by opening `Package.swift`.

## PR expectations

For UI changes, include:
- a short before/after summary
- screenshots or a short screen recording when useful
- testing notes

For behavior changes, include:
- what changed
- why it changed
- what you verified manually

## Stability bar

Lumi is currently a polish-heavy native utility project. Please bias toward:
- stability over cleverness
- calmness over feature noise
- minimal safe changes over broad rewrites

## Areas to avoid in drive-by PRs

Please avoid large uncoordinated changes to:
- startup lifecycle
- panel window architecture
- rendering/compositor assumptions
- global hotkey behavior

If you want to work in those areas, open an issue or draft PR first so we can align on approach.
