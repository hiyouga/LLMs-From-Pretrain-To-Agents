# LLMs: From Pretrain To Agents - LaTeX Beamer Presentation

This directory contains a LaTeX Beamer presentation about the development history of Large Language Models (LLMs).

## Presentation Details

- **Title**: LLMs: From Pretrain To Agents
- **Author**: Yaowei Zheng
- **Date**: January 26, 2026
- **Theme**: Luebeck (with customizations)
- **Aspect Ratio**: 16:9
- **Font Size**: 12pt
- **Language**: English

## Files

- `main.tex` - Main LaTeX Beamer file (imports all parts)
- `part1_overview.tex` - Part 1: LLM Development Overview
- `part2_training_inference.tex` - Part 2: Training and Inference
- `part3_agents.tex` - Part 3: Agent Evolution
- `part4_future.tex` - Part 4: Future Development
- `LLMs_From_Pretrain_To_Agents.tex` - Legacy single-file version (deprecated)

## Content Overview

The presentation is divided into 4 main parts:

### Part 1: LLM Development Overview
- Transformer architecture
- Probabilistic modeling
- Scaling laws
- Emergent abilities

### Part 2: Training and Inference
- Pre-training strategies
- Post-training and alignment (SFT, RLHF)
- Multimodal alignment
- Inference acceleration techniques
- Reinforcement learning methods

### Part 3: Agent Evolution
- From model prompting to environment interaction
- Context and memory systems
- Web search integration
- Tool use and APIs
- Multi-agent systems

### Part 4: Future Development
- Long-horizon reinforcement learning
- Test-time compute and inference scaling
- Language-Use paradigm
- World models
- Continual learning and neuro-symbolic AI

## How to Compile

### Using pdflatex
```bash
pdflatex main.tex
pdflatex main.tex  # Run twice for TOC
```

### Using lualatex (recommended for better Unicode support)
```bash
lualatex main.tex
lualatex main.tex  # Run twice for TOC
```

### Using xelatex
```bash
xelatex main.tex
xelatex main.tex  # Run twice for TOC
```

## Requirements

You need a LaTeX distribution installed on your system:

- **Windows**: MiKTeX or TeX Live
- **macOS**: MacTeX
- **Linux**: TeX Live (install via package manager)

Required LaTeX packages (usually included in standard distributions):
- beamer
- Luebeck theme (part of beamer)

## Output

The compilation will generate:
- `main.pdf` - The final presentation PDF
- Auxiliary files (.aux, .log, .nav, .out, .snm, .toc) - Can be safely deleted after compilation

## Notes

- The presentation uses the Luebeck theme with customizations:
  - `\setbeamertemplate{headline}{}` removes the high headline
  - 16:9 aspect ratio for modern displays
  - 12pt font size for better readability
- Run the compilation command twice to ensure the table of contents is properly generated
- The modular structure (separate .tex files) makes it easy to edit individual sections
- The presentation is designed to be comprehensive yet concise, suitable for academic or professional settings
