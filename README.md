
# TAP-VQA: Structured Attribute Prompting for Zero- and Few-Shot Visual Question Answering

## Overview

TAP-VQA (Tree-based Attribute Prompting for VQA) is a research project exploring structured prompting strategies for improving zero-shot and few-shot generalization of Vision-Language Models (VLMs) on unseen multimodal datasets.

Inspired by the ICLR 2025 paper *"Tree of Attributes Prompt Learning for Vision-Language Models"*, this project adapts the Tree of Attributes Prompt (TAP) framework from image classification to the Visual Question Answering (VQA) setting.

We design structured, multi-step prompts that guide VLMs through systematic visual reasoning before generating answers.

---

## Motivation

While modern Vision-Language Models achieve strong zero-shot and few-shot results, they often struggle with:

- Complex visual reasoning
- Noisy real-world data
- Domain-specific datasets (e.g., medical or educational VQA)
- Unseen question distributions

This project investigates whether structured attribute prompting can improve generalization performance across unseen domains.

---

## Methodology

Instead of directly asking a VLM a question about an image, TAP-VQA introduces:

1. **Hierarchical Attribute Decomposition**
   - Object-level attributes
   - Scene-level attributes
   - Contextual cues

2. **Multi-Step Structured Prompting**
   - Step 1: Visual attribute extraction
   - Step 2: Structured reasoning
   - Step 3: Question-aware answer generation

3. **Zero-shot and Few-shot Evaluation**
   - No fine-tuning
   - Limited example prompting
   - Cross-domain generalization testing

Evaluation is conducted using **VLMEvalKit**.

---

## Datasets

We evaluate TAP-VQA on diverse VQA datasets:

- **VizWiz-VQA** (Real-world, low-quality images)
- **TQA** (Textbook Question Answering - educational domain)
- **VQA-RAD** (Medical Visual Question Answering)

These datasets allow evaluation across noisy, educational, and medical domains.

---

## Experimental Setup

- Vision-Language Models 
- Zero-shot evaluation
- Few-shot prompting
- Performance comparison:
  - Baseline prompting
  - TAP structured prompting

Metrics:
- Accuracy
- Domain generalization performance
- Error analysis


