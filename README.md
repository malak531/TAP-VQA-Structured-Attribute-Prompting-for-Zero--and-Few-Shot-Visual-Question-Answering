# TAP-VQA: Structured Attribute Prompting for Zero- and Few-Shot Visual Question Answering

## Author
Tong Ding, Wanhua Li, Zhongqi Miao, Hanspeter Pfister

---

## Problem Statement

Vision-Language Models (VLMs) have shown strong performance in zero-shot and few-shot Visual Question Answering (VQA). However, their ability to generalize to unseen datasets, domain-specific tasks, and complex multimodal reasoning scenarios remains limited.

In many cases, VLMs struggle when handling noisy real-world images, educational content, or medical visual data. This project investigates whether structured prompting can improve generalization performance across such unseen domains.

---

## Project Idea

This project proposes TAP-VQA (Tree-based Attribute Prompting for VQA), a structured prompting framework inspired by the "Tree of Attributes Prompt Learning for Vision-Language Models" approach.

Instead of directly prompting a model to answer a question about an image, TAP-VQA introduces hierarchical attribute decomposition and multi-step reasoning:

1. Extract relevant visual attributes.
2. Organize them into a structured representation.
3. Guide the model through reasoning before generating the final answer.

The goal is to evaluate whether structured attribute prompting improves zero-shot and few-shot generalization of VLMs across diverse VQA datasets.

---

## Brief Overview

This project will:

- Adapt the Tree of Attributes prompting method to the VQA task.
- Evaluate performance on multiple unseen multimodal datasets.
- Compare baseline prompting vs. structured attribute prompting.
- Analyze generalization performance in zero-shot and few-shot settings.

The evaluation will be conducted using VLMEvalKit on datasets including VizWiz, TQA, and VQA-RAD.

