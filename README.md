# 🎨 Primordial

An evolutionary art engine that uses genetic algorithms to create unique digital artworks through natural selection.

## What It Does

Primordial evolves populations of digital organisms (genomes) that represent abstract artworks. Each genome contains:
- **Colors** - Hue, saturation, lightness palettes
- **Shapes** - Circles, rectangles, triangles, lines, arcs
- **Movements** - Rotation, translation, pulsing animations
- **Parameters** - Complexity, symmetry, rhythm, density

Through tournament selection, crossover, and mutation, these genomes compete for survival based on aesthetic fitness criteria.

## Features

- 🧬 **5 Fitness Environments** - Balanced, Symmetry, Chaos, Minimalist, Organic
- 🎯 **Multi-Objective Optimization** - Custom weight balance across 4 objectives
- 🏆 **Hall of Fame** - Auto-saves top performers across generations
- 📊 **Evolution Tracking** - Real-time fitness charts
- 🔬 **Genome Comparison** - Visual and statistical analysis
- 🎲 **Seeded Random** - Reproducible evolution
- 💾 **Export System** - Save artworks and Hall of Fame archives
- 🎨 **Breeding Mode** - Manually cross-breed favorite genomes

## Quick Start

1. Open `index.html` in a modern browser
2. Click "Auto-Evolve" to start evolution
3. Watch as art emerges from randomness
4. ⭐ Favorite interesting genomes
5. Export your favorites or the entire Hall of Fame

## Evolution Parameters

- **Mutation Rate** - Probability of random changes
- **Population Size** - Number of genomes per generation
- **Elitism** - Top N genomes guaranteed survival
- **Tournament Size** - Selection pressure strength

## Environments

Each environment rewards different aesthetic qualities:

- **Balanced** - Rewards complexity, color harmony, and movement
- **Symmetry** - Prefers ordered, patterned compositions  
- **Chaos** - Favors high complexity and unpredictability
- **Minimalist** - Simple, clean, zen aesthetics
- **Organic** - Flowing forms and natural color palettes

## Technical Details

Built with:
- Vanilla JavaScript (ES6+)
- HTML5 Canvas for rendering
- Web Audio API for sound synthesis
- Chart.js for fitness visualization
- JSZip for Hall of Fame exports

Genetic algorithm features:
- Tournament selection
- Single-point crossover
- Gaussian mutation
- Elitism preservation
- Multi-objective fitness evaluation

## Origin Story

Built in approximately 4 hours on a mobile device using HTML editor apps. 

Because sometimes the best projects come from boredom.

---

*"From chaos, beauty emerges"*
```


Features reproducible evolution via seeded random 
generation, comprehensive genome analysis tools, and 
automated archiving of top-performing specimens.
