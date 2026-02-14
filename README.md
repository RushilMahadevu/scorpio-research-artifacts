# Scorpio: Verifiable Socratic Scaffolding for Physics LLMs

This repository contains the research artifacts for the paper: 
*"Scorpio: A Verifiable Framework for Enforcing Socratic Scaffolding in Physics LLMs Beyond Fine-Tuning."*

## 🔬 Overview
Scorpio is a modular constraint architecture designed to bridge the "helpfulness-learning gap." 
By layering inference-time rules, we achieve a **0% Direct Answer Rate** without expensive fine-tuning.

## 📁 Repository Contents
- **Prompts**: Modular Markdown files for Domain, Pedagogical, and Socratic layers.
- **Data**: CSV logs of the 125-response ablation study, including expert validation scores.
- **Rubric**: The 5-point Pedagogical Quality rubric used in the blinded multi-pass protocol.

## 🚀 Usage
To replicate the FULL stack configuration, concatenate the files in `prompts/` in the following order:
1. `domain_layer.md`
2. `pedagogical_layer.md`
3. `notation_layer.md`
4. `socratic_stack.md`