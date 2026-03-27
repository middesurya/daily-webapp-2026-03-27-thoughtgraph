# ThoughtGraph — Personal Knowledge Graph

## Overview
An interactive personal knowledge management tool that lets you capture ideas as nodes and automatically discovers connections between them using text similarity. Beautiful force-directed graph visualization powered by D3.js.

## Inspiration
- "Personal Encyclopedias" trending on Hacker News (whoami.wiki)
- Growing trend of personal knowledge management (PKM) tools
- Community interest in visual thinking and mind mapping

## Core Features
1. **Add Thoughts** — Quick capture of ideas, notes, snippets with optional tags
2. **Auto-Linking** — Automatic discovery of connections using TF-IDF text similarity
3. **Interactive Graph** — D3.js force-directed graph with zoom, pan, drag
4. **Node Details** — Click nodes to view, edit, or delete thoughts
5. **Tag System** — Color-coded categories/tags for organization
6. **Search & Filter** — Full-text search and tag filtering
7. **Import/Export** — JSON export/import for data portability
8. **Dark/Light Mode** — Toggle between themes

## Tech Stack
- Single HTML file with embedded CSS and JavaScript
- D3.js v7 for force-directed graph visualization
- Vanilla JS for text similarity (TF-IDF implementation)
- localStorage for persistence
- No build tools, no framework — pure web standards

## Scoring
- Novelty (3x): 8/10 — Knowledge graphs exist but auto-linking via text similarity in a lightweight browser app is fresh
- Feasibility (3x): 9/10 — Single HTML + D3.js, no backend needed
- Wow Factor (2x): 9/10 — Interactive node graph is visually stunning
- Learning Value (2x): 8/10 — D3.js force simulation, TF-IDF, graph theory
- Utility (1x): 8/10 — Everyone takes notes, visual connections add real value
- **Total: 93/110**

## Date
2026-03-27
