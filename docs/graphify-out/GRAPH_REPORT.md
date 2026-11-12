# Graph Report - cyberia-hardhat  (2026-11-12)

## Corpus Check
- 4 files · ~2,420 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 1 file(s) not represented in the graph (top: (none) 1)

## Summary
- 20 nodes · 21 edges · 3 communities (1 shown, 2 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `6ae0e490`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- hardhat.config.js
- deployObjectLayerToken.js

## God Nodes (most connected - your core abstractions)
1. `__filename` - 1 edges
2. `__dirname` - 1 edges
3. `coinbaseKey` - 1 edges
4. `config` - 1 edges
5. `__filename` - 1 edges
6. `__dirname` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Communities (3 total, 2 thin omitted)

### Community 0 - "hardhat.config.js"
Cohesion: 0.22
Nodes (4): coinbaseKey, config, __dirname, __filename

## Knowledge Gaps
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Not enough signal to generate questions. This usually means the corpus has no AMBIGUOUS edges, no bridge nodes, no INFERRED relationships, and all communities are tightly cohesive. Add more files or run with --mode deep to extract richer edges._