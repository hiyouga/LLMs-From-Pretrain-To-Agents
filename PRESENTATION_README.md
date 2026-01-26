# LLMs: From Pretrain To Agents - LaTeX Beamer Presentation

This directory contains a LaTeX Beamer presentation about the development history of Large Language Models (LLMs).

## Presentation Details

- **Title**: LLMs: From Pretrain To Agents
- **Author**: Yaowei Zheng
- **Date**: January 26, 2026
- **Theme**: Luebeck
- **Language**: English

## File

- `LLMs_From_Pretrain_To_Agents.tex` - Main LaTeX Beamer source file

## Content Overview

The presentation covers:

1. **Introduction to Large Language Models** - What are LLMs and their key characteristics
2. **Early Days: Foundation Models** - Word embeddings and the Transformer revolution
3. **The Pre-training Era** - BERT, GPT series, and other notable models
4. **Instruction Tuning and Alignment** - From pre-training to instruction following, RLHF
5. **Modern Era: Large-Scale LLMs** - Current landscape and open-source revolution
6. **LLM Agents: The Frontier** - What are agents, frameworks, capabilities, and applications
7. **Challenges and Future Directions** - Current challenges and future outlook
8. **Conclusion** - Summary and key takeaways

## How to Compile

### Using pdflatex
```bash
pdflatex LLMs_From_Pretrain_To_Agents.tex
pdflatex LLMs_From_Pretrain_To_Agents.tex  # Run twice for TOC
```

### Using lualatex (recommended for better Unicode support)
```bash
lualatex LLMs_From_Pretrain_To_Agents.tex
lualatex LLMs_From_Pretrain_To_Agents.tex  # Run twice for TOC
```

### Using xelatex
```bash
xelatex LLMs_From_Pretrain_To_Agents.tex
xelatex LLMs_From_Pretrain_To_Agents.tex  # Run twice for TOC
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
- `LLMs_From_Pretrain_To_Agents.pdf` - The final presentation PDF
- Auxiliary files (.aux, .log, .nav, .out, .snm, .toc) - Can be safely deleted after compilation

## Notes

- The presentation uses the Luebeck theme, which provides a professional appearance with a sidebar navigation
- Run the compilation command twice to ensure the table of contents is properly generated
- The presentation is designed to be comprehensive yet concise, suitable for academic or professional settings
