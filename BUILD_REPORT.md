# Build Report — ThoughtGraph

**Date:** 2026-03-27
**Build Duration:** ~15 minutes
**Status:** SUCCESS

## What Was Built

**ThoughtGraph** — An interactive personal knowledge graph that lets you capture ideas as nodes and automatically discovers connections using TF-IDF text similarity, visualized with D3.js force-directed graphs.

## Inspiration Sources

- "Personal Encyclopedias" (whoami.wiki) trending on Hacker News front page
- Product Hunt trend toward AI-powered personal knowledge tools
- Growing community interest in Zettelkasten/Second Brain methodologies
- GitHub trending: agentic AI tools and personal productivity apps

## Tech Decisions

- **Single HTML file**: Maximum portability, zero build complexity, instant deployment
- **D3.js v7**: Industry-standard force-directed graph with smooth physics simulation
- **Vanilla JS TF-IDF**: No API calls needed, all computation runs client-side
- **localStorage**: Simple persistence, no backend required
- **CSS custom properties**: Clean dark/light theme toggling

## Features Delivered

1. Add/edit/delete thoughts with title, content, and tags
2. Automatic connection discovery via TF-IDF cosine similarity
3. Interactive force-directed graph with drag, zoom, pan
4. Color-coded tags with filtering
5. Full-text search
6. JSON import/export
7. Dark/light mode
8. Keyboard shortcuts (N = new, / = search, Esc = close)
9. Detail panel showing connection strength percentages
10. Sample data for immediate demo experience

## Scoring

| Criterion | Weight | Score | Weighted |
|-----------|--------|-------|----------|
| Novelty | 3x | 8 | 24 |
| Feasibility | 3x | 9 | 27 |
| Wow Factor | 2x | 9 | 18 |
| Learning Value | 2x | 8 | 16 |
| Utility | 1x | 8 | 8 |
| **Total** | | | **93/110** |

## Deployment

- **GitHub:** https://github.com/middesurya/daily-webapp-2026-03-27-thoughtgraph
- **Live:** https://thought-graph-green.vercel.app

## Lessons Learned

- Static HTML vercel.json `{"cleanUrls": true}` works perfectly for single-file apps
- TF-IDF cosine similarity with a threshold of 0.08 produces meaningful connections without too much noise
- D3 force simulation needs collision force to prevent node overlap
- Sample data is essential for a good first impression — empty state kills wow factor
