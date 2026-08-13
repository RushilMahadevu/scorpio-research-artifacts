[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21924456.svg)](https://doi.org/10.5281/zenodo.21924456)

# Scorpio Research Artifacts for [Scorpio Main Repository](https://github.com/RushilMahadevu/scorpio)

This repository contains the research artifacts for the paper: 
*"Scorpio: A Verifiable Framework for Enforcing Socratic Scaffolding in Physics LLMs Beyond Fine-Tuning."*

## 🔬 Overview
Scorpio is a modular constraint architecture designed to bridge the "helpfulness-learning gap." 
By layering inference-time rules, we achieve a **0% Direct Answer Rate** without expensive fine-tuning.

## 📁 Repository Contents
- **Prompts**: Modular Markdown files for Domain, Pedagogical, and Socratic layers.
- **Data**: Test battery & results log of the 125-response ablation study.

## 🚀 Usage
To replicate the FULL stack configuration, concatenate the files in `prompts/` in the following order:
1. `domain_layer.md`
2. `pedagogical_layer.md`
3. `notation_layer.md`
4. `socratic_stack.md`
