# NLP-LLM-Alignment-FineTuning-PEFT-DPO
Comparative study of LLM alignment using Full Fine-Tuning, Parameter-Efficient Fine-Tuning (Q-LoRA), and Direct Preference Optimization (DPO) on code generation and behavioral safety tasks.

## Objective
This repository presents an experimental deep dive into the trade-offs and complexity of aligning Large Language Models (LLMs).

It implements and compares three post-training pipelines:

1. **Full Fine-Tuning (FFT)** with a small encoder model and language modeling (LM) head.
2. **Parameter-Efficient Fine-Tuning (Q-LoRA/SFT)** for skill acquisition.
3. **Direct Preference Optimization (DPO)** for behavioral alignment and safety.

## Goal
Observe how training paradigms (FFT, PEFT/SFT, DPO) impact model compliance and safety.
