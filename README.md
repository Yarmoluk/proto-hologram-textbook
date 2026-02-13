# Proto Hologram — Intelligent Sales Enablement Textbook

[![GitHub Pages](https://img.shields.io/badge/Live_Site-GitHub_Pages-blue)](https://yarmoluk.github.io/proto-hologram-textbook/)
[![Chapters](https://img.shields.io/badge/Chapters-16-orange)](https://yarmoluk.github.io/proto-hologram-textbook/)
[![MicroSims](https://img.shields.io/badge/MicroSims-3-purple)](https://yarmoluk.github.io/proto-hologram-textbook/)

**Live Site:** [yarmoluk.github.io/proto-hologram-textbook](https://yarmoluk.github.io/proto-hologram-textbook/)

A dual-purpose intelligent textbook covering Proto Hologram technology and competitive intelligence. Combines a 7-chapter technology deep-dive with a 9-chapter competitive battlecard — both structured using Bloom's Taxonomy learning objectives, interactive MicroSims, and knowledge graph visualizations.

Built using Dan McCreary's intelligent textbook methodology as part of coursework for SEIS 666: Digital Transformation with AI at the University of St. Thomas.

## Structure

### Technology Textbook (`index.html`)
7 chapters covering holographic communication technology:
1. Introduction to Holography (Pepper's Ghost through modern volumetric displays)
2. Proto Product Line (Luma, M2, Epic — specifications and use cases)
3. How It Works (optics, spatial computing, AI integration)
4. Content Creation (live beaming, pre-recorded, text-to-hologram, AI avatars)
5. Applications (education, healthcare, retail, enterprise, entertainment)
6. ProtoOS Platform (Linux-based OS, cloud CMS, fleet management, SOC-2/HIPAA)
7. Future of Spatial Computing

### Competitive Intelligence (`competitive.html`)
9 chapters of sales enablement material:
- Market overview ($4.5B market, telepresence sub-market analysis)
- Proto's 5 competitive moats
- 10 competitor profiles (HYPERVSN, Looking Glass, ARHT Media, Holoconnects, Realfiction, Voxon, Google Beam, Samsung, MDH, Leia)
- Pre-written objection handlers for every major competitor
- 15-capability comparison matrix across 8 competitors

## Interactive Features

- **MicroSims (p5.js):** Holographic projection simulator, global beaming network animation, competitive landscape bubble chart
- **Knowledge Graphs (vis-network.js):** 24-node technology concept map, competitive relationship network
- **Glossaries:** 25 technology terms + 18 competitive intelligence terms
- **Bloom's Taxonomy:** Learning objectives at all 6 cognitive levels

## What Makes This Different

Unlike traditional sales decks, this structures competitive intelligence as a knowledge graph. When a prospect mentions a competitor, the sales rep doesn't search slides — the structured knowledge surfaces the right positioning, technical differentiators, and objection responses instantly.

This is one of several experiments testing whether the intelligent textbook approach works for sales enablement the same way it works for education, legal training, and clinical reference.

## Technology

Pure static HTML — no build process, no dependencies, no server required. Just HTML, CSS, p5.js, and vis-network.js.

```bash
git clone https://github.com/Yarmoluk/proto-hologram-textbook.git
# Open index.html in any browser
```

## Source Materials

- `proto-hologram-knowledge-base.md` — Complete technology reference (15K)
- `proto-hologram-competitive-intelligence.md` — Competitive battlecard (22K)
- `claude-project-instructions.md` — AI assistant configuration

## License

CC BY-NC-SA 4.0
